# E-commerce_platform1

## 项目介绍
该项目为在线电商项目，使用Vue进行开发，另外涉及了ES6++Webpack+Axios等前端技术进行开发，采用模块化、组件化、工程化的开发模式

## 项目功能
<p><b>首页（Home组件)</b>:涉及了三级列表展示，轮播图，接口请求数据以及多个静态页面的展示</p>

![image](https://github.com/yepiao11/E-commerce_platform1/blob/main/images/home.jpg)

<p><b>商品搜索（Search组件)</b>：涉及了路由参数跳转，面包屑以及页面器的实现</p>

![image](https://github.com/yepiao11/E-commerce_platform1/blob/main/images/search.jpg)

<p><b>详情展示(Detail组件)</b>，涉及了商品的放大与展示等等</p>

![image](https://github.com/yepiao11/E-commerce_platform1/blob/main/images/detail.jpg)

<p><b>购物车(Shopcart组件)</b>，添加商品到购物车，购物车商品的个数增减与修改</p>

![image](https://github.com/yepiao11/E-commerce_platform1/blob/main/images/shopcart.jpg)

另外还有登录注册等其他功能，涉及了封装axios、防抖和节流等技术

## 涉及技术
1.前台数据处理、交互、组件化：vue，vue-router，vuex，element-ui，swiper，moment
<br/>
2.前后台交互：ajax请求（axios，async/await）,mock数据
<br/>
3.模块化：ES6
<br/>
4.项目构建/工程化：webpack，vue-cli
<br/>
5.css预编译器：less
<br/>

## 文档说明
api：ajax请求相关内容
<br/>
assets：放置一些静态资源（例如图片）
<br/>
components：存储非路由组件
<br/>
mock：存储模拟数据
<br/>
pages：存储路由组件
<br/>
router：路由器相关内容
<br/>
store：vuex相关
<br/>
utils：工具函数模块
<br/>
App.vue:应用组件
<br/>
main.js入口文件
<br/>
babel.config.js:babel配置文件
<br/>
package.json：看到项目描述、项目依赖、项目运行指令
<br/>

## 操作步骤
### 进入项目目录
cd E-commerce_platform1
### 安装依赖
npm install
### 启动服务
npm run serve
