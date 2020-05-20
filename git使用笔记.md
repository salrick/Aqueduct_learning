# 1.下载代码后更改上传
>1.git clone https://自己的仓库url地址
2.修改自己的代码
3.git add .
4.git commit -m "本次提交项目的备注名"
>>这一步之后可能要填写git的账号密码，在VScode里面操作的话跟着提示走就好了
>
>5.git checkout -b 要提交的分支名(否则默认提交到master分支)
>6.git push --set-upstream origin db
>>这步完成以后如果不报错就可以到git的网页上面查看文件了。
# 2.新建项目并上传本地代码
>1.新建文件夹并添加代码（可以是从微信上传输然后解压过来的）
2.在命令行（cmd、git bash、powershell）中进入到根目录（我们目前的dart项目为pubspec所在目录）
>>cd(空格)+该路径 
>
>3.git init
4.git add .
5.git commit -m "本次提交项目的备注名"
>>这一步之后可能要填写git的账号密码，在VScode里面操作的话跟着提示走就好了
>
>6.git checkout -b 要提交的分支名(否则默认提交到master分支)
>7.git push --set-upstream origin db
>>这步完成以后如果不报错就可以到git的网页上面查看文件了。
# 附（当我发现新的要注意的地方的时候可能会更新）
>1.使用git add . （add后面有个空格）后可以使用git status查看更改情况。