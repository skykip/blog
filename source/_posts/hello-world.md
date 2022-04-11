---
title: 使用 Hexo+GitHub 搭建个人博客
tags:
- hexo
- 搭建
categories:
- 工具
---
本文主要使用Hexo与Github进行个人blog的搭建
Hexo官网：[Hexo](https://hexo.io/zh-cn/)
Github官网：[Github](https://github.com/)

### 环境介绍
博主的本地环境为：MacBook Air M1，Macos 11.2.2，Homebrew 3.4.5

---


# 开始搭建
## 1.安装 node与npm
``` bash
$ brew install node
$ brew install npm

$ node
$ Welcome to Node.js v17.8.0.

$ npm -version
$ 8.6.0
```
---
## 2.Hexo安装
``` bash
# 使用npm安装Hexo
$ npm install hexo-cli -g

# 初始化Hexo blog
$ hexo init blog
```
本地blog初始化成功，本地路径为`/Users/username/blog`

---
## 3.Hexo主题选择
Hexo可在官网自由选择
官网主题：[HexoTheme](https://hexo.io/themes/)
***进入主题页面，点击图片可对主题进行预览，点击蓝色主题名称可进入相应的主题Github主页***

### （1）主题下载
```bash
#从终端进入blog项目中
$ cd blog
#使用git克隆相应主题到blog中
#格式：git clone [url] themes/xxx
#本博客采用Wikitten主题进行构建
$ git clone https://github.com/zthxxx/hexo-theme-Wikitten themes/Wikitten
```
### （2）主题配置





通过git clone [url] themes/xxx 将主题克隆到本地，
修改 _config.yml 中的theme：xxx

``` bash
# 使用npm安装Hexo
$ npm install hexo-cli -g

# 初始化Hexo blog
$ hexo init blog
```
本地blog初始化成功，本地路径为`/Users/username/blog`

---









Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)
