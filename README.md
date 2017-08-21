# Git
Git使用筆記

• 初始化:git init

• 查看檔案狀態: git status

• 將檔案加入快照名單: git add <filename>
   也可以用 git add . 或 git add --all 一次新增所有的檔案到快照名單

• 快照: git commmit -m "XXXX"
  XXXX的部分就是你要給檔案的註解，建議寫清楚明白點會比較好喔~
  

• 連線到GitHub的專案: git remote add origin https://github.com/User/Example.git
    P.S. https://github.com/User/Example.git 每個人的專案連結都會不一樣喔 User的地方應該是你的Git暱稱，Example.git的Example應該是你的專案名稱
    如果你的專案叫HelloWorld、暱稱叫Hello的話，後面就會長這樣:https://github.com/Hello/HelloWorld.git
  
• 上傳檔案: git push -u origin master

• 下載檔案: git pull --rebase origin master

• 錯誤教學:

如過上傳的時候顯示出: error: failed to push some refs to git 'https://github.com/XXX/XXXX.git'
  代表你電腦裡面的專案資料夾中沒有包含『README.md』這個檔案 所以請從你的GitHub上下載一個README.md檔案丟到你的專案資料夾裡面就OK囉~
  
  
