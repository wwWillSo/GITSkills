# GITSkills
$git init 
$git add {filename}
$git commit -m {comment}
$git status 
$git diff
$git log --gragh --pretty=oneline
$git reset --hard HEAD^
$git reset --hard {commit_id}
$git reflog
$git checkout -- {filename}
$git reset HEAD {filename}
$git rm {filename}
$ssh-keygen -t rsa -C "244864220@qq.com"
$git remote add origin git@github.com:wwWillSo/learngit.git
$git push -u origin {name}
$git push origin {name}
$git clone git@github.com:wwWillSo/GITSkills.git
$git checkout -b {name}
$git branch
$git checkout {name}
$git merged {name}
$git branch -d {name}
$git log --gragh
$git merge --no-ff -m "{comment}" {name}
$git stash
$git stash list
$git stash pop
$git branch -D {name}
$git remote 
$git remote -v
$git tag {tagname} {commit_id}
$git tag
$git show {tagname}
$git push origin {tagname}
查看远程库信息，使用git remote -v；
本地新建的分支如果不推送到远程，对其他人就是不可见的；
从本地推送分支，使用git push origin branch-name，如果推送失败，先用git pull抓取远程的新提交；
在本地创建和远程分支对应的分支，使用git checkout -b branch-name origin/branch-name，本地和远程分支的名称最好一致；
建立本地分支和远程分支的关联，使用git branch --set-upstream branch-name origin/branch-name；
从远程抓取分支，使用git pull，如果有冲突，要先处理冲突。

