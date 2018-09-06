# node-study
node学习笔记

## npm

### 全局安装 -g 

- 只能在命令行中使用
- 默认安装路径 npm root -g

### nrm 
源管理器

```
npm install nrm -g
nrm test 测试链接时间
nrm ls 显示所有的可用源
nrm use name 切换源
```

### nvm
切换node版本

### http-server
创建本地服务
```
npm install http-server -g
http-server -p 300 更改端口号
```

### 本地安装
- 安装之前需要初始化

```
npm init 
```
> package.json中的script可以配置一些快捷方式

### 项目依赖
- 开发时使用，上线也需要
```
npm install name
```

### 开发依赖
- 开发时使用，上线不需要
```
npm install --save-dev name
```

### yarn
```
npm install -g yarn
```
```
yarn init
yarn add name
yarn add name ---dev
yarn remove name
yarn install
```

### npm发布包
```
npm addUser 登录账号

npm publish 发布
```
