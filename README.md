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