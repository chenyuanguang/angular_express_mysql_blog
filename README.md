# 此项目为针对angular、node、mysql实现一个简单的博客系统


# config文件夹
* config.js:数据库的配置信息；
* dbconnect.js:进行数据库连接，采用的是链接池方式；

## db文件夹
* 存储的是数据库sql文件；

## public文件夹
* 存放的是所有的静态服务文件；

## route文件夹

### api文件夹（接口文件夹）

*article.js:文章的插入接口
*detail.js: 文章详情接口
*article.js:文章列表接口

### view文件夹（服务端渲染页面）

* index.html:首页列表渲染
* detail.html:详情页面 
* addArticle.js:文章增加页面


## app.js文件

* 端口号为9999；

## 启动项目：

* `npm install`
* `npm start` 
* `访问9999端口`
