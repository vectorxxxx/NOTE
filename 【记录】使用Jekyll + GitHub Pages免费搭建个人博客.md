# 使用Jekyll + GitHub Pages免费搭建个人博客

![](https://img.shields.io/badge/Ruby-v2.7.3--1-red) ![](https://img.shields.io/badge/RubyGems-v3.2.18-red) ![](https://img.shields.io/badge/Git-v2.31.1-red) ![](https://img.shields.io/badge/Node.js-v14.17.0-yellowgreen) ![](https://img.shields.io/badge/Python-v3.9-yellowgreen)

:sparkles: **My Blog**：[无名の辈 | VectorX (vectorxxxx.github.io)](https://vectorxxxx.github.io/)

![image-20210603000219393](https://gitee.com/vectorx/ImageCloud/raw/master/html5/20210603000220.png)



## Download

- :white_check_mark: Ruby：[Downloads (rubyinstaller.org)](https://rubyinstaller.org/downloads/) 【参考：[Ruby安装演示_小蓝枣的博客-CSDN博客_ruby安装](https://blog.csdn.net/qq_38161040/article/details/84205367)】
- :white_check_mark: RubyGems：[Download RubyGems | RubyGems.org | Ruby 社区 Gem 托管](https://rubygems.org/pages/download)
- :white_check_mark: Git：[Git - Downloads (git-scm.com)](https://git-scm.com/downloads)
- :white_large_square: Node.js：[Download | Node.js (nodejs.org)](https://nodejs.org/en/download/)
- :white_large_square: Python：[Download Python | Python.org](https://www.python.org/downloads/)

:sparkles: 因为我本地已经有`Node.js`和`Python`环境了，所以无法验证是否确实需要。不过参考了很多教程，大多数是没有说明需要安装两种环境的。如果你在安装过程中遇到问题，可以再选择安装。



## Install

```shell
# 1. 安装RubyGems：解压缩RubyGems并cd至其目录下
cd rubygems
ruby setup.rb
# 2. 替换gem源（可选）
gem sources --add https://gems.ruby-china.org/ --remove https://rubygems.org/
gem sources -l
# 3. 安装jekyll 
gem install jekyll
# 4. 安装bundler
gem install bundler
```

:sparkles: 至此，我们的基本环境已经搭建完毕



## Clone

:sparkles: `Github`上`Fork`项目：[wu-kan/wu-kan.github.io: my homepage & template for jekyll-theme-WuK](https://github.com/wu-kan/wu-kan.github.io)

:sparkles: 修改`Settings`设置：格式`your_username.github.io`

![image-20210602220529246](https://gitee.com/vectorx/ImageCloud/raw/master/html5/20210602220532.png)

```shell
# 1. 克隆Github项目，svn和git方式二选一
git clone https://github.com/vectorxxxx/vectorxxxx.github.io
# 快速下载必要的文件，过滤模板中博文和图片
# svn checkout https://github.com/vectorxxxx/vectorxxxx.github.io/trunk/ --depth=files
# 2. 自动下载并部署所有依赖
cd vectorxxxx.github.io
bundle install
```



## Run

```shell
# 运行启动命令 s/serve/server is all right!
bundle exec jekyll serve
# 如果出现端口冲突，可以手动指定端口号
bundle exec jekyll serve --port [port]
```



---



## Themes

- :heart: ​http://jekyllthemes.org/
- :heart: ​https://github.com/jekyll/jekyll
- :heart: https://jekyllthemes.dev/



## Theme

- :star: [wu-kan/wu-kan.github.io: my homepage & template for jekyll-theme-WuK](https://github.com/wu-kan/wu-kan.github.io)
- :star: ​[Huxpro/huxpro.github.io: My Blog / Jekyll Themes / PWA](https://github.com/Huxpro/huxpro.github.io)
- :star: ​[mattvh/jekyllthemes: A directory of the best-looking themes for Jekyll blogs (github.com)](https://github.com/mattvh/jekyllthemes)
- :star: ​[mmistakes/minimal-mistakes: Jekyll theme for building a personal site, blog, project documentation, or portfolio. (github.com)](https://github.com/mmistakes/minimal-mistakes/)



## Link

- :link: [星合の空 | wu-kan](https://wu-kan.cn/)
- :link: [不安分的猿人 (gitee.io)](http://huaairen.gitee.io/)
- :link: [黄玄的博客 | Hux Blog (huangxuan.me)](https://huangxuan.me/)
- :link: [主页 - 资源库 (leachchen.com)](https://www.leachchen.com/#/)
- :link: [LiberXue|FullStack|独立开发者|jekyll blog|GitHub blog](https://liberxue.github.io/book/?liberxue)



---



## 参考手册

- :closed_book: [GitHub Pages | Websites for you and your projects, hosted directly from your GitHub repository. Just edit, push, and your changes are live.](https://pages.github.com/)
- :closed_book: [快速指南 - Jekyll • 简单静态博客网站生成器 (jekyllcn.com)](http://jekyllcn.com/docs/quickstart/)
- :closed_book: [如何快速正确的安装 Ruby, Rails 运行环境 · Ruby China (ruby-china.org)](https://ruby-china.org/wiki/install_ruby_guide/)
- :closed_book: [Quick-Start Guide - Minimal Mistakes (mmistakes.github.io)](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)
- :closed_book: [快速开始 | Valine 一款快速、简洁且高效的无后端评论系统。](https://valine.js.org/quickstart.html)
- :closed_book: [配置 - Merger (justhx.com)](https://merger.justhx.com/cn/docs/configure)
- :closed_book: [Shields.io: Quality metadata badges for open source projects](https://shields.io/)



## 参考资料

- :book: [基于Jekyll搭建个人博客](https://wu-kan.cn/_posts/2019-01-18-基于Jekyll搭建个人博客/)
- :book: [Jekyll + Github Pages 搭建个人免费博客](https://zhuanlan.zhihu.com/p/87225594)
- :book: [Jekyll + Github Pages 博客搭建入门](https://www.jianshu.com/p/9f198d5779e6)
- :book: [Github+Jekyll 搭建个人网站详细教程](https://www.jianshu.com/p/9f71e260925d)

