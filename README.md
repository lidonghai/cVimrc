加载配置的两种方式：

###  本地加载

**ATTENTION**
使用本配置文件时注意：需要在拓展管理里打开“允许访问文件网址”
1. 下载.cVimrc文件到c盘根目录
2. 将以下内容复制到cVim配置中
```
set localconfig
let configpath = 'C:\.cVimrc'
```
3. 保存，然后重启或者刷新浏览器

### 网络加载
直接在"Sync cVimrc with GitHub Gist"栏输入.cVimrc的链接即可，测试发现可能需要Fq。
