## 前端在线数据mock服务

[mock-oint](http://mock-oint.61info.cn/) 是一个旨在为公司内部开发同学提供在线数据mock的服务平台，通过私有化搭建easy-mock来实现，可在内网放心使用。

### 启动
```bash
$ npm run dev
# 访问 http://127.0.0.1:7300
```

### 更多命令
```
# 前端静态资源构建打包
$ npm run build

# 以生产环境方式启动，需要提前执行 build
$ npm run start

# 单元测试
$ npm run test

# 语法检测
$ npm run lint
```

### 服务器部署
#### 通过jenkin 触发构建部署和启动（若启动失败需要到服务器手动启动）
```bash
npm run pm2:start
```
