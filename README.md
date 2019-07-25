# Taro 小程序搭建

## 初始化依赖，下载所有依赖
```
npm install
```

### 微信小程序编译模式
```
npm run dev:weapp  
***
npm run build:weapp
```

### 支付宝小程序编译模式
```
npm run dev:alipay  
***
npm run build:alipay
```
### h5编译模式
```
npm run dev:h5  
***
npm run build:h5
```
### eslint， eslint fix处理，提交之前会处理此操作
```
npm run lint
```

### 技术点介绍
本项目使用到typescript + redux数据流  
暂时未使用到ui框架  
建议使用utils工具类 详细如下  
data.js 数组或者对象的 增删改  
dedounce.js 防抖操作  
promiseWrapper.js promise 封装  
index.js 各种工具类  
