# GIT

## 安装

https://git-scm.com/

![image-20210129170040734](D:\霸道小猫的文件夹\img\Git_001.jpg)

1.可以查看文档

2.下载

2.1安装时按照默认选择即可

2.2打开gitbash，输入 `git --version`，确定版本号正常出现

## 管理GIT项目 

### gti add

跟踪新文件，或者说将内容从工作目录添加到暂存区。

### git status

用于显示工作目录和暂存区的状态。使用此命令能看到那些修改被暂存到了, 哪些没有, 哪些文件没有被Git tracked到。`git status`不显示已经`commit`到项目历史中去的信息。看项目历史的信息要使用`git log`.

### git commit

主要是将暂存区里的改动给提交到本地的版本库

| -m   | git commit -m [message] | 在命令行中提供提交注释。                      |
| ---- | ----------------------- | --------------------------------------------- |
| -a   | $ git commit -a         | 修改文件后不需要执行 git add 命令，直接来提交 |

```git
$ git commit -am '修改 hello.php 文件'
[master 71ee2cb] 修改 hello.php 文件
 1 file changed, 1 insertion(+)
```