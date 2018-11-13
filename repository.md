You have an empty repository
To get started you will need to run these commands in your terminal.

New to Git? Learn the basic Git commands
Configure Git for the first time
```
git config --global user.name "梁**"
git config --global user.email "ri**@163.com"
```
Working with your repository
I just want to clone this repository
If you want to simply clone this empty repository then run this command in your terminal.
```
git clone https://github.com/liangriyu/flink-quickstart.git
```
My code is ready to be pushed
如果你代码已经准备好推送到仓库，请在终端中执行该命令
```
cd existing-project
git init
git add --all
git commit -m "Initial Commit"
git remote add origin https://github.com/liangriyu/flink-quickstart.git
git push -u origin master
```
My code is already tracked by Git
If your code is already tracked by Git then set this repository as your "origin" to push to.
```
cd existing-project
git remote set-url origin https://github.com/liangriyu/flink-quickstart.git
git push -u origin master
```
