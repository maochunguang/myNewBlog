# myNewBlog
## 本地运行，或者发布到github的gh-pages
1. 全局安装gitbook-cli,gh-pages
`npm install gitbook gitbook-cli gh-pages -g`

2. 本地发布和运行
```bash
cd myNewBlog
gitbook install ## 按照本地依赖
gitbook build ## 本地build，生成_book
gitbook serve ## 本地运行查看
gh-pages -d _book ## 发布到gh-pages分支
gitbook pdf . ## 在目录下生成pdf文件
gitbook epub .  ## 在目录下生成epub文件
```
3. 在线阅读该文档 
[github java-inteview](https://maochunguang.github.io/java-interview/) 
[gitee java-inteview](https://mcg_dev.gitee.io/java-interview/) 