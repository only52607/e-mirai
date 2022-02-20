# e-mirai
 基于mirai-http-api的epl sdk

# 注意

本项目目前暂停维护，源码中部分写法或许已经过时。

如需编写Mirai插件，请改用其他编程语言。

# 开始

## 1.环境配置
### （1）安装[`mirai-console-loader`](https://github.com/iTXTech/mirai-console-loader)并启动。
### （2）导入[`http-api`](https://github.com/project-mirai/mirai-api-http)插件，并记录下端口及Key值。
### （3）在Console终端登录bot。

## 2.开始开发
### （1）新建e程序文件。
### （2）导入e-mirai模块，在"Mirai.初始化"方法中填入本机ip与端口以及刚刚记录下的Key值。
### （3）开始开发，你可以通过"示例.e"学习基本用法。



## 已实现功能

- [x] 群和好友消息发送

- [x] 复杂消息构造（包括引用回复、图片消息、At消息、闪图、XML等）

- [x] 图片上传

- [x] 消息撤回

- [x] 好友取备注、昵称等操作

- [x] 群禁言、移除等操作

- [x] 群和好友消息监听

- [x] 群禁言，入群等事件监听

## 待实现功能

- [ ] 好友变动，机器人变动各类事件监听


## 已知问题

进行消息监听时会有几率发生闪退。



# 原项目
[`mirai`](https://github.com/mamoe/mirai): 多平台 QQ Android 和 TIM PC 协议支持库与高效率的机器人框架.

