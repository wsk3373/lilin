'this is first doman' 

git branch -v  查看
git branch   创建分支 
git 加-d  就是删除
git push all          所有
git push origin master   推送到远程创库
git push --force origin master  强覆盖推送  同等  -f        
                      如果其他人为这个分支提交了贡献，并将他们的更改推送到了远程服务器上，而你强制将其推到了远端，那么你将覆盖他们的更改.为避免这种情况，可以使用--force-with-lease 选项
git push origin --delete master    删除远程master

git pull --rebase test dev   要是推送拒绝。
git fetch
--------------------------------
git chechout -b branchname   加-b 表示创建分支brandhname 并切换到创建的分支.相当于两条命令:
git branch branchname 
git chechout branchname
-------------------------------
