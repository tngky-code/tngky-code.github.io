---
title: "github pages with hugo"
date: 2021-05-22T02:37:29+08:00
summary: "Hugo 基本使用配置，发布到github pages"
---

``` c#
public int MyProperty { get; set; }
``` 
## Summary

Hugo 基本使用配置，发布到github pages

### Hugo Foundation

Hugo 基本使用配置

#### Quick Start

office doc:<https://gohugo.io/getting-started/quick-start/>

url:<https://github.com/gohugoio/hugo/releases>

#### Command Collection

创建文章： hugo new posts/my-first-post.md

    目标路径：content/posts

创建网站： hugo new site mysite

本地预览页面： hugo new site mysite

将项目发布到docs目录： hugo -d docs

#### Configuration

##### Content Article

ps:文章配置为\-\-\- \-\-\-中

draft:文章是否为草稿 ，true 不显示

##### layouts

从theme中拷贝.html,在其中修改会覆盖主题layouts

##### 项目 config.toml

配置网站主题： theme = "xhugo" 

配置网站基本URL： baseURL = "https://tngky-code.github.io" 

### Hugo Foundation

1.创建github pages Repository(与通常的Repository相同)

2.将Hugo生成静态网站文件 或 以hugo -d docs命令生成过的项目 传入创建的Repository

3.设置github pages:

    配置 url:

        https://github.com/<用户名>/<Repository名>/settings/pages

        Repository->settings->Pages/github pages
        
    设置source选项指定分支(如果Repository不是静态文件,需要设置路径/docs)
    
