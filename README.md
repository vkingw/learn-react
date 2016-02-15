# 环境要求

1. 环境要求 node js环境 ,请安装最新node js 版本
2. 打开cmd(win下)或者终端(mac & linux)执行npm -v 后可以看到显示版本号, **以后所有执行都是指在命令行或者终端下执行**
3. 安装Yeoman 、Bower、Grunt 、Gulp，Mac下可能需要sudo 安装,执行下面命令
   npm install -g yo bower grunt-cli

***

# 构建一个项目

1. 执行 yo 
2. 选择 Install a generator
3. 搜索关键字 react , 稍等片刻(根据网络环境)会出现一些列表, 选择安装 React Webpack
4. 退出yo, 创建一个目录, mkdir reactTest, 进入 cd reactTest
5. 执行yo, 选择React Webpack, 可以给project起名或者用默认的
6. 选择css语言, 默认即可
7. 是否打开 postcss , 根据需求选择 y or N
8. 然后等待项目自动构建,  此时会从网络下载相关的依赖库, 网络环境会影响时间
9. 当看到下面图案时就完成了, 如果错误可以删除node_modules文件夹, 然后执行 npm install 重新下载依赖
   ![](https://github.com/vkingw/learn-react/blob/master/QQ20160215-0%402x.png)

***

# 运行项目

1. npm run start 即可运行项目
2. 打开package.json, 可以看的scripts下的命令都可以运行, 功能如名称所示

***

# ES6学习

在React和Redux的dome代码中会有涉及到ES6的语法, 可以在学习过程中一并学习

***

# React学习

1.建议直接学习官方的教程

  [React官方](https://facebook.github.io/react/)   
  [中文React](http://reactjs.cn/)
  
2.教程里面的例子最好都跟着手敲一边, 不要拷贝粘贴, 有些例子中文中无法跑通, 官方可以

***

# Redux学习

1.建议直接学习官方的教程

   [Redux官方](http://redux.js.org/)   
   [Redux中文](http://camsong.github.io/redux-in-chinese/index.html)
   
2.教程里面的例子最好都跟着手敲一边, 不要拷贝粘贴, 有些例子中文中无法跑通, 官方可以
