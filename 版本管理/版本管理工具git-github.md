
# GIT

## git 简介
Git是一款免费、开源的分布式版本控制系统，用于敏捷高效地处理任何或小或大的项目。
Git 是 Linus Torvalds 为了帮助管理 Linux 内核开发而开发的一个开放源码的版本
控制软件。

## 安装 git

- 下载地址 [git](https://git-scm.com/downloads)
- 64-bit Git for Windows Setup. 安装版
- 64-bit Git for Windows Portable. 绿色版
- **建议使用绿色版，直接运行解压到纯英文路径中即可使用。**

### 配置环境变量
- GIT_HOME C:\PortableGit
- path %GIT_HOME%;%GIT_HOME%\bin

### git-bash 使用说明 
git-bash 可以在 windows中执行 linux 命令的工具。 
执行 git-bash 命令进入到 shell 环境。
-  注意：切换路径时使用linux系统风格。 
``` shell
$ cd  /D/B03/bootstrap/day4/code
```

## GIT 使用
1. $ git init 初始化版本库

    在项目根目录中，执行 $ git init 命令初始化本地版本库。

2. $ git status 查看本地库状态

    git status -s  输出简要的变更日志

3. 在根目录中创建 .gitignore 文件。

   .gitignore 文件中将定义哪些文件不添加到本址库中。 

4. $ git add --all 将除.gitignore定义之外的所有文件添加到追踪列表

    $ git add . //功能同上
    
    $git add 文件名  //添加指定名称的文件到追踪列表。

5. $ git commit -m '提交日志'

6. $ git log  查看提交日志

7. $ git diff 对比当前状态和版本库中状态的变化

8. $ git reset --hard  回到之前的版本库。



# GitHub
社交化编程
[github](https://github.com/)

``` shell
// 将本地库同步到 github中。
echo "# Notes" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/lichao668/Notes.git
git push -u origin master
```












