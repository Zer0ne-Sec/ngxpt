<center><h2>ngxpt</h2></center>

<center><font size=2>新一代XSS平台，持续性连接，分布式部署，远控般体验</font></center>

<center><div style="float"><img src="https://img.shields.io/github/stars/Zer0ne-Sec/ngxpt?style=social"><img src="https://img.shields.io/github/forks/Zer0ne-Sec/ngxpt?style=social"><img src="https://img.shields.io/github/sponsors/Zer0ne-Sec"></div></center>

## ngxpt

当前市面上的XSS平台基本都是同一套源码搭建出来的，较为久远，且使用一次功能(截图、获取cookie等)就需要插入一次链接。假设下现在某系统后台留言处有一个XSS点，但是每插一次都会接到客服打来的电话，这体验太糟糕了。使用ngxpt可以只需要插入一次链接，之后想获取什么信息，直接选中相应的模块，点击发送就可以了，享受远控般的体验。

本项目采用golang+echo+vue进行开发，分布式部署，加密传输，私有节点。

私有节点：用户可申请自己创建节点，并决定是否开放，若决定不开放，则该节点为私有节点。私有节点，仅创建者本身可使用，且相关数据保存在该节点上。

## 特点

- 远控般的使用体验
- 多节点分布式
- 私有节点存储数据

## 计划开发

- 通知反馈
- 私有节点
- 用户管理



## 更新日志

### v0.0.1-beta(2021/07/22)

- 项目上线



## 使用说明

### 1. 创建任务

