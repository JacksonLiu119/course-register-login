# 課程報名快速登入

這是一個靜態網頁工具，用來快速登入校方報名系統並開啟課程清單。

## 使用方式

1. 開啟 GitHub Pages 網址。
2. 第一次使用時輸入自己的帳號與密碼。
3. 在私人裝置上可勾選「僅在此瀏覽器保存帳密並自動登入」。
4. 按下登入按鈕後，頁面會前往課程清單。

帳密只保存在使用者自己的瀏覽器 `localStorage`，不會寫入 GitHub。請勿在公用電腦勾選保存。

若要清除 LINE 內建瀏覽器或其他瀏覽器保存的帳密，開啟：

```text
https://jacksonliu119.github.io/course-register-login/?reset=1
```

## 發佈到 GitHub Pages

1. 在 GitHub 建立新的 public repository，例如 `course-register-login`。
2. 將 `index.html`、`README.md` 和 `開啟快速登入.cmd` 上傳到 repository。
3. 開啟 repository 的 `Settings` > `Pages`。
4. 在 `Build and deployment` 的 `Source` 選擇 `Deploy from a branch`。
5. 選擇 `master` 或 `main` branch，以及 `/ (root)`，再按 `Save`。
6. 等待 GitHub Pages 完成部署。

網址通常會是：

```text
https://你的GitHub帳號.github.io/course-register-login/
```
