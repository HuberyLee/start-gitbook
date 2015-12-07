# 图书项目结构

一个图书项目根目录下包含以下文件：

* **README.md:** REAME相当于书籍的前言部分
* **SUMMARY.md:** SUMMARY是最重要的一个部分, 它创建的是整书的索引, 你也可以通过gitbook init读取SUMMARY.md来生成目录结构
* **LANGS.md:** 当你需要发布多个语言版本时，根目录需要放置一个LANGS.md
* **GLOSSARY.md:** List of terms with descriptions
* **book.json:** 图书项目的配置文件

其中，**README.md:** 文件和 **SUMMARY.md:** 文件是一个图书项目中必须有的，其他的文件可以根据需要自行添加。那么，新建一个简单的图书项目后，目录结构大概如下：

```
lihuis-MacBook-Pro:how_to_start_gitbook lihui$ tree
.
├── README.md
└── SUMMARY.md

0 directories, 2 files
```
