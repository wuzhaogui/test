## 1 git 配置
```
查看git版本
git --version

查看配置信息
vim ~/.gitconfig
git config --list

配置用户名和邮件
git config --global user.name "username"
git config --global user.email "123456@qq.com"
```
## 2 git 创建仓库
```
使用当前目录作为git仓库
git init
使用指定目录作为git仓库
git init repo

提交文件到仓库
git add file
git commit -m 'comment'

从现有 Git 仓库中拷贝项目
git clone 'Git 仓库' '目录'
git clone git@github.com:fsliurujie/test.git     
```

## 3 git 命令
```
echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin git@github.com:wuzhaogui/test.git
git push -u origin master

git pull --rebase origin master
                
```
