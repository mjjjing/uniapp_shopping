# uniapp_shopping 项目介绍

## 一、项目概述  
**uniapp_shopping** 是一个基于 UniApp 框架开发的跨平台购物应用项目。该项目允许开发者编写一套代码，同时发布到 iOS、Android、H5 以及各种小程序等多个平台，极大地提高了开发效率和应用的覆盖范围。本应用为用户提供了便捷的购物体验，涵盖商品展示、搜索、购物车管理、订单处理等常见购物功能。

## 二、功能特性

### 商品展示
- 以列表和网格形式展示丰富的商品信息，包括商品图片、名称、价格和简要描述  
- 支持商品分类浏览，方便用户快速找到所需商品

### 商品搜索
- 提供强大的搜索功能，用户可以通过关键词搜索特定商品  
- 支持模糊搜索，提高搜索的准确性和灵活性

### 购物车管理
- 用户可以将喜欢的商品添加到购物车中，并随时修改商品数量  
- 购物车支持商品总价计算和批量删除功能

### 订单处理
- 用户可以在购物车中选择商品进行下单，并选择支付方式完成支付  
- 提供订单状态跟踪功能，用户可以查看订单的支付状态、发货状态和收货状态

### 用户信息管理
- 支持用户注册和登录功能，方便用户管理个人信息和订单  
- 用户可以修改个人资料、收货地址等信息

## 三、技术栈

| 模块       | 技术实现                     |
|------------|------------------------------|
| 前端框架   | UniApp                       |
| 编程语言   | Vue.js、JavaScript           |
| 样式设计   | CSS、SCSS                    |
| 后端服务   | ( Node.js + Express)         |
| 数据库     | MySQL                       |

## 四、安装与运行

### 1. 克隆项目  
`git clone https://github.com/mjjjing/uniapp_shopping.git`  
`cd uniapp_shopping`

### 2. 安装依赖  
`npm install`

### 3. 运行项目  
- **开发环境**：在 HBuilderX 中打开项目，选择相应的运行平台（如微信小程序模拟器、浏览器等），点击运行按钮即可  
- **生产环境**：在 HBuilderX 中进行项目打包，根据不同平台的要求进行发布  

## 五、项目结构

```
uniapp_shopping/
├── pages/           # 页面文件
│   ├── index/       # 首页
│   ├── goods/       # 商品详情页
│   ├── cart/        # 购物车页
│   ├── order/       # 订单页
│   └── user/        # 用户信息页
├── components/      # 组件文件
├── static/          # 静态资源文件（图片、字体等）
├── uni.scss         # 全局样式文件
├── pages.json       # 页面配置文件
├── manifest.json    # 项目配置文件
└── package.json     # 项目依赖配置文件
```

## 六、贡献指南  
如果你想为这个项目做出贡献，请遵循以下步骤：  

1. Fork 这个仓库到你自己的 GitHub 账户  
2. 创建一个新的分支：`git checkout -b feature/your-feature-name`  
3. 进行代码修改和功能开发  
4. 提交你的更改：`git commit -m "Add your commit message"`  
5. 推送分支到你的远程仓库：`git push origin feature/your-feature-name`  
6. 在 GitHub 上创建一个 Pull Request，详细描述你的更改和功能  

## 七、问题反馈  
如果你在使用过程中遇到任何问题或有任何建议，请在 GitHub Issues 中提交：  
https://github.com/mjjjing/uniapp_shopping/issues  

## 八、许可证  
本项目采用 **MIT 许可证**