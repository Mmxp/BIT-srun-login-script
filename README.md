fork自https://coding.net/u/huxiaofan1223/p/jxnu_srun/git

# 概述

NCU移动深澜校园网登录python脚本，可用于任何支持python的设备的网络命令行登录或命令行登录。

# 文件说明

|文件|说明|
|:-:|:-:|
|BitSrunLogin/|深澜登录函数包|
|demo.py|登录示例脚本|
|always_online.py|在线监测脚本，如果监测到掉线则自动重连|

always_online.py可采用`nohup`命令挂在后台：
``` bash
nohup python always_online.py &
```
