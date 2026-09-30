# AI 應用規劃師 互動模擬考

一個單檔 HTML 的互動測驗網站，題庫來自 iPAS AI 應用規劃師（初級）歷屆公告試題，經人工逐題核對正確答案並撰寫詳解。

## 功能
- 目前題庫 351 題（已達成 300 題目標，持續擴充中），每輪隨機抽取 50 題
- 依科目篩選（科目一 / 科目二 / 全部）
- 作答後立即顯示正解與詳解
- 每輪結束顯示 9 大主題正確率分析，找出弱項
- 可重複「開始新一輪模擬」，從題庫重新洗牌抽題

## 部署方式（GitHub Pages）
1. 在 GitHub 建立一個新的 repository（例如 `ai-planner-quiz`），public
2. 把這個資料夾裡的 `index.html` 上傳到 repo 根目錄（可以直接在 GitHub 網頁上用 "Add file → Upload files" 拖曳上傳，不需要 git 指令）
3. 進入 repo 的 **Settings → Pages**
4. Source 選擇 `Deploy from a branch`，Branch 選 `main`，資料夾選 `/ (root)`，按 Save
5. 等 1-2 分鐘，頁面會出現在 `https://你的帳號.github.io/ai-planner-quiz/`

之後每次題庫更新，只要重新上傳覆蓋 `index.html` 即可，網站會自動更新。
