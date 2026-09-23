# HandsFree

**Windows 桌面自動化工具,不用寫程式。** 把重複的滑鼠、鍵盤、網頁操作做成腳本,按一個鍵就自動完成。
參數用選的,不用自己打;不會編腳本也沒關係,用說的讓 AI 幫你寫。

**[English](README.md)** · **買斷價 9 USDT** · 免費試用 7 天

![HandsFree main window](https://github.com/user-attachments/assets/33c2a906-d9ca-4a07-8460-2a4948d0fd35)

## 功能

- **錄製與回放**:照平常操作一次,就變成可以重複執行的腳本
- **不用寫程式**:選命令、填參數,座標、顏色、圖片都直接在畫面上點選
- **找圖、找色、找文字(OCR)**:畫面上出現某個按鈕、顏色或文字才動作,內建文字辨識,不用另外安裝
- **網頁自動化**:直接操作網頁上的按鈕、輸入框、表格,網頁捲動或視窗大小改變都不影響
- **流程控制**:如果/否則、重複、逐一處理清單、子程式、背景同時監控
- **資料處理**:讀寫檔案、CSV 表格、剪貼簿、日期時間、文字與清單處理
- **🤖 AI 自動寫腳本**:把內建的「AI 指令包」貼給 ChatGPT、Gemini 等 AI,說你想做什麼,AI 寫好整支腳本,貼回來就能跑
- **熱鍵、排程、自動開始**:全域熱鍵啟動/停止,也能每天定時或視窗出現時自動執行
- **單步偵錯、中斷點、復原/重做**(Ctrl+Z / Ctrl+Y)
- **發佈給別人用**:把腳本和用到的圖片打包成一個資料夾,對方雙擊就能用
- **中文 / English 介面一鍵切換**
- 內建 11 課教學與 8 個範例腳本

### 看腳本執行

每一步執行時會亮起來,右邊的執行紀錄寫出每一步做了什麼。

![A script running, step by step](https://github.com/user-attachments/assets/909c13cc-7030-4bda-853d-469f1fa53484)

### 讓 AI 幫你寫腳本

![The AI writes the script for you](https://github.com/user-attachments/assets/9dbfe697-bc8f-4e83-bc5e-6501365ba6bc)

## 下載與安裝

1. 到 **[Releases](../../releases)** 下載最新版的 `HandsFree.zip`
2. 解壓縮到任何資料夾(整個資料夾要放在一起,不能只拿 exe)
3. 雙擊 `HandsFree.exe`

**系統需求**:Windows 10 / 11(64 位元)。網頁功能會使用電腦內建的 Microsoft Edge(或 Google Chrome)。
不需要安裝 Python 或其他軟體,文字辨識也已經內建。

**掃毒報告**:[VirusTotal 對 HandsFree.zip 的掃描結果](https://www.virustotal.com/gui/file/085c683a4303ba074c984e7e86c8cf9965d1addd8c95b8ec767dea8612e4de18) — 沒有任何防毒廠商判定為惡意。

### 第一次開啟會看到的提示

- **「Windows 已保護您的電腦」**(SmartScreen):程式還沒有數位簽章。點「**其他資訊**」→「**仍要執行**」。
- **「是否允許此程式變更您的裝置?」**:請按「是」。程式需要系統管理員權限,才能操作同樣以管理員權限執行的程式(例如部分遊戲)。
- 部分防毒軟體會對「會控制滑鼠鍵盤」的程式特別警告,這是自動化工具的正常現象。

## 價格與開通

| | |
|---|---|
| **免費試用** | 第一次開啟起 7 天,所有功能都能用 |
| **買斷授權** | **9 USDT**,加密貨幣一次付清,永久使用,不用月費 |

1. 寄信到 **[99handsfree@gmail.com](mailto:99handsfree@gmail.com)** 購買,回信會告訴你付款方式。
2. 付款後會收到一組卡號。
3. 在 HandsFree 打開開通視窗(試用期滿會自動出現,或從「說明 → 開通 / 授權狀態」打開),按「貼上卡號」→「開通」。

開通完全離線,不需要網路。

## 使用注意

請只在你有權限的電腦、帳號與網站上使用自動化,並遵守各網站、遊戲的服務條款。

## 第三方元件

HandsFree 本身為閉源軟體。程式隨附的開放原始碼元件(Qt / PySide6、pynput、Tesseract OCR、OpenCV、NumPy 等)依各自授權條款散佈,
清單在下載包的 `第三方元件授權.txt`,條款全文在 `licenses` 資料夾。其中 LGPL 元件(Qt、pynput)可以自行替換:Qt 是獨立的 DLL 檔,pynput 以原始碼放在 `pynput` 資料夾。
