---
title: "How to Create a Website with Github"
---

## 搭建本地开发环境
* 下载Ruby，对于Window来说直接下载Ruby+Devkit(x64)
下载地址：https://rubyinstaller.org/downloads/
![Rubyinstaller](/assets/images/rubyinstaller.png)
下载完成后直接安装，再打开cmd输入 ruby -v 命令检验安装是否成功。
![Ruby -v](/assets/images/ruby_v.png)
* 下载RubyGems
下载地址：https://rubygems.org/pages/download
![RubyGems](/assets/images/rubygems.png)
下载zip文件并解压，再打开cmd到解压后的路径，执行 ruby setup.rb 命令，进行安装。
等待完成后，输入 gem -v 命令，检验是否成功。
* 安装Jekyll
cmd中输入 gem install jekyll 命令，进行安装。
等待完成后，输入 jekyll -v 命令，检验是否安装成功。

## 搭建本地博客
* 在Jekyll官网查找自己喜欢的主题 http://jekyllthemes.org/
* 在自己喜欢的主题页面直接download或者fork到自己的账号
![Minimal Mistake Theme](/assets/images/minimal_mistake.png)
* 启动本地服务器
在cmd中选择博客模板的路径，执行 jekyll serve 命令，启动本地服务器。
* 通过浏览器浏览本地博客 http://127.0.0.1:4000

## GitHub Pages
* 进入自己的博客项目，点击Setting。
![Github_Setting](/assets/images/github_setting.png)
* 点击Pages，并设定好Branch
![Github_Pages](/assets/images/github_pages.png)
![Github_Branch](/assets/images/github_branch.png)
* 将项目名称修改为userName.github.io
![Github_Name](/assets/images/github_name.png)

## GitHub Desktop
* 官网下载GitHub Desktop: https://desktop.github.com/
* 登录账号并与浏览器GitHub账户绑定
* 


