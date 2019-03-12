### git 切换分支的时候 是否需要提交当前已经修改的

有如下几种处理方式：

1. add并且commit，再checkout，提交到当前分支
2. add但不commit，可以stash，然后checkout回来之后stash apply，在commit，提交到当前分支
3. add但不commit，也不stash，直接checkout，然后再commit的话，记录就在切换分支下面。