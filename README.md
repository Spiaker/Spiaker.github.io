

![Github Forks](https://img.shields.io/github/forks/senli1073/senli1073.github.io?style=flat)
![Github Stars](https://img.shields.io/github/stars/senli1073/senli1073.github.io?style=flat)
![License](https://img.shields.io/github/license/senli1073/senli1073.github.io)
![Last Commit](https://img.shields.io/github/last-commit/senli1073/senli1073.github.io)

# 用于个人学术网站的简单 Github Pages 网站。.

## 预览
[![screenshot_full](D:\Github\Personal website\Spiaker.github.io\screenshot_full.png)](https://spiaker.github.io/)


## 介绍

这个个人学术网站基于 [bootstrap](https://github.com/StartBootstrap/startbootstrap-new-age)。

旨在将 Markdown 文件集成为内容输入。部署前无需编译网页。加载时，Markdown 文件会自动解析并嵌入到页面中。

此模板支持 LaTeX 公式输入。您可以将 and 用作 inline-math 的分隔符，或者将 and 用作 display-math 的分隔符。还支持 、 和 等宏。有关更多详细信息，请参阅 [MathJax](https://docs.mathjax.org/en/latest/index.html)。`$...$``\(...\)``$$...$$``\[...\]``\ref{...}``\eqref{...}``\begin{equation}...\end{equation}`

:milky_way: 演示: https://senli1073.github.io/

## 开始使用

### 1. Fork 此存储库
存储库名称应为 ，它也将是您网站的 URL。`<username>.github.io`


### 2. 编辑页面内容

（1） 转到要存储项目的文件夹，并克隆新的仓库：
```
git clone https://github.com/<username>/<username>.github.io.git
```
目录结构如下：

```.
.
├── contents
└── static
    ├── assets
    │   └── img
    ├── css
    └── js
```

（2） 修改各部分的内容，对应 。`contents/*.md`

（3） 调整网站的标题、版权信息和其他文本`contents/config.yml`

（4） 将网页的背景图像和照片替换为新的`static/assets/img/`

（5） 推送它：

```
git commit -am 'init'
git push
```


### 3. 使用

启动浏览器并转到 `https://<username>.github.io`



## 许可证

版权所有 Spiaker，2025 年。
