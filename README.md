<p align="center">
  <img height="100px" src="./logo.png" />
</p>

# [CodiMD](https://github.com/hackmdio/codimd)

CodiMD是一个写作与分享 Markdown 的最佳平台。

## 部署

本项目基于开源项目 [CloudBase Framework](https://github.com/Tencent/cloudbase-framework) 开发部署，支持一键云端部署

[![](https://main.qcloudimg.com/raw/67f5a389f1ac6f3b4d04c7256438e44f.svg)](https://console.cloud.tencent.com/tcb/env/index?action=CreateAndDeployCloudBaseProject&appUrl=https%3A%2F%2Fgithub.com%2FTencent-Cloud-Plugins%2FTencentCloudBase-CodiMD&branch=master)

### 配置

- `CMD_DB_URL`: 数据库连接地址
- `CMD_DB_HOST`: 数据库地址
- `CMD_DB_PORT`: 数据库端口
- `CMD_DB_NAME`: 数据库名称
- `CMD_DB_USERNAME`: 数据库用户名
- `CMD_DB_PASSWORD`: 数据库密码
- `CMD_USECDN`: 是否使用CDN

### 依赖

- CynosDB：使用 CynosDB 数据库存储数据

## 注意事项

1. 部署时，需要将服务路径设置为根路径 `/`
