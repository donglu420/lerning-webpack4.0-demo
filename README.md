# learning-webpack4.0-demo
学习webpack4.0的笔记心得和一些小demo源码
## webpack安装
	- 安装本地的webpack
	- webpack webpack-cli -D//-d表示上线时不需要
## webpack可以进行配置
	- 打包工具 -> 输出后的结果 （js模块)

	-打包(支持我们的js的模块化）

## 手动配置webpack
	-默认配置文件的名字 webpack.config.js
	- 手动配置使用npx webpack --config xxxxx.js
	- 或者可以手动配置package.json文件添加脚本
		"scripts": {
  		"build":"webpack --config webpack.config.my.js"
 			 }
  		使用npm run bulid即可
## HTML插件
