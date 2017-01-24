# staticBlog
使用markdown文件生成静态网站


## 文件路径树

1. markdown路径存放使用markdown编写的文章
2. html文件夹是markdown经过编译输出的html静态文件
3. index.html是用来组织blog首页以及串联各个html静态文件的页面
4. server.js是本地预览的服务器

## 技术栈

1. 采用gulp处理文件流
2. 采用gulp-markdown插件编译markdown文件到指定的路径
3. 整个blog的页面布局采用materialize.css框架
4. 服务器静态采用hapi和inert搭建
