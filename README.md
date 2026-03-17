# GIT指令集練習


### Markdown
- https://hackmd.io/@howkii-studio/markdown_intro

### 檢視版本號
- git version

### 註冊全域資訊 
- git config --global user.name daisy
- git config --global user.email rtw165@gmail.com

### 初始化倉庫
- git init
- .git/

### 控管狀態
- U -> Untrack (未追蹤) 
- A -> Added (已加入) 
- D -> Deleted (已刪除) 
- M -> Modified (已變更)

### 加上控管 
- git add 1.txt 
- git add .  (加入所有變動，包含加入控管，需小心使用) 

### 檢視裝態
- git status 

### 恢復刪除
- git restore 1.txt 

### 加入不控管的項目
- 新增.gitignore

### 檢視暫存區狀態
- git ls-files -s 


### 恢復上一動
- git checkout filename
- git checkout .


### 加入倉庫
- git commit -m "專案初始化完成"
- git commit --amend   (跟最新commit合併)


### 檢視倉庫
- git log
- git log --oneline

- 資訊過多，按enter，最後按q離開
- 資訊過多，按enter，可以按q離開


### 分支的概念
- master (主分支)
- git branch


### 切換commit 
- git checkout commit-sha五碼 
	- 觀察當時的程式碼
- git checkout master


### 新增分支
- git branch test

### 切換分支
- git checkout test


### 合併分支
- git checkout master
- git merge test

### 刪除分支
- git branch -D test


### 申請github
- github.com

### 綁訂到雲端倉庫
- git remote add origin https://github.com/rtw165-sys/git-demo

### 檢視雲端倉庫網址
- git remote -v

### 推送到雲端
- git push
- git push -u origin master (第一次)
- git push -f 
	- force 強制

### 複製專案
- git clone https://github.com/rtw165-sys/git-demo.git(包含.git)



### 從雲端拉取
- git pull

### VSCODE
- ctrl+shift+p 
- 更改終端機 
	- default terminal =>cmd.exe 


### 重置專案的使用權
- git remote set-url origin https://iiiplay@github.com/iiiplay/git-demo.git
