﻿Git is a distributed version control system.
Git is a distributed version control system.
Git is free software.
我是第三个版本了.


第一步是用git add把文件添加进去，实际上就是把文件修改添加到暂存区； git add xx 或者 git add .

第二步是用git commit提交更改，实际上就是把暂存区的所有内容提交到当前分支。 git commit -m 'xx'

因为我们创建Git版本库时，Git自动为我们创建了唯一一个master分支，所以，现在，git commit就是往master分支上提交更改。

你可以简单理解为，需要提交的文件修改通通放到暂存区，然后，一次性提交暂存区的所有修改。

