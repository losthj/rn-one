
## react Native的介绍和使用

react Native  (全栈工程师)

app的项目

app开发流程
前端  前端设计、用户界面、mock假数据测试
后端  nodejs koa、Mongodb、RESTful API服务

app后端
Koa         搭建API服务
MongoDB     音频视频的建模
七牛云(qiniu)和Cloudinary     静态资源的上传、存储和合并


环境搭建  
1、Nodejs项目构建
2、React Native环境的搭建
3、异常调试
4、Xcode 引入第三方模块

服务器端
1、服务器端频繁的异步处理
2、MongoDB对于数据的建模
3、数据增删改查

前后端连调
1、无后台实现接口
2、Mock本地数据测试


需要苹果电脑开发

为什么选择React Native
JSX语法（react）
1、网页开发
2、APP开发

react核心思想
1、组件形态的生命周期机制
2、状态与属性的数据交换机制

让开发应用变得更加的灵活而又有章法，不再是过去的
html/css/javascript杂糅在一起，事件、行为、展现、
强行分离和抽象的状态，同时性能上也带来提升

在语法这个技术层面react Native的优势
1、react Native是纯的javascript组件化，不掺和不同的语言形态
2、react Native的技术框架，允许你很方便的介入和调用到各个平台下的API
3、RN的布局用到的是flex布局，上手成本很小
4、渲染原生视图的能力

APP开发技术
安卓  java
ios   object C

总而言之，学会React的基本语法以后，可以去开发网页，可以去开发
ios app,可以去开发Android App，一招走遍天下

window安装安卓开发环境
Node  python2.x  JDK1.8

Android 开发环境
安装 Android Studio

安装react native的工具（脚手架） 
	npm install -g react-native-cli
创建react Native init my-app(项目名称)

运行项目
react-native run-android

命令行需要输入
react-native bundle --platform android --dev false --entry-file index.android.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res/
更新项目内容，然后在Android Studio中运行run

异步/同步 sync/await

获取异步函数的返回值

异步函数本身会返回一个Promise,所以我们可以通过then来获取异步函数的返回值