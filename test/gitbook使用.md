#gitbook安装使用
###1、安装
首先到[nodejs](http://nodejs.cn/)下载，然后安装Node.js的包管理器npm。
然后，通过`sudo npm install -g gitbook-cli`命令安装gitbook
###2、使用
创建一个文件夹，然后初始化

```
mkdir test
gitbook init
```
初始化之后会有两个文件README.md和SUMMARY.md,README.md 是作品的介绍，SUMMARY.md 是作品的目录结构，里面要包含一个章节标题和文件索引的列表：

```
# Summary

This is the summary of my book.

* [section 1](section1/README.md)
    * [example 1](section1/example1.md)
    * [example 2](section1/example2.md)
* [section 2](section2/README.md)
    * [example 1](section2/example1.md)
```
初始化书以后，我们就该创建对应章节的内容了。在这里，我们可以先创建对应的文件夹，然后在里面编辑对应的内容，之后更新SUMMARY.md这个目录文件；如果在编辑之前我们已经确定好了内容标题和目录，也可以先编辑SUMMARY.md文件，然后通过`gitbook init`来初始化一遍，它会自动创建文件目录和对应的md文件。


###参考：
[Gitbook 的使用和常用插件](http://zhaoda.net/2015/11/09/gitbook-plugins/)   
[Mac下GitBook制作电子书](http://liaoer.net/2015/04/30/Mac%E4%B8%8BGitBook%E5%88%B6%E4%BD%9C%E7%94%B5%E5%AD%90%E4%B9%A6/) 
[使用GitBook](http://blog.windrunner.info/app/gitbook-tutorial.html)    
[Gitbook 使用入门](http://wanqingwong.com/gitbook-zh)