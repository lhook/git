# git
Using git for the first time.
ls 指令   —————— 查看文件
pwd 指令  —————— 查看路径
mkdir +name   ——————创建文件夹

文件内初始化git (创建git仓库)
    git config --global user.email "you@example.com"
    git config --global user.name  "Your Name"
    cd test(文件夹名)       进入文件夹
    git init     （ 创建了隐藏文件）

   向仓库中添加文件
   工作区——暂存区——git仓库

 touch+文件名后缀    创建文件
   git status                  查看状态
   git+add+文件名               添加到暂存区
   git commit -m ' 文件名后缀'      将文件从暂存区提交到仓库

 vi +文件名        修改文件
     按i 进入修改   退出点Esc 按 " ：wq " 保存
     git add 文件名后缀   修改后的文件加入暂存区
      git commit -m '第X次修改 并提交到仓库'     文件修改后提交到仓库

 删除仓库文件
     1.rm -rf 文件名后缀    删除文件 
							   
     2.git rm 文件名后缀    git中删除文件
     3.git commit -m '第X次通过git删除仓库文件'   


     git push 将本地仓库提交到远程仓库

     git clone 仓库地址




