# 软件工程笔记5

# 软件配置管理

软件配置管理是一种标识、组织和控制修改的技术，它作用于整个软件生命周期，其目的是使错误达到最小并最有效地提高生产率。

# 软件配置项
软件配置项（Software Configuration Item，简称SCI）是为了配置管理而作为单独实体处理的一个工作产品或软件。



# 版本
版本是在明确定义的时间点上某个配置项的状态；版本管理是对系统不同的版本进行标识和跟踪的过程，从而保证软件技术状态的一致性。



# 基线
基线（Baseline）是软件配置项的一个稳定版本，它是进一步开发的基础， 只有通过正式的变更控制过程才能改变。



# 版本控制问题
我们小组学习使用git来进行版本管理。


# 软件配置管理工具git
Git 是一个开源的分布式版本控制系统，用于敏捷高效地处理任何或小或大的项目。

Git 是 Linus Torvalds 为了帮助管理 Linux 内核开发而开发的一个开放源码的版本控制软件。

Git 与常用的版本控制工具 CVS, Subversion 等不同，它采用了分布式版本库的方式，不必服务器端软件支持。

# Git 工作流程


一般工作流程如下：

1. 克隆 Git 资源作为工作目录。
2. 在克隆的资源上添加或修改文件。
3. 如果其他人修改了，你可以更新资源。
4. 在提交前查看修改。
5. 提交修改。
6. 在修改完成后，如果发现错误，可以撤回提交并再次修改并提交。
<!-- 下图展示了 Git 的工作流程： -->

# Git 基本操作
Git 的工作就是创建和保存你项目的快照及与之后的快照进行对比。


Git 常用的是以下 6 个命令：git clone、git push、git add 、git commit、git checkout、git pull

![](https://www.runoob.com/wp-content/uploads/2015/02/git-command.jpg)

## git init 命令
git init 命令用于在目录中创建新的 Git 仓库。

在目录中执行 git init 就可以创建一个 Git 仓库了。

```
$ mkdir runoob

$ cd runoob/

$ git init

```

## git clone
git clone 拷贝一个 Git 仓库到本地，让自己能够查看该项目，或者进行修改。

拷贝项目命令格式如下：

 `git clone [url]`

## git add
git add 命令可将该文件添加到暂存区。

添加一个或多个文件到暂存区：

`git add [file1] [file2]`
添加指定目录到暂存区，包括子目录：

`git add [dir]`
添加当前目录下的所有文件到暂存区：

`git add .`

## git commit
git commit 命令将暂存区内容添加到本地仓库中。

提交暂存区到本地仓库中:

`git commit -m [message]`
[message] 可以是一些备注信息。

提交暂存区的指定文件到仓库区：

```
$ git commit [file1] [file2] ... -m [message]
-a 参数设置修改文件后不需要执行 git add 命令，直接来提交

$ git commit -a

```

设置提交代码时的用户信息
开始前我们需要先设置提交的用户信息，包括用户名和邮箱：
```
$ git config --global user.name 'runoob'
$ git config --global user.email test@runoob.com
```

如果去掉 --global 参数只对当前仓库有效。

提交修改
接下来我们就可以对 hello.php 的所有改动从暂存区内容添加到本地仓库中。

以下实例，我们使用 -m 选项以在命令行中提供提交注释。
```
$ git add hello.php
$ git status -s
A  README
A  hello.php
$ git commit -m '第一次版本提交'
[master (root-commit) d32cf1f] 第一次版本提交
 2 files changed, 4 insertions(+)
 create mode 100644 README
 create mode 100644 hello.php
 ```

## git reset

git reset 命令用于回退版本，可以指定退回某一次提交的版本。

git reset 命令语法格式如下：

`git reset [--soft | --mixed | --hard] [HEAD]`

## git push
git push 命令用于从将本地的分支版本上传到远程并合并。

命令格式如下：
```
git push <远程主机名> <本地分支名>:<远程分支名>如果本地分支名与远程分支名相同，则可以省略冒号：
git push <远程主机名> <本地分支名>
```


