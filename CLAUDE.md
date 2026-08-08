# pilot-course

**這個 repo 是 `kansasray/gym-course`(我們自己 fork 的 curate-course 框架)的 clone,裡面放一門課:`courses/pilot/`「飛行員之路」。** 框架主題無關,負責建置、稽核、連結驗證、SEO 與部署;課程內容全在 `courses/pilot/`。上游附的 `courses/gym/` 是對照範例,不要動。

課程:繁中介面與導讀 + 英文為主的教學影片,PPL(私人飛行員)學科 + 裝備選購 + 台灣考照路徑。3 部 10 章(入門與裝備 2 章/學科核心 6 章/實務與台灣路徑 2 章),24 單元 43 延伸。官方對照軸是 FAA 免費手冊(PHAK/AFH),因框架的 citations 只認 PMID/DOI,手冊對照一律寫在 `why` 自由欄位,**不建 citations 檔、不宣告 `grades`**(立場頁的 `evidence_grade` 直接放中文標籤,靠 `gradeOf()` fallback 顯示,同 atak-course 的解法)。

## 指令

```bash
COURSE=courses/pilot make build audit      # 一律帶 COURSE=
COURSE=courses/pilot make verify           # 打真實 oEmbed
COURSE=courses/pilot COOKIES_BROWSER= uv run python src/build/fetch_meta.py
```

## 這門課的策展決策(改動前先讀)

- **配額是照供給訂的,不均勻是刻意的**:學科核心章 3 單元、裝備與台灣章 2 單元。盤點在 `docs/plans/youtube-coverage-survey.md`(604 英文/199 中文命中):中文 PPL 教學供給實質為零,唯一的台灣輕航機系列(Sega Ho)觀看數兩位數,CH10 照收並在 why 說明「小眾非低質」。
- **PHAK 逐章朗讀頻道(Phillip J. Murphy、FlyingForHours)刻意不進格子**——那是朗讀不是教學,只在 why 提及手冊章節。
- **法規章(CH7)的時效處理**:影片提到具體數字時 why 註明「以現行 FAR 為準」+ 上傳日期;AFH 有 -3B/-3C 兩版並存,引用寫「現行版」不寫版號。
- **零售商內容(Sporty's 耳機指南)有收但 why 標明身分**,判斷打折。
- **立場頁 4 則**(`data/stance.json`),兩則標「對課程不利」:裝備不用急著買、中文教材撐不起。
- 導讀時間碼一律取自 `yt-dlp %(chapters)j` 章節標記、自動字幕逐句定位、或影片描述欄的創作者時間戳;拿不到就寫「整支看完」,**無編造**。

## 框架陷阱(承襲 atak-course/Azimuth 踩過的,此 repo 適用)

1. `ui.facetLabel` 與 `ui.tabs.stance` 是 index.html 無條件引用的,不用也要填
2. 首頁立場區塊無條件渲染(render.js),不寫立場頁會出現孤兒空塊 → 本課已寫
3. `ui.unitTypes` 的 id 避開 `field`/`demo`(撞框架掃描與 paywall-core.js)→ 本課用 concept/procedure/pathway;kinds 用 lecture/practice/story
4. 宣告 `grades` 會觸發 seo.py 的分級計數檢查(立場聲明不掛單元導致對不上)→ 不宣告,標籤直接進 evidence_grade
5. `make serve` port 8899 可能被 Azimuth 或其他課佔用,驗證前先 `curl localhost:PORT | grep '<title>'` 確認是哪門課
6. `fetch_meta.py` 預設借 Chrome cookie 會被 macOS TCC 擋 → `COOKIES_BROWSER=` 走無 cookie
7. `make og` 需要 imagemagick;`make deploy` 前要先手動 `npx wrangler@4 pages project create pilot-course --production-branch main`
8. 平行策展的波與波之間必須彙整**已用 video ID 禁用清單**(本課三波:CH1/3/4/5 → CH2/6/7/8 → CH9/10,全程零重複);共用 scratchpad 清理時**只刪自己下載的檔**

## 狀態(2026-08-08 完成)

- **已上線 https://pilot-course.pages.dev**(Pages 專案 `pilot-course`,production branch `main`,wrangler 手動部署;新部署先回 522 屬正常冷啟動)
- 3 部 10 章 24 單元 67 支影片、18 小時整;`make verify` 連結 67/67、`make audit` 0 錯誤 1 警告(Sega Ho 165 觀看,刻意收錄)、89 tests 全過
- 67 支零跨章重複;38 個頻道,最大佔比 11.9%
- **GitHub**:`kansasray/pilot-course`(public,Discussions 已開,giscus 設定已填但 **App 待 Kansas 安裝**:https://github.com/apps/giscus)
- `upstream` 指向 `kansasray/gym-course`(自己的框架 fork)
