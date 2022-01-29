# AI-heroku-vless

## 概述

本专案用于在 Heroku 上部署 AIRay WebSocket。

部署完成后，每次启动应用时，运行的 AIRay 将始终为最新版本。

## 部署

### 步骤

> [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/Hardbroke/AI-heroku-vless)

 回到专案首页，点击上面的链接以部署 AIRay

### 变量

对部署时需设定的变量名称做如下说明。

| 变量 | 默认值 | 说明 |
| :--- | :--- | :--- |
| `ID` | `b4821af5-19e6-47e0-8033-33613a9dad14` | VLESS 用户 ID，用于身份验证，为 UUID 格式 |
| `WSPATH` | `/` | WebSocket 所使用的 HTTP 协议路径 |
