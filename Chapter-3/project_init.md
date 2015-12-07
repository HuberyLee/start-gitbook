# 初始化图书项目

在完成一个基本的图书项目结构的创建后，我们需要在 **SUMMARY.md** 文件中录入我们所要编写的图书的目录结构信息，格式如下：

```bash
* [GitBook简介](Chapter-1/README.md)
* 基本安装
    * [Node.js安装](Chapter-2/node.js_install.md)
    * [GitBook安装](Chapter-2/gitbook_install.md)
    * [基本命令](Chapter-2/gitbook_command.md)
* 编写图书项目结构
    * [图书项目结构](Chapter-3/book_format.md)
    * [初始化图书项目](Chapter-3/project_init.md)
    * [生成与发布](Chapter-3/generate_and_post.md)
```

保存后，使用命令 ``gitbook init`` 初始化我们的图书项目，这时GitBook会根据我们的目录结构信息生成所对应的目录和文件：

```bash
lihuis-MacBook-Pro:how_to_start_gitbook lihui$ tree
.
├── Chapter-1
│   └── README.md
├── Chapter-2
│   ├── gitbook_command.md
│   ├── gitbook_install.md
│   ├── node.js.png
│   ├── node.js_install.md
│   ├── preview_osx.jpg
│   └── sublime_text.png
├── Chapter-3
│   ├── book_format.md
│   ├── generate_and_post.md
│   └── project_init.md
├── README.md
├── SUMMARY.md
├── _book
│   ├── Chapter-1
│   │   └── index.html
│   ├── Chapter-2
│   │   ├── gitbook_command.html
│   │   ├── gitbook_install.html
│   │   ├── node.js.png
│   │   ├── node.js_install.html
│   │   ├── preview_osx.jpg
│   │   └── sublime_text.png
│   ├── Chapter-3
│   │   ├── book_format.html
│   │   ├── generate_and_post.html
│   │   └── project_init.html
│   ├── gitbook
│   │   ├── app.js
│   │   ├── fonts
│   │   │   └── fontawesome
│   │   │       ├── FontAwesome.otf
│   │   │       ├── fontawesome-webfont.eot
│   │   │       ├── fontawesome-webfont.svg
│   │   │       ├── fontawesome-webfont.ttf
│   │   │       └── fontawesome-webfont.woff
│   │   ├── images
│   │   │   ├── apple-touch-icon-precomposed-152.png
│   │   │   └── favicon.ico
│   │   ├── plugins
│   │   │   ├── gitbook-plugin-fontsettings
│   │   │   │   ├── buttons.js
│   │   │   │   └── website.css
│   │   │   ├── gitbook-plugin-highlight
│   │   │   │   ├── ebook.css
│   │   │   │   └── website.css
│   │   │   ├── gitbook-plugin-livereload
│   │   │   │   └── plugin.js
│   │   │   ├── gitbook-plugin-search
│   │   │   │   ├── lunr.min.js
│   │   │   │   ├── search.css
│   │   │   │   └── search.js
│   │   │   └── gitbook-plugin-sharing
│   │   │       └── buttons.js
│   │   └── style.css
│   ├── index.html
│   └── search_index.json
└── book.json

17 directories, 43 files
```

随后，我们就可以在对应章节的对应文件中编写对应的内容了。
