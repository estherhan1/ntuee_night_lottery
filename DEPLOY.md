# 🚀 部署指南

## 步驟 1: 在 GitHub 創建新倉庫

1. 前往 https://github.com/new
2. 倉庫名稱填寫：`ntuee_night_lottery`
3. 描述（可選）：台大電機之夜 2026 抽獎系統
4. 選擇 **Public**（公開）
5. **不要**勾選 "Add a README file"、"Add .gitignore"、"Choose a license"
6. 點擊 "Create repository"

## 步驟 2: 推送程式碼到 GitHub

你的專案已經準備好了！請在你的電腦終端機執行以下指令：

### 如果你已經下載了專案檔案：

```bash
cd ntuee_night_lottery
git remote add origin https://github.com/estherhan1/ntuee_night_lottery.git
git push -u origin main
```

### 如果需要輸入帳號密碼：

GitHub 現在使用 Personal Access Token (PAT) 而非密碼。

**創建 Token 的步驟：**
1. 前往 https://github.com/settings/tokens
2. 點擊 "Generate new token" > "Generate new token (classic)"
3. Note: 填寫 "ntuee_night_lottery"
4. Expiration: 選擇有效期限
5. 勾選 `repo` 權限
6. 點擊 "Generate token"
7. **複製 Token**（只會顯示一次！）

推送時使用 Token 作為密碼：
- Username: estherhan1
- Password: 貼上你的 Token

## 步驟 3: 啟用 GitHub Pages

1. 前往 https://github.com/estherhan1/ntuee_night_lottery
2. 點擊 "Settings"（設定）
3. 左側選單點擊 "Pages"
4. Source 選擇：`Deploy from a branch`
5. Branch 選擇：`main` 和 `/ (root)`
6. 點擊 "Save"

**等待 1-2 分鐘後，你的網站將發佈在：**
🌐 **https://estherhan1.github.io/ntuee_night_lottery/**

## 步驟 4: 測試網站

前往上面的網址，確認抽獎系統正常運作！

## 需要更新網站？

如果之後需要修改網站內容：

```bash
# 修改檔案後
git add .
git commit -m "描述你的修改"
git push
```

GitHub Pages 會自動重新部署，通常 1-2 分鐘內生效。

---

## 常見問題

**Q: Push 時出現 Authentication failed？**
A: 確保使用 Personal Access Token 而非密碼。

**Q: 網站沒有更新？**
A: 等待 1-2 分鐘，清除瀏覽器快取後重新整理。

**Q: 404 錯誤？**
A: 確認 GitHub Pages 設定中 Branch 選擇 `main` 和 `/ (root)`。

---

祝你的電機之夜抽獎活動順利！🎉
