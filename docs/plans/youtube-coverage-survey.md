# YouTube 覆蓋度盤點 —「私人飛行員(PPL)學科教學 + 飛行裝備選購」策展課

調查日期：2026-08-08
方法：`yt-dlp --flat-playlist "ytsearch30:<query>"`，英文 16 組關鍵字 + 中文 8 組關鍵字（另加 4 組追加關鍵字），共約 803 筆搜尋結果（英文 604 支去重影片、中文 199 支）；輔以 WebSearch 查頻道背景。原始搜尋結果存於 `/private/tmp/claude-501/-Users-kansasray-claude/1e3c149f-7245-461e-b12a-927bb1e360ce/scratchpad/yt-ppl-survey/`（本機暫存，非專案內）。

**總結論先講**：英文供給非常厚，足以撐起一整個「學科核心」部；裝備選購有廣度但業配/興趣錯位需要篩選；中文供給幾乎是空的——沒有一個頻道在教 PPL 學科，能用的中文素材是輕航機、海外自訓 vlog、跟航空公司機師招募相關的內容，量體撐不起獨立一整章的中文教學內容。

---

## 1. 主力頻道前 8-10 個

| 頻道 | 內容偏向 | 量體與觀察 |
|---|---|---|
| **Free Pilot Training**（Josh Campbell，前軍職 CFI/AGI） | 成套 ground school：「PPL Lesson N」「PPL Ground Lesson N」編號課程，見過 Lesson 1–61+ | 本次調查命中率最高（58 次跨查詢），單支觀看數 10 萬–130 萬，官網稱「YouTube 上最完整的免費 PPL 地面學校」。**最適合當學科核心的骨幹頻道** |
| **MzeroA Flight Training**（Jason Schappert） | 學科講解 + 考照心法，品牌老字號 | 18 年經營、官網稱認證超過 55,000 名飛行員；本次命中 41 次，涵蓋無線電、E6B、失速螺旋等主題 |
| **FLY8MA.com Flight Training** | 免費 ground school（Sport/Private/Instrument/Commercial 都有） | 命中 36 次；另有姊妹頻道「FLY8MA」做 Cessna 170 灌木叢飛行 vlog（實飛/裝備向，非學科） |
| **Pilot Institute Airplanes** | 學科講解 + 空域/氣象/系統，橫跨最多主題查詢 | 官網稱訓練超過 45 萬人；命中 48 次，是廣度最高的頻道之一 |
| **SkyEagle Aviation Academy** | 成套 ground school：「Lesson 1」\~「Lesson 28+」，單集 30–80 分鐘 | 命中 17 次，觀看數中等（1.2 萬–75 萬） |
| **Pilot Certified** | 兩條成套系列：「Free Private Pilot Ground School Lesson 1–18」+「Mock Checkride Task A–H」 | 頻道較小（觀看數千級），但**編號完整、覆蓋學科全貌**，且有專門的模擬口試系列 |
| **FlightInsight** | 單主題精緻短片（降落、空域、E6B、跨場飛行規劃） | 命中 17 次，個別影片可達 220 萬觀看（"How to Land an Airplane"），適合當「單元補充片」而非主線 |
| **ERAU SpecialVFR** | Embry-Riddle 航空大學官方製作（Aviation 101、Aircraft Systems、Airspace Lesson） | 官方機構出品，可信度最高，但覆蓋是片段式（只找到系統/空域幾集），非完整成套 |
| **Phillip J. Murphy** / **FlyingForHours** | **FAA 官方手冊逐章朗讀**（PHAK + Airplane Flying Handbook，"Audio/Video Book"、"Full Audio Read-Along"） | 見第 5 項細述 —— 這是對照官方文件的關鍵軸 |
| **King Schools** | 老牌訓練機構，E6B 14 集教學系列 + 個別學科主題 | 命中 9 次，內容扎實但非全套 ground school |

次要但值得記錄：**Airplane Academy**（創作者向 vlog + 建議文，"Complete Private Pilot's License Process" 這類總覽片觀看數高）、**PilotEssentials** / **Cheese Pilot**（模擬口試 mock oral/checkride 專門戶）、**Sporty's Pilot Shop**（航材零售商自有頻道，見第 6 項陷阱）、**Angle of Attack**（高製作學生飛行紀錄片風格，但本次只找到 2 支，非成套）。

---

## 2. 中文供給

**量級**：英文 604 支 vs 中文 199 支命中（同樣搜尋量下）。時長分布上中文更懸殊：中文命中 96% 落在 15 分鐘以內（短片/vlog），英文只有 62%；英文有 38% 落在 15 分鐘以上（含完整學科課），中文只有 4%。

**核心結論：找不到任何一個中文頻道在做 PPL 學科系統教學。** 找到的中文素材可歸三類，都撐不起一整章：

1. **台灣輕航機教學**——`Sega Ho何孟揆` 有真正的 4 集成套學科課（L1 法規、L2 飛機性能、L3 飛行原理與載重平衡、L4 飛航安全與罰則，各 22–50 分鐘），繁中、台灣脈絡，但觀看數僅 45–220，是個幾乎沒人看過的小頻道。`威翔航空AeroJones Aviation`（台灣輕航機廠商/飛行俱樂部，含鎮江中國分部內容）多為 80–450 秒的行銷/學員日記短片，非教學。
2. **海外自訓 PPL vlog**——`Alvin飛翔大叔`（澳洲雪梨 Bankstown，Piper Archer/PA28，粵語/國語）記錄真實 nav/solo 訓練進度，是「實際路徑」敘事素材但非教學；`懶人包er`（空巴機師）「PPL 預備課」系列只做了 3 集（每集約 12 分）就轉向 A320 系統內容，無以為繼。
3. **航空公司機師招募**（易與 PPL 搜尋混淆但語境不同）——`FTTW培訓機師考試情報站`「踏入前艙」系列 30+ 集，內容是華航/長榮/星宇培訓機師招募流程/體檢/面試，只有 1 集（EP15，5:45 分鐘）擦邊碰到「PPL 地面學科理論課」，深度不足；`單單機長說`（現職機長，~180 集）多為航空公司職涯經驗分享，非 GA/PPL 學科。

簡中供給（`美国飞行教练杰瑞米`、`航咖`、`飞行员欧文`等）多為個別「美國學飛心得」訪談/敘事影片，10–20 分鐘、每頻道僅個位數相關影片，同樣不成系統。

**建議**：中文章節不要規劃成「教學單元」，改規劃成「敘事/心得單元」（Alvin/單單機長挑選相關集數）+「台灣輕航機專節」（Sega Ho 4 集為骨幹，補 AeroJones 花絮）+「策展者自寫繁中導讀橋接英文 PHAK 對照軸」。不要預期能用純中文影片填滿一整章教學內容。

---

## 3. 學科主題逐項厚度

| 主題 | 厚度 | 代表頻道 |
|---|---|---|
| 空氣動力學 | **豐富** | Free Pilot Training、Pilot Institute、FlightInsight、Phillip J. Murphy（PHAK Ch.4/5 朗讀）、MIT OpenCourseWare 講座 |
| 飛機系統與儀表 | **豐富** | ERAU SpecialVFR（系統編號系列：電力/飛控/引擎）、Epic Flight Academy、Free Pilot Training、PHAK Ch.7/8 朗讀 |
| 航空氣象 | **豐富** | SkyEagle、Pilot Institute、Pilot Certified、Moltar Aviation、King Schools 皆有專集；PHAK Ch.12/13 朗讀 |
| 領航（VFR圖/E6B/航線規劃） | **豐富** | King Schools 14 集 E6B 系列、Sporty's、FlightInsight、Free Pilot Training「E6B 完整指南」、跨場飛行規劃逐步教學 |
| 法規與空域 | **豐富** | Free Pilot Training 多次命中空域主題、ERAU「Airspace Lesson 1」、Mr. Mig's Classroom、FlightInsight「Learn Airspace Quickly」 |
| 無線電通訊程序 | **中等偏豐富** | MzeroA、FlightInsight、Fly With The Guys、King Schools「不塔台機場通聯」——夠用但不像空域/氣象那樣有多個編號成套系列 |
| 人因與 ADM | **中等** | 較零散，多為個別 CFI 單支影片（Phillip J. Murphy PHAK Ch.2 朗讀、Jeremy Maurer、Epic Flight Academy），沒找到大頻道的深度成套系列，PHAK 逐章朗讀是骨幹 |
| 失速螺旋等飛行操作理論 | **中等** | 零散單支影片（SmartPilot、"What Causes an Airplane to Spin"），AFH Ch.3/4（基本操作/失控恢復）朗讀涵蓋理論但缺乏視覺示範深度 |

---

## 4. 裝備選購厚度

| 子類 | 厚度 | 觀察 |
|---|---|---|
| 搖桿/軛、方向舵踏板 | 中等 | 買家指南存在，但集中在飛行模擬玩家頻道（G-LOC Media、Blu Games、Aus Flight Simmer），偏「遊戲玩具評測」語境，非「PPL 程序練習器」框架，需人工篩選 |
| 航空耳機（DC/Bose/Lightspeed） | 中等，**業配濃度高** | 單一搜尋中 `Sporty's Pilot Shop`（航材零售商自有頻道）就佔 11/30 命中；獨立評測（Fastback Flying、AVweb、Taking Off）相對薄，需明確標示廠商自製 vs 獨立比較 |
| E6B 機械 vs 電子 | **豐富** | King Schools 14 集系列、Sporty's 操作教學、Free Pilot Training「完整指南」——這個子題意外地厚 |
| 平板 EFB（ForeFlight/SkyDemon） | 稀薄偏中等 | 找到零星評測（Stefan Drury「Top 10 iPad Tips」等），但 ForeFlight vs SkyDemon 直接對比內容薄；SkyDemon 偏英國語境、ForeFlight 偏美國語境，沒有針對台灣讀者的比較內容 |
| 家用模擬器（MSFS 2024/X-Plane 12）當 PPL 程序練習器 | 中等，**框架錯位** | MSFS/X-Plane 內容量體龐大，但絕大多數是「飛行模擬嗜好」框架（VR、模組、場景），「拿來當 PPL 程序練習器」的教學/評測只是這片海洋裡的少數，需要仔細篩選才挑得出對的影片 |

**Q4 總結**：裝備選購**可以撐起一節、但不夠獨立撐起一整章高品質內容**——五個子類都有東西，但深度不均、業配與興趣錯位需要人工篩選，不是「開了配額就自動填滿」。

---

## 5. 官方免費教材（PHAK / Airplane Flying Handbook）

**確認找到兩個逐章朗讀官方手冊的頻道**：
- **Phillip J. Murphy**（品牌 "AGPIAL Audio/Video Book"）——PHAK 與 Airplane Flying Handbook 都有，樣本涵蓋 PHAK 第 1、2、4、5、6、7、8、11、12、16 章，AFH 第 1、3、4、5、8、9、10、13、17 章
- **FlyingForHours**（品牌 "Full Audio Read-Along"）——涵蓋 PHAK 第 1、5、7、8、10、11、12、13、14、16 章，AFH 第 1、3、5、12、18 章

**重要提醒**：這兩者是**逐字朗讀手冊原文的錄音**（單集 29 分鐘–3.3 小時），不是「講解式教學」影片——適合當「聽原文 / 官方文件對照軸」，但不能取代有圖表示範的教學影片。觀看數不高但穩定（數百–4.5 萬），顯示是真實的「讀書會/開車聽」小眾用途。

**建議用法**：每個學科單元可配「教學影片（Free Pilot Training / Pilot Institute / SkyEagle 等）+ 對應章節的官方朗讀（Phillip J. Murphy / FlyingForHours）」雙軌，做成「先聽官方原文、再看教學拆解」的單元結構。**未逐一核對兩頻道是否 100% 覆蓋全部 16 章 PHAK + 全部 AFH 章節**——樣本顯示涵蓋率高但非普查，正式訂單元前建議請人力逐一核對這兩個頻道的完整播放清單。

---

## 6. 陷阱

- **長篇直播/podcast**：FLY8MA 另有 Spreaker podcast 陣地；懶人包er 有「Live with Restream」直播檔。量不算主流，但存在——>2小時的英文影片有 16/604，建議逐支核對是否為直播 VOD（通常內容鬆散、不適合剪成單元）。
- **Checkride 恐懼行銷**：`PilotEssentials`、`Cheese Pilot` 是模擬口試/checkride 專門戶（單集 30–90 分鐘）。從標題樣本看語氣偏實務準備而非恐嚇行銷，但建議挑用前抽看 2-3 支確認語氣。
- **裝備業配濃度**：`Sporty's Pilot Shop`（航材零售商自有頻道）是本次調查裝備類搜尋命中最多的單一頻道（跨查詢共 31 次），標題常是自家產品操作教學/開箱——策展時要明確標「廠商自製」vs「獨立評測」，不能當獨立第三方意見引用。
- **內容過時**：實測發現 Airplane Flying Handbook 同時存在 **-3B 版與 -3C 版**的朗讀/教學影片並存於同一批搜尋結果中（FAA 已改版），舊版影片的空域/法規細節可能與現行規定不一致。**規則**：每支選用影片要標註對應的手冊版本/年份，2021 年前的空域與氣象服務類影片需額外複核現行規定。
- **關鍵字碰撞**：
  - 中文「超輕型載具」與電動代步車、空拍機、軍用輕型戰車、遊戲載具等內容嚴重碰撞，幾乎不可用；輕航機相關搜尋務必直接用「輕航機」或「LSA」。
  - 中文「自訓機師 心得 部落格」這類長句查詢完全失效——回傳的是健康、短劇、旅遊等不相關內容，證實中文搜尋要用短的 2-3 詞組合（如「輕航機 教學」「學飛 vlog」），長句/口語化查詢在 YouTube 演算法下表現很差。
  - 英文「MSFS 2024 flight training」「X-Plane 12 flight training」與泛用飛行模擬嗜好內容（VR 評測、模組、場景）大量碰撞，「拿模擬器練 PPL 程序」這個精確意圖的內容只佔其中一小部分，需人工篩選。

---

## 7. 影片長度分布與建議 audit 門檻

**英文（604 筆跨查詢命中，含重複計次，非去重普查——僅供分布參考）**：
0–5 分鐘 136 / 5–15 分鐘 239 / 15–30 分鐘 130 / 30–60 分鐘 118 / 1–2 小時 81 / 2 小時以上 16

**中文（199 筆跨查詢命中，同上）**：
0–5 分鐘 96 / 5–15 分鐘 95 / 15–30 分鐘 30 / 30–60 分鐘 17 / 1–2 小時 2 / 2 小時以上 0

**建議 audit 門檻（依內容型態分層，不要用單一門檻套全課）**：

| 內容型態 | 建議 min–max |
|---|---|
| 學科核心單主題解說片（如「空域解說」「E6B教學」） | 8–35 分鐘（低於 8 分鐘常是預告/淺講，高於 35 分鐘容易變成完整章節課，適合另歸類） |
| 完整成套 ground school「章節課」（SkyEagle/Pilot Certified 式編號課） | 20–90 分鐘 |
| PHAK/AFH 官方手冊逐章朗讀（補充/選讀用，非核心分鐘數) | 25 分鐘–3.5 小時（本質就長，當作可選聽讀資源，不計入核心課時） |
| 裝備評測/開箱 | 5–20 分鐘（超過此區間常是直播問答或深度嗜好向內容，較難剪成單元） |
| 中文 vlog / 自訓心得 / 實際路徑敘事 | 5–15 分鐘（貼合實測中文供給的真實分布，門檻拉高會混進不相關的航空公司職涯內容） |

---

## 每部 / 每章配額建議（假設 3 部 × 10–11 章）

供給分析顯示三部的「能撐起的密度」差異很大，**不建議三部用同一套配額**，否則學科核心部會浪費厚供給、實務與台灣路徑部會被迫灌水湊數。

### 第一部：入門與裝備（10–11 章）
- 入門總覽類章節（如何成為 PPL、完整流程、第一堂課）：英文供給豐富，每章 **4–6 單元**沒問題。
- 裝備類章節（搖桿/軛、耳機、E6B、EFB、家用模擬器）：厚度中等且業配/興趣錯位需篩選，建議每章 **3–4 單元**（不要訂到 6+，篩選成本會拖垮排程），且耳機與模擬器兩章要預留額外時間人工排除業配/嗜好向噪音。
- 若這部硬性要湊到 10–11 章，裝備子題可能撐不了那麼多獨立章節——建議把「搖桿/踏板」與「家用模擬器」合併成一章，或另闢「入門總覽」子章節補數量，避免出現有章節但沒東西可放的空章。

### 第二部：學科核心（10–11 章，對應類 PHAK 章節架構）
- 這部**供給最厚**，是整個課程真正能撐起質量的骨幹。空氣動力學、飛機系統、氣象、領航、法規空域這五個主題可以做到每章 **6–10 單元**（教學片+官方朗讀對照+補充片）。
- 無線電通訊程序：中等厚度，每章 **4–5 單元**。
- 人因/ADM、失速螺旋等飛行操作理論：偏薄，每章建議壓低到 **3–4 單元**，不要跟厚章用同樣密度，硬湊會拉進不相關或品質不一的內容。

### 第三部：實務與台灣路徑（10–11 章）
- Checkride 準備類章節（英文）：供給足夠，每章 **4–6 單元**（PilotEssentials/Cheese Pilot/Gold Seal 等）。
- 中文相關章節（台灣輕航機、海外自訓心得、中文資源彙整）：**這是全課程供給最薄的部分**，每章建議壓到 **2–4 單元**，且部分規劃中的章節可能需要合併——例如「台灣輕航機」單靠 Sega Ho 的 4 集 + AeroJones 花絮撐不起獨立厚章；「海外自訓心得」單靠 Alvin飛翔大叔 + 單單機長說挑選集數也撐不了太多單元。**建議把「台灣輕航機」與「海外自訓心得」考慮合併成 1-2 章而非規劃成 3-4 個獨立章節**，否則會出現內容明顯比其他部單薄、東拼西湊的章節。
- 若堅持要 10–11 章都填滿，中文相關章節將不可避免地需要策展者自寫繁中導讀/文字內容來補位，而非單純倚賴既有影片——這點建議先跟 Kansas 確認是否可接受（框架允許文字補充，但改變了「以影片為主」的課程性質）。

---

## 資料來源檔案（本機暫存，如需複查）
- 搜尋原始輸出：`/private/tmp/claude-501/-Users-kansasray-claude/1e3c149f-7245-461e-b12a-927bb1e360ce/scratchpad/yt-ppl-survey/`（`res_*.txt` 為英文查詢，`cn_res_*.txt`/`cn2_*.txt` 為中文查詢，格式 `id|duration(秒)|view_count|channel|title`）
