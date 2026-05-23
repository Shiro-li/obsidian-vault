# GitHub 新專案上傳流程

1. 進入專案資料夾
	cd 專案名稱

2. 初始化 Git
	git init

3. 加入所有檔案
	git add .

4. 建立版本紀錄
	git commit -m "first commit"

5. 連接 GitHub repository
	git remote add origin GitHub網址

6. 設定主分支
	git branch -M main

7. 上傳到 GitHub
	git push -u origin main

理解：
本地專案 → 建立 Git 管理 → 連接 GitHub → 上傳