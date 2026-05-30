# Site Manifest: huahkwang-history-site

## 專案基本資訊
- 專案名稱：huahkwang-history-site
- 網站名稱：華光寺｜歷史沿革
- 網站型態：小型多頁靜態網站
- 語言版本：繁體中文
- 部署方式：GitHub Pages
- 命名規則：全部統一使用 `huah kwang`，不再使用舊拼法

## 網站目的
本網站為「華光寺歷史沿革」主題的小網站，先獨立完成一個可閱讀、可導覽、可延伸閱讀的歷史模組。  
此網站之後將作為華光寺總網站中的一個子網站，再掛到更上層的華光寺主頁之下。

## 網站頁面結構
1. `index.html`  
   歷史沿革首頁，採摘要導覽形式。

2. `history-background.html`  
   歷史背景詳細頁。

3. `founding-monk.html`  
   創寺法師詳細頁。

4. `construction-process.html`  
   籌建過程詳細頁。

---

## 首頁內容定位
首頁不是完整長文頁，而是：
- 先給整體導言
- 三大主題各自給出短摘要
- 每段下方提供「延伸閱讀」
- 引導使用者進入詳細頁閱讀

首頁三大主題：
1. 歷史背景
2. 創寺法師
3. 籌建過程

首頁另有：
- Hero 主視覺
- 頁面導言
- 歷史意義簡述
- 頁尾

---

## 詳細頁內容定位
三個詳細頁分別承接首頁中的「延伸閱讀」。

每個詳細頁都要有：
- 頁面標題
- 該主題完整長文
- 對應圖片
- 上方返回區
- 下方返回區

返回區至少包含：
- 回歷史沿革（連回 `index.html`）

並預留：
- 回上一層主頁（未來接到華光寺總首頁）

---

## 檔案結構
```text
huahkwang-history-site/
├─ AGENTS.md
├─ content_manifest.md
├─ index.html
├─ history-background.html
├─ founding-monk.html
├─ construction-process.html
├─ assets/
│  ├─ css/style.css
│  ├─ js/script.js
│  └─ images/
└─ docs/
   ├─ final_copy_home.md
   ├─ final_copy_history-background.md
   ├─ final_copy_founding-monk.md
   └─ final_copy_construction-process.md
