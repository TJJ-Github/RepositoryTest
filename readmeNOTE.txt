

位置	cd D:/Files/Data/TAN/Git/testgit

工作区到暂存区的新增			git add XXX
暂存区到工作区的确定			git commit -m XXX

丢弃（工作区到暂存区）的修改即前1步	git checkout -- XXX
撤销（暂存区到工作区）的修改即后1步	git reset HEAD XXX

退回（工作区到工作区）的版本一共2步	git reset --hard HEAD^
撤销（工作区到工作区）的退回一共2步	git reset --hard YYYY(从日志查看)

回收文件（工作区到暂存区）1步		rm XXX
删除文件（工作区到工作区）2步		git rm XXX
撤销删除（工作区到暂存区）1步		git checkout -- XXX

查看内容	cat XXX
查看状态	git status
查看变化	git diff HEAD -- XXX
查看日志	git log --pretty=oneline	git log		






