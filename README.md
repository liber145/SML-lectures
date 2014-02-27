git如何删除本地所有未提交的更改，包括修改的，新增的，删除的，还有一些编译生成的临时文件。
就是回到上一版本的干净状态。有如下两个命令：
1.git clean -df
2.git reset --hard
第一个命令删除所有untracked的文件如果文件已经被tracked, 修改过的文件不会被回退。
第二个命令只把tracked的文件revert到前一个版本，对于untracked的文件(比如编译的临时文件)都不会被删除。
