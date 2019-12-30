# 提交第一个本地代码到github

## 1.配置git用户信息

  `git config --global user.name 'duheng'`


  `git config --global user.email '12@qq.com'`

  `git config -l //查看配置`

## 2.克隆远程仓库到本地

  `git clone url //url:远程仓库地址`

## 3.初始化本地仓库

  `git init`

## 4.创建需要提交的测试文件
  
  `touch READMED.md`

## 5.建立与远程仓库的链接

  `git remote add origin https://github.com/DuXiaoHeng/webpack-learn.git` 

## 6.挂起要提交的文件到缓存区

  `git add READMED.md`

## 7.提交代码，并设置本次提交的描述

  `git commit -m '本次提交的描述'`

## 8.推送提交的代码到远程仓库
  
  `git push -u origin master`
