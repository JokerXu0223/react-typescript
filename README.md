###版本环境
```html
node 6.0+(v8.11.1)
npm 3.0+(v5.6.0)
```
## 技术栈
基于create-react-app 
React+Redux+Antd

### 项目结构
```html
|--public 
  |--index.html  全局入口
  
|--src     源文件
  |--actions        动作
  |--assets         静态资源
  |--components     组件
  |--config         配置
  |--constants      常量
  |--entity         数据模型
  |--reducers       所有store函数
  |--routes         路由配置
  |--stores         store配置
  |--utils          工具
  |--themes         less主题样式
  |--views          容器视图
    |--Error        错误页面
    |--Hello        首页
    |--Hello        demo
    |--app.less     Layout入口less
    |--app.tsx      Layout入口
  
  |--index.tsx      全局入口js
  |--index.less     全局入口css
  
|--config-overrides.js 覆盖create-react-app配置
|--package.json
|--README.md
|--tsconfig.json
|--tsconfig.test.json
|--tslint.json
```

###配置
```html
$ npm install -g  yarn
```

### 安装依赖
* Run 'yarn'

### 开发环境
* Run 'yarn start'

### 打包
* Run 'yarn build'

### 注意安装依赖
```html
需要安装typeScript的版本
$ npm install -S redux react-redux @types/react-redux(类似)
```
