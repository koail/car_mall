# 前言

该项目是由(vue2.x完成的)

# 基本功能
* 轮播图效果 商品详情轮播效果
* 商品立即购买/加入购物车
* 购物车加减数量删除商品(模拟)
* 购物车结算清空
* 商品删除结算
* 模拟支付成功后加入订单
* 商品订单删除
* 模拟订单付款成功生成订单
* Localstorage本地存储数据


## 项目安装及运行
安装脚手架 运行启动服务 浏览器本地访问http://localhost:8080

### 项目可能会遇到的问题
internal/modules/cjs/loader.js:583
    throw err;
    ^

Error: Cannot find module 'chalk'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:581:15)
    at Function.Module._load (internal/modules/cjs/loader.js:507:25)
    at Module.require (internal/modules/cjs/loader.js:637:17)
    at require (internal/modules/cjs/helpers.js:22:18)
    at Object.<anonymous> (D:\wang\car_mall-master\car_mall-master\build\check-versions.js:1:75)
    at Module._compile (internal/modules/cjs/loader.js:689:30)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:700:10)
    at Module.load (internal/modules/cjs/loader.js:599:32)
    at tryModuleLoad (internal/modules/cjs/loader.js:538:12)
    at Function.Module._load (internal/modules/cjs/loader.js:530:3)
npm ERR! code ELIFECYCLE

解决方法：
* 到项目文件夹下，删除node_modules文件和package-lock.json文件。注意不是package.json
* 在项目下运行npm install
* 继续运行npm run dev(vue3是npm run serve)



