# tepig-bridge-python

仅可用于正常学术研究以及技术搜索需要

### 运行环境

类unix系统、python3.6+

无需安装第三方库

### 使用方式

**服务器**

密码必须为整数类型

```bash
nohup python server.py -p [本地监听端口] -P [密码] &
```

**客户端**

密码必须与服务器密码一致

```bash
nohup python client.py -lp [本地监听端口] -rp [服务器端口] -rh [服务器地址] -P [密码] &
```

### 协议

本项目使用[MIT协议](https://github.com/thingerpig/tepig-bridge-python/blob/master/LICENSE)
