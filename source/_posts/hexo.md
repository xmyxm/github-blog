---
title: hexo使用教程
date: 2019-10-30 09:59:07
tags: [hexo, 教程]
image: https://img.meituan.net/msmerchant/46f2b1b3049c72495540ee4a6ac91ac7441906.jpg #摘要图片吧
---

### 一.创建hexo
```bash
    hexo new pagename 创建一个post模板的页面
```

### 二.创建页面
```bash
    hexo new pagename 创建一个post模板的页面
```

### 三.常见问题
```bash
    hexo new pagename 创建一个post模板的页面
```

#### 1. wordcount is not defined 报错！
{% asset_img wordcount.png This is an example image %}
这是因为你使用的theme里面开启了字数统计功能，且项目未安装wordcount插件，解决方案如下：
```
    1. 安装 wordcount 依赖即可
```

```bash
    npm install hexo-wordcount
```
### 在你的hexo目录下执行这样一句话npm install hexo-asset-image –save，这是下载安装一个可以上传本地图片的插件
