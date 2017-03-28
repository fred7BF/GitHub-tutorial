新建方法：
   clone      从别的仓库克隆一个目录
   init       初始化一个新的git目录（如果初始化成功，目录下就会生成.git目录，这个目录中存储着仓库数据)

更改工作区文件后: 
   add        将文件添加进暂存区（如果不执行此命令，更改的文件会显示在Untracked files里)
   mv         移动或重命名一个文件、目录、文件夹
   reset      Reset current HEAD to the specified state
   rm         删除暂存区的文件

检查状态：
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        查看提交日志，可以加上文件或目录名，就会只显示该目录的相关日志
   show       Show various types of objects
   status     查看仓库状态（十分常用的命令）

版本：
   branch     查看，创建，删除分支
   checkout   切换分支或存储工作树
   commit     将暂存区中的文件保存到仓库的历史记录中
   diff       查看工作树、暂存区、最新提交之间的差别
   merge      合并两个以上的分支
   rebase     Reapply commits on top of another base tip
   tag        查看、创建、编辑标签

合作 (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       更新远程主机

