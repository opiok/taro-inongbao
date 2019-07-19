#taro-inongbao

#基于taro框架开发

#项目运行方法：

##1.cd taro-inongbao
tip:
 如果没有taro-inongbao文件夹内没有node_modules,
 运行命令：
 npm i
 npm i yarn -g

##2.npm run dev:weapp 

#代码编辑：
推荐vscode
微信开发者工具不支持jsx文件

#效果查看：
打开微信者开发工具，
添加新项目，文件夹指定为  含有node_modules的taro-inongbao文件夹



#资料参考：

小程序开发文档：https://developers.weixin.qq.com/miniprogram/dev/framework/

taro：https://taro-docs.jd.com/taro/docs/GETTING-STARTED.html

taro-ui：https://taro-ui.jd.com/#/docs/quickstart




范例：

一个可靠的 Taro 项目可以按照如下方式进行组织

├── config                 配置目录
|   ├── dev.js             开发时配置
|   ├── index.js           默认配置
|   └── prod.js            打包时配置
├── src                    源码目录
|   ├── components         公共组件目录
|   ├── pages              页面文件目录
|   |   ├── index          index 页面目录
|   |   |   ├── banner     页面 index 私有组件
|   |   |   ├── index.js   index 页面逻辑
|   |   |   └── index.css  index 页面样式
|   ├── utils              公共方法库
|   ├── app.css            项目总通用样式
|   └── app.js             项目入口文件
└── package.json



