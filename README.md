# 个人简历

- 卜成健/男/1994 
- 手机：13160300173
- Email：freebreaker@aliyun.com
- QQ：592378845
- 微信： bcj15251769638.

## 基本信息

 - 学历:本科 
 - 期望职位：前端工程师
 - 期望薪资：8k~10k
 - 期望城市：上海/杭州
 - Github：http://github.com/freebreaker
 - 语言能力：CET6
 - [个人博客](http://www.jianshu.com/u/e5a631722da0)

 

## 项目经历

### Vue版知乎日报 2017/07~2017/07

#### 项目介绍

Vue知乎日报，具有主题日期功能，暂支持手机端。[预览地址](http://dadaluobo.site:8228/) / [GitHub源码](https://github.com/freebreaker/vue-dailyPaper) 

#### 实现方式

利用vue-cli生成项目，通过vue-router实现单页路由跳转，通过ajax来获取接口数据，并渲染到页面；通过Vuex状态管理，将日期，文章id等复用数据共享，遵循共享组件的思路；通过Webpack打包，线上部署到阿里云服务器。CSS设计上采用Mint UI; 后端用Nodejs,对跨域的数据接口进行了转发。

#### 项目收获?

复用组件时，解决界面刷新的问题。
遇到跨域问题，在开发环境下的跨域可以在config里设置，但部署到线上的时候出错，多番查询后先是设置了nginx代理，然后又尝试着Node转发接口，在此过程中文件位置屡屡出错，改变默认build文件位置即可。

#### 技术栈

Vue/Node




### React Todo应用 2017/06~2017/07

#### 项目介绍

React Todo应用。具有完整的登录，注册，邮箱找回密码功能。[预览地址](https://freebreaker.github.io/leanCloudTodo/build/index.html) / [GitHub源码](https://github.com/freebreaker/leanCloudTodo/tree/master/src) 

#### 实现方式

将组件逐一细分，尽量做到每一块都是一个独立的组建，方便日后修改，将状态放在顶层APP，通过props分发给子组件，通过state来管理数据状态，在渲染时，通过过滤筛选函数，把todoitem筛选然后渲染到页面；通过路由实现单页面的路由跳转，最后将账号密码部署到LeanCloud,并参考文档，增添邮箱找回密码。

#### 项目收获?

React入门，掌握了React数据由上而下分发机制，熟悉JSX语法，在重构的过程中熟悉组件拆分，掌握父子组件的通信。

#### 技术栈

React/LeanCloud





### MyBlog 2017/05~2017/06

#### 项目介绍

具有注册登录，发表文章的个人博客[预览地址](https://dadablog.herokuapp.com/signin)/[GitHub源码](https://github.com/freebreaker/FreeBlog)

#### 实现方式

运用Nodejs,线上部署可登陆的博客，通过路由实现单页面跳转，本地将数据存放在mongodb，线上最终部署到Heroku，数据存放在Mlab.

#### 项目收获?

Node入门,熟悉正常网站搭建的基本流程。

#### 技术栈

Nodejs/Mongodb



### FM音乐电台 2017/05~2017/06

#### 项目介绍

FM音乐电台[预览地址](https://freebreaker.github.io/FM-Radio/music.html)/[GitHub源码](https://github.com/freebreaker/FM-Radio)

#### 实现方式

运用原生JS，实现歌词滚动，单曲循环，下一首等功能；JQuery Ajax的Jsonp获取数据，根据接口数据将歌词的时间做间隔，歌词滚动；通过歌曲长度的百分比来对歌曲进行快进；歌曲时间转格式；原生CSS写基本样式,支持移动端。

#### 项目收获?

原生JS的熟练运用，包括函数的封装，函数原型链的相关知识，遇到的难点在后端数据获取之后，对数据采取的方法要与功能对应，样式与JS分离。

#### 技术栈

原生JS/Jquery




## 掌握技能

- 能够书写语义合理，结构清晰，易维护的HTML结构，能够高度还原设计稿，完成较为复杂的布局,熟悉Less/SaSS等预处理工具
- 熟悉原生JS，Ajax，掌握常见的跨域方式，如Jsonp,CORS
- 能够封装常用的一些组件，比如轮播、Tab、懒加载、木桶布局等
- 了解ES6的一些常见语法，并在项目中应用
- 熟悉HTTP，对Node有一定的使用经验
- 对前端框架jQuery/Bootstrap/Vue/React 有项目经验
- 对前端工具：NPM/Gulp/Webpack 有使用经验
- 熟悉版本管理Git的使用
- 熟悉Express，Mongodb，能够搭建中等难度的网站项目


## 自我评价


感谢您与百忙之中阅读我的简历，转行互联网是我个人生涯做的最重要的决定之一。我认为诚实，努力，智慧是程序员必备的品质，也是我转行的原因。在传统行业待久了，难免多些尔虞我诈。在学习能力方面，能够阅读英文文档，对于新框架新技术也有学习的热情，漫漫长夜敲代码，不失为创造的享受。希望能够与您共事以及共同进步。
