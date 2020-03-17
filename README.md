# walle-web

> 这是为 walle 配套开发的前端项目，基于 [vue-admin-template](https://github.com/PanJiaChen/vue-admin-template) 项目开发而来，包含了 Element UI & axios & iconfont & permission control & lint，这些搭建后台必要的东西。

## Build Setup

```bash
# 克隆项目
git clone https://github.com/all4you/walle-web.git

# 进入项目目录
cd walle-web

# 安装依赖
npm install

# 建议不要直接使用 cnpm 安装以来，会有各种诡异的 bug。可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev
```

浏览器访问 [http://localhost:9528](http://localhost:9528)

## 发布

```bash
# 构建测试环境
npm run build:stage

# 构建生产环境
npm run build:prod
```

## 其它

```bash
# 预览发布环境效果
npm run preview

# 预览发布环境效果 + 静态资源分析
npm run preview -- --report

# 代码格式检查
npm run lint

# 代码格式检查并自动修复
npm run lint -- --fix
```

