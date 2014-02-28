git 删除本地所有未提交的更改       
1.git clean -df     #删除所有untracked的文件,如果文件已经被tracked, 修改过的文件不会被回退。    
2.git reset --hard  #只把tracked的文件revert到前一个版本，对于untracked的文件(比如编译的临时文件)都不会被删除。   
