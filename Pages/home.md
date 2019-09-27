# Allenem 的博客主页

## 一、介绍

这是我 Allenem 的个人博客首页，之前有试过 Hexo，有试过 Vue+Nodejs，但最终还是选择了原始的手写 HTML+CSS，理由很简单，GitPage 只支持静态页面展示和跳转。

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

页面分三部分：左边菜单栏（手机是右上角下拉菜单），页底部分，主体部分（采用iframe标签套用HTML文件）。

当然如果你想套用我的模板也行，直接拿去用就好。（LICENSE：[MIT](./LICENSE)）

使用步骤如下，方便以后指导自己添加心得笔记：

---

- 1.在 `./Notebooks` 文件夹下新建 `xxx.md` 文件；
- 2.拷贝文章内容，粘贴到 [该网址](https://allenem.github.io/md2HtmlOrPdf/index.html) 的 `input Markdown content` 区域，点击 <button> 下载html </button> ；
- 3.将下载的 `index.html` 文件改名 `xxx.html` 移动到 `./Notebooks` 目录下;
- 4.将 `./Notebooks/xxx.html` 的 **第6行** 代码段①改为代码段②（修改标题）:

    代码段①
    ```html
            <title>GitHub Markdown CSS demo</title>
    ```
    代码段①
    ```html
            <title>xxx</title>
    ```
- 5.将 `./Notebooks/xxx.html` 的 **第9行** 代码段③选择性改为代码段④（为了加载css文件快一点或者解决不能加载css样式问题）:

    代码段③
    ```html
    <link rel="stylesheet" href="https://blog-static.cnblogs.com/files/allenem/mycss.css">
    ```
    代码段④
    ```html
    <link rel="stylesheet" href="../CSS/mycss.css">
    ```
- 6.在 `./Pages/notebooks.html` 的 **第28行** 代码段⑤下面添加代码段⑥（目录页面添加条目）:

    代码段⑤
    ```html
    <ul>
    ```
    代码段⑥
    ```html
    <li><a target="_blank" href="../Notebooks/xxx.html">xxx</a></li>
    ```
- 7.大功告成。

---

## 四、最后来两张我老婆照片镇楼

![焰灵姬5](./img/焰灵姬5.jpg)

![焰灵姬3](./img/焰灵姬3.jpg)