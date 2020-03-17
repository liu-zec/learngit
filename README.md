# 学习Git使用
## git add  ------- 添加到缓存区
## git commit   ------  提交到当前分支
## git status  ------- 查看状态
## git log    --------   查看版本记录  `"按q退出"`
## git reflog  -------- 查看操作记录 （里面有git commit --- 提交的id） "按q退出"
## git reset --hard commit_id  -----------  退回到某个版本
## git checkout -b develop   --------  创建develop分支并切换到develop分支  相当于下面两个命令
  ### git branch develop    -------  创建分支
  ### git checkout develop    --------  切换分支
## git branch  ------ 查看所有分支
## master 上分支修改有冲突
## git merge develop -----  合并 指定分支 develop 到当前分支上，develop 上最新修改被合并到master 分支上面了

## git switch -c develop  ------ 同 git checkout -b develop 作用一样  新的 git switch 更容易理解
## git switch master  ----- 切换分支
## git branch -d develop   ------ 删除分支
## git branch -D develop   ------ 删除分支   这个分支没有被合并过  强行删除

## git log --graph  可查看分支合并图


## git remote 查看远程分支
