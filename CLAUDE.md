# 專案說明（給 Claude Code）

- 這是「資遣不求人」計算器，全部程式碼都在 `index.html`（HTML + CSS + 原生 JS，無框架、無建置步驟）。
- 介面語言：繁體中文（台灣用語）。金額格式 `NT$ 12,345`。
- 顏色一律用 `:root` 的 CSS 變數，並同時維護淺色與深色兩組值。
- 計算邏輯在 `<script>` 內：`ymd()` 年資、`noticeDays()` 預告天數、`jobLeave()` 謀職假、`annual()` 特休天數。
- 修改計算公式後，請用 README.md 的「驗算案例」確認數字不變。
- 法條連結格式：`https://law.moj.gov.tw/LawClass/LawSingle.aspx?pcode=N0030001&flno=<條號>`（勞基法 N0030001、勞退條例 N0030020、就服法 N0090001）。
- 本機預覽：`open index.html`，或 `python3 -m http.server` 後開 http://localhost:8000
