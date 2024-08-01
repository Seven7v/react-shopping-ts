# react ts 项目demo 学子笔记


## 创建项目
- 初始化项目
```javascript
npx create-react-app appName --template typescript
```

- 安装项目响应依赖
```javascript
npm i redux react-redux redux-thunk redux-logger -S

npm i react-router-dom axios nprogress normalize.css antd -S

npm i sass sass-loader -D
```

- 初始化目录
```
project
│   README.md
│   .env    
│   package.json
└───src
│    └───api  // 接口 
│    └───pages // 页面
│    └───store  // 状态管理
│    └───utils  // 工具
│    └───type // ts
│    └───fils //  ...初始化项目自动生成文件内容
└───node_modules
    │   ...
```
