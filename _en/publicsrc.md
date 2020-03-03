---
layout: page
title: 上传到公用源服务器
---

如果您的文件超出第三方托管服务尺寸限制（不幸的是，好像大部分线路都是这样……），我们提供能够处理大文件的公用源服务器。

### 选择源服务器

目前可用的公用源服务器有：

* [天津公用源服务器](https://api.zbx1425.tk:8953/bcs-src) - 由 [zbx1425](https://zbx1425.tk) 搭建

### 注册账号并登录

按"注册"按钮，填入相应信息。源服务器通常会要求您提供Email。

接下来登入您的账号。

### 上传文件

将您那个以Email为名称的文件夹的内容上传到源服务器。`author.ini`应该在根目录下。

可同时上传最多8个文件，但无法一次性上传整个文件夹，创建文件夹请使用[新建]->[文件夹]。

### 刷新数据

公用源有着自动刷新功能，每5分钟一次，您可耐心等待。

如果您性子比较急，您可以先到 [此页面点击按钮](https://api.zbx1425.tk:8953/bcs-src/metadata.php)， 再打开 [此页面(无任何内容)](https://api.zbx1425.tk:8953/bcs-index/responsemerger.php)，以手动刷新。

回到软件主页，按"刷新"按钮。如果您的配置文件书写无误，您的路线应当出现在列表中。

### 另见

网站的评论功能有些细节需要向您说明。见[此处](rssnotif.html)

注：您可能会发现您的文件夹中出现类似 `***.thumb.jpg` 的文件。这些文件由系统自动维护，请将这些文件留在原处，不需编辑、删除和移动。如您要移除线路，将其与其它路线相关文件一同移除即可。