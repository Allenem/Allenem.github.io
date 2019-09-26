# Allenem 的博客主页

## 一、介绍

这是我 Allenem 的个人博客首页，之前有试过 Hexo，有试过 Vue+Nodejs，但最终还是选择了原始的手写 HTML+CSS，理由很简单，GitPage 只支持静态页面展示和提跳转。

## 二、组成

我的博客主要有以下几个方面组成：

- 主页
- 博文
- 项目
- 关于

### 1.主页

简单介绍一下我这个项目。

### 2.博文

博文就是我学习的一些笔记。

暂时设定包含 HTML， CSS， JavaScript， Vue， React， Nodejs， Git相关， Java， Python， CV， NL， 学校课程学习记录，一些小技巧 等等吧。

### 3.项目

贴出一些我的项目仓库地址和简介。

### 4.关于

我的个人简介。

## 三、该博客项目简介

本博客是静态网页，没有前后端交互功能，仅仅作笔记展示使用。

使用步骤如下，方便以后指导自己如何新添心得笔记：

- 1.在 `./Notebooks` 文件夹下新建 `markdown` 文件；
- 2.拷贝文章内容，粘贴到[该网址](https://allenem.github.io/md2HtmlOrPdf/index.html) 的 `input Markdown content` 区域，点击 <button>下载html</button> ；
- 3.将下载的 `index.html` 文件改名 `xxx.html` 移动到 `./Notebooks` 目录下;
- 4.在 `./Notebooks/index.html` 的代码段①下面添加代码段②:

    代码段①
    ```html
    <li><a href="./index.html">目录</a></li>
    ```
    代码段①
    ```html
    <li><a href="./xxx.html">xxx</a></li>
    ```
- 5.大功告成。

&hearts; 注意：`<a href="./xxx.html">xxx</a>` 中 `./xxx.html` 如果是外部链接需加入 `target="_blank"` ,例如： `<a target="_blank" href="./xxx.html">xxx</a>` 

## 四、最后来两张好看的照片镇楼吧

![焰灵姬5](./img/焰灵姬5.jpg)

![焰灵姬3](./img/焰灵姬3.jpg)
