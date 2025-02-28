1. 仓库操作  
git init：初始化仓库  
git clone <URL>：克隆远程仓库  
  
2. 提交更改  
git add <文件>：添加文件到暂存区  
git add .：添加所有修改  
git commit -m "消息"：提交暂存区内容  
git commit -am "消息"：添加所有已跟踪文件并提交  
  
3. 分支管理  
git branch：查看分支  
git branch <分支名>：创建分支  
git checkout <分支名>：切换分支  
git switch -c <新分支>：创建并切换分支  
git merge <分支名>：合并分支到当前分支  
git branch -d <分支名>：删除分支  
  
4. 远程操作  
git remote -v：查看远程仓库地址  
git pull：拉取远程代码并合并  
git push：推送到远程仓库  
git push -u origin <分支名>：首次推送并关联分支  
  
5. 撤销与恢复  
git restore <文件>：丢弃工作区修改  
git restore --staged <文件>：取消暂存  
git reset --hard HEAD^：回退到上一提交（慎用）  
git revert <提交ID>：安全撤销某次提交  
  
6. 查看信息  
git status：查看状态  
git log：查看提交历史  
git log --oneline：简洁历史  
git diff：查看工作区改动  
git diff --staged：查看暂存区改动  
  
7. 其他实用  
git stash：暂存当前修改  
git stash pop：恢复暂存内容  
git tag <标签名>：打标签