---
title: hexo使用教程
date: 2019-10-29 19:09:11
tags: hexo,教程
---
### 一.创建hexo
```bash
    hexo new pagename 创建一个post模板的页面
```

### 二.创建页面
```bash
    hexo new pagename 创建一个post模板的页面
```

### 三.常见问题
```bash
    hexo new pagename 创建一个post模板的页面
```

#### 1. wordcount is not defined 报错！
    图示:
    ![]('./hexo/wordcount.png')
    这是因为你使用的theme里面开启了字数统计功能，且项目未安装wordcount插件，解决方案如下：
```
    1. 安装 wordcount 依赖即可
```

```bash
    npm install hexo-wordcount
```

