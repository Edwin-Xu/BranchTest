# BranchTest
> 终于搞懂了分支等中级的git知识！
## 复习
1. origin：对于本地而言的，是本地指向远程仓库的默认名称，origin就代表远程仓库的URL，可以自行定义，git clone newName url?
2. master: 默认分支。 origin master：已经表明是哪个远程仓库的那个分支，如果只使用git push，往往后报错，upstream的问题，使用git push -u origin master指定仓库和分支即可。
3. 创建分支：git branch newBranchName
4. 切换分支：git checkout branchName
5. 合并分支：git merge branchName 将branchName最近的commit合并到当前分支，注意是branchName的最近的commit
6. HEAD：和分支无关，指向仓库最近的一次commit——最近的一个版本。
