# 基本命令

跟其他的Linux命令一样，我们可以使用 ``命令 -h`` 的形式查看命令的使用信息：

```bash
lihuis-MacBook-Pro:GitBook lihui$ gitbook -h

  Usage: gitbook [options] [command]


  Commands:

    versions                          list installed versions
    versions:print                    print current version to use in the current directory
    versions:available                list available versions on NPM
    versions:install [version]        force install a specific version of gitbook
    versions:link [folder] [version]  link a version to a local folder
    versions:uninstall [version]      uninstall a specific version of gitbook
    versions:update [tag]             update to the latest version of gitbook
    help                              list commands for a specific version of gitbook
    *                                 run a command with a specific gitbook version

  Options:

    -h, --help               output usage information
    -V, --version            output the version number
    -v, --gitbook [version]  specify GitBook version to use
    -d, --debug              enable verbose error
```

从输出的信息，我们可以看到，使用命令 ``gitbook help`` 可以查看GitBook所有的命令：

```bash
lihuis-MacBook-Pro:GitBook lihui$ gitbook help
  build [book] [output]      build a book
    --format     Format to build to (Default is website; Values are website, json, ebook)
    --log    Minimum log level to display (Default is info; Values are debug, info, warn, error, disabled)

  pdf [book] [output]    build a book to pdf
    --log    Minimum log level to display (Default is info; Values are debug, info, warn, error, disabled)

  epub [book] [output]   build a book to epub
    --log    Minimum log level to display (Default is info; Values are debug, info, warn, error, disabled)

  mobi [book] [output]   build a book to mobi
    --log    Minimum log level to display (Default is info; Values are debug, info, warn, error, disabled)

  serve [book]   Build then serve a gitbook from a directory
    --port   Port for server to listen on (Default is 4000)
    --lrport     Port for livereload server to listen on (Default is 35729)
    --watch      Enable/disable file watcher (Default is true)
    --format     Format to build to (Default is website; Values are website, json, ebook)
    --log    Minimum log level to display (Default is info; Values are debug, info, warn, error, disabled)

  install [book]     install plugins dependencies

  init [directory]   create files and folders based on contents of SUMMARY.md
```

可以看到，GitBook的命令并不多，使用起来还是比较简单的。
