# [vuepress-devkit](https://github.com/itmacy/vuepress-devkit)

## 项目说明
该项目是基于项目[vuepress-demo](https://github.com/itmacy/vuepress-demo)开发的一款vuepress开发工具，可作为使用vuepress搭建博客的初始模板。

## 项目运行
- 1.安装node环境
- 2.运行：`npm run dev`。
- 3.访问： `http://localhost:8080/`。

> 注意：package.json文件中的部署脚本指令：`"deploy": "start deploy.sh"`是针对Windows操作系统下运行的，如果是mac系统，则把`start`替换为`bash`。

## 项目部署
- 1.在github上创建两个repository，第一个名为`USERNAME.github.io`（USERNAME替换成自己的github账号），第二个名字随意，例如VuePressBlog，并把VuePressBlog
克隆下来，把vuepress-devkit项目里面的全部文件拷贝到VuePressBlog项目里面。
- 2.在deploy.sh文件进行相关配置。
- 3.运行：`npm run deploy`。
- 4.访问：`https://USERNAME.github.io/`（USERNAME替换成自己的github账号），例如访问我的：[https://itmacy.github.io/](https://itmacy.github.io/)。

## 更多
关于vuepress的更多配置和使用请移步[官网](https://www.vuepress.cn/guide/)。


  