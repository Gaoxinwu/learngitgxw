Git is a distributed version control system;
Git is free software distributed under the GPL;
Git has a mutable index called stage.
Git tracks changes of files.
分布式版本系统的最大好处之一是在本地工作完全不需要考虑远程库的存在，也就是有没有联网都可以正常工作，而SVN在没有联网的时候是拒绝干活的！当有网络的时候，再把本地提交推送一下就完成了同步，真是太方便了！
Creating a new branch is quick.
git add把文件添加进去，实际上就是把文件修改添加到暂存区；
git commit提交更改，实际上就是把暂存区的所有内容提交到当前分支。
我们创建Git版本库时，Git自动为我们创建了唯一一个master分支，所以，现在，git commit就是往master分支上提交更改。
Git跟踪并管理的是修改，而非文件。
要克隆一个仓库，首先必须知道仓库的地址，然后使用git clone命令克隆。

Git支持多种协议，包括https，但通过ssh支持的原生git协议速度最快。
git commit -m ""
git push