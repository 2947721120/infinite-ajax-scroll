Infinite AJAX Scroll
====================

jQuery插件把你的分页的页面到无限滚动网页提供方便。
下载，文档和演示，请访问： http://infiniteajaxscroll.com/

[![Build Status](https://travis-ci.org/webcreate/infinite-ajax-scroll.png?branch=master)](https://travis-ci.org/webcreate/infinite-ajax-scroll)

## Licensing
无限AJAX滚动可以用在商业项目和应用程序一次性购买商业许可。

http://infiniteajaxscroll.com/docs/license.html

对于非商业的，个人的，或者开源项目和应用程序，你可以使用AJAX的无限滚动在MIT许可的条款。您可以使用AJAX的无限滚动免费。

## 贡献
为了促进无限AJAX滚动，请遵循以下说明：
*叉项目，并创建一个新的特性分支
*安装开发工具
*写功能/修正错误
*未来的/修正错误的写入测试
*运行测试
*提交您的pull请求
### 安装开发工具

1. 安装bower 组件

    ``` sh
    $ bower install
    ```

2. 安装 npm 模块

    ``` sh
    $ npm install
    ```

### 运行测试
测试与完成 [Busterjs](https://github.com/busterjs/buster) and [Grunt](https://github.com/gruntjs/grunt).

1.启动 a buster 服务器：:

    ``` sh
    $ grunt buster::server:block
    ```

2.推出一些浏览器和连接到 `http://localhost:1111` 并捕获它们。

3. 运行测试：

    ``` sh
    $ grunt buster::test
    ```
