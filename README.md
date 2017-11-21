# build-a-simple-website-from-imooc-course
项目主要来自imooc的课程实例，项目基于Node.js+Express+MongoDB搭建的小型电影网站，通过学习可以大概了解建站的一个过程。

## 主要页面
前台页面：电影列表页、电影详情页、登录页、注册页
后台页面：电影录入更新页、电影管理列表、用户管理列表、电影分类添加页

## 主要功能
用户登录注册、用户登录持久化、电影录入更新（同步豆瓣api、海报上传）、用户评论、电影搜索

## 技术栈
### 前台
Bootstrap、Moment.js

### 后台
Jade：前端模板渲染引擎，用于输出前端页面
Nodejs：后台运行平台
Express：测试服务器
MongoDB：数据库
Mongoose：数据库管理

### 自动化构建
grunt：检测文件改动并自动构建
bower：第三方静态文件库管理
jshint：js校验

## Build Setup
```
# clone the repo into your disk.
$ git clone https://github.com/Huitimkit/build-a-simple-website-from-imooc-course.git

# install dependencies
$ npm install

# run
$ grunt

# visit
$ http://localhost:3000/
```

## Thanks
@imooc @Scott
