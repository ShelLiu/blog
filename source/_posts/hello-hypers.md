---
title: HyperS 前端团队博客创建了
date: 2017-07-20
tag: 
- HyperS
---

千呼万唤始出来，HyperS 的前端团队博客终于在今天搭建好了。欢迎各位小伙伴的踊跃投稿。
在投稿的时候，需要注意的是：
**所有文章不能涉及到公司安全信息，以及客户相关资料，通过直属 Leader 审核后才能发布。**

## 文章格式
### 按照 hexo 的格式进行发布
```javascript
---
title: you post title
date: 2017-07-20 15:04:29
tags:
- ES7
- Async函数
---

//正文部分

// 结尾
> 本文作者：[Superman](https://github.com/superman66)
> 原文地址：[原文地址]()
>...
```
文章应包括：
* 标题
* 时间
* 标签 - (须正确设置标签）
* 正文 - 文章的内容
* 结尾 - 用于添加作者信息

**结尾的格式**

* 本文作者 - 可以填写你的 GitHub 或者 个人站点信息
* 原文地址 - 填写文章的出处（可选）
* 其他按需添加

## 如何投稿
**第一步：Fork 博客的 repository 到你的 GitHub 账号**

>Blog Github 地址：[Blog](https://github.com/hypers/blog)

**第二步：clone repository 到你本地**
clone 到本地后，并切换到 `dev` 分支。
```bash
git clone git@github.com:hypers/blog.git
git checkout -b dev
```

**第三步：创建文章**
进入到 `blog/source/_posts` 文件夹，创建 markdown 文件，按照上面的格式写文章。
文章写完之后，直接提交到 GitHub。

**第四步**
提交 `pull reqeust` 即可。


> 本文作者：[Superman](https://github.com/superman66)
