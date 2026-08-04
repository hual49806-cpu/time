# 時光修復局－國語版 V1

已整合：
- 南一版五上國語第一課〈幸福筆記本〉100 題題庫
- 男女修復員角色（待機、攻擊、勝利、受傷）
- 四個關卡背景
- 四位 Boss 的待機、受傷、死亡畫面
- 每關隨機抽取 10 題，共 40 題
- 重新挑戰、返回章節、前往下一關
- 金幣、時光碎片、生命值與自動存檔

## 本機試玩
解壓縮後直接開啟 `index.html`。

## 部署到 GitHub Pages
1. 在 GitHub 建立新的 repository。
2. 將本資料夾內的所有檔案上傳到 repository 根目錄。不要只上傳外層資料夾。
3. 開啟 `Settings` → `Pages`。
4. 在 `Build and deployment` 選擇 `Deploy from a branch`。
5. Branch 選 `main`，資料夾選 `/root`，按下 Save。
6. 等待約數分鐘，GitHub Pages 會顯示遊戲網址。

## 題庫位置
- `data/questions.json`：原始 JSON
- `data/questions.js`：遊戲直接讀取版本

## 圖片位置
- `assets/backgrounds/`
- `assets/characters/`
- `assets/bosses/`

## 通關規則
每關 10 題，答對至少 7 題即通關。答錯會扣除 1 點生命值。
