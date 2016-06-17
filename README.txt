Git is a version control system.
Git is free software.

git config --global user.name="ajshu"
git config --global user.email="shu.aojun@qq.com"

git init
git add
git commit -m "i commit a file"

git status
git diff

git log//查看提交历史
git log --pretty=oneline
git reset --hard HEAD^//HEAD指向的版本就是当前版本,回退
git reset --hard HEAD^^
git reset --hard HEAD~100
git reflog //查看命令历史，以便确定要回到未来的哪个版本

工作区和暂存区
