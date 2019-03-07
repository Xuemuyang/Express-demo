# Express-demo

Node.js实战第二版Express项目

## 实现功能

- 配置
  - 环境
- 视图渲染
  - ejs模板引擎
- 路由
  - Web UI路由
  - API 路由
- 错误处理
  - 404
  - 500
- 开发日志
- 数据库操作
- 会话
- 表单验证
  - 特定路由上使用校验中间件
- 中间件
- 登录/注册
  - 密码加密

### 配置

环境变量 `NODE_ENV` ，通过 Express 的一组 API 去操作。

### 视图渲染

生产环境中 view cache 默认开启，开发环境禁用。

数据传到视图，变量会从以下寻找，优先级从高到低

- `res.render()`参数
- res.locals
- app.locals

## 模块

- `body-parser` extract the entire body portion of an incoming request stream and exposes it on req.body.
