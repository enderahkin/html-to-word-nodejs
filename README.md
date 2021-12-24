html-to-word-nodejs
============
    该依赖包可使用nodeJS将html转成word文档。
# 使用方式
1. 安装依赖
> cnpm i html-to-word-nodejs
2. 示例
```javascript
var HtmlDocx = require('html-to-docx-nodejs');
var htmldemo='<h1>测试</h1>'
var options={
    content:htmldemo,
    docname:'demo',
    path:'/OutDir'
}

//参数说明
//options.content   html字符串
//options.docname   输出的docx文档名
//options.path      输出的docx路径

HtmlDocx.todoc(htmldemo,options)
```
