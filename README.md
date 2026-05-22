# hello-world

輕量示範儲存庫。以下是取得專案與確認本機環境的步驟。

## 環境需求

- [Git](https://git-scm.com/) 2.x 或以上  

本儲存庫目前不包含 Node、Python、Docker 等其他建置或執行依賴。

## 取得程式碼

HTTPS：

```bash
git clone https://github.com/mengchu35/hello-world.git
cd hello-world
```

SSH：

```bash
git clone git@github.com:mengchu35/hello-world.git
cd hello-world
```

## 設定完成後請自檢

```bash
pwd
git status
ls -la
```

預期在專案根目錄可看到 `readme.txt`；本說明以 `README.md` 為準。

## 協作分支（選讀）

從最新 `master` 開分支再送 PR：

```bash
git fetch origin master
git checkout -b your-branch-name origin/master
```

---

若之後新增可編譯或可執行的程式，請在此檔補上對應的安裝、建置與執行指令。
