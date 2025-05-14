# SessionStorage 測試靜態網站

用於測試在開啟新頁面（如新分頁或新視窗）時，`sessionStorage` 的行為是否會繼承的簡單網頁。

## 📁 專案結構

```
.
├── index.html # 主頁面，可輸入並儲存 sessionStorage 值
└── test.html # 測試頁面，顯示從 sessionStorage 讀取的值
```

## 🔧 使用方式

1. 使用瀏覽器開啟 `index.html`。
2. 在輸入框輸入任意文字。
3. 點擊「存入 sessionStorage」按鈕，將值儲存至當前分頁的 `sessionStorage`。
4. 點擊「開啟新分頁 test.html」按鈕，在新分頁或新視窗中開啟 `test.html`。
5. 觀察新頁面是否能夠讀取 `sessionStorage` 中儲存的值。
