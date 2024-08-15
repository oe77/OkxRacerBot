[![Static Badge](https://img.shields.io/badge/Telegram-Bot%20Link-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/OKX_official_bot/OKX_Racer?startapp=linkCode_116016253)

# 🔥🔥 [OKX Racer游戏入口](https://t.me/OKX_official_bot/OKX_Racer?startapp=linkCode_110429030) 🔥🔥

- [OKX Racer游戏说明](https://www.okx.com/zh-hans/help/okx-racer-players-guide) 

![image](https://github.com/oe77/OkxRacerBot/blob/master/2024-08-15_202044.png)


## 功能  
| 功能                                                   | 支持 |
|-----------------------------------------------------------|:---------:|
| 支持多用户                                            |     ✅     |
| 支持代理                                  |     ✅     |
| 支持 tdata / pyrogram .session / telethon .session |     ✅     |
| 自动猜测价格                                              |     ✅     |
| 自动车手任务 (KYC除外)                                   |     ✅     |
| 自动伙伴任务                                                |     ✅     |
| 自动第日任务                                               |     ✅     |


## 设置
| 设置                |                                 简介                                 |
|-------------------------|:---------------------------------------------------------------------------:|
| **API_ID / API_HASH**   | Telegram API 密钥 (默认 - android) |
| **SLEEP_TIME**          |             运行间隔时间 (默认 - [300, 500])             |
| **AUTO_BOOST**          |                     自动加满燃料箱 (默认 - True)                      |
| **BOOSTERS**            |              自动升级燃料箱与涡轮增压器 (默认 - True)              |
| **AUTO_TASK**           |                自动任务（KYC 任务除外） (默认 - True)                |
| **USE_REF**             |                      使用 ref 链接（默认 - True)                      |
| **RANDOM_PREDICTION**   |                随机猜测价格（默认值 - True)                 |
| **MAX_COMBO_COUNT**     |                       最大组合数（默认 - 28)                        |
| **USE_PROXY_FROM_FILE** | 是否开启代理 bot/config/proxies.txt  (True / False)  |



## 1.安装
- 1.安装 [Python](https://www.python.org/downloads/release/python-31014/) **version 3.10**
- 2.克隆OkxRacerBot
```shell
git clone https://github.com/Desamod/OkxRacerBot.git
cd OkxRacerBot
```

# 2.自动安装OkxRacerBot:

Windows:
```shell
run.bat
```

Linux:
```shell
run.sh
```


## 3.获取 telegram API 密钥
1. 登录[telegram API](https://my.telegram.org)。 PS:电话地址要跟IP对上,不然报错
2. 选择 "API development tools" 填写表格注册新的Android应用程序。
3. 将 API_ID 与 API_HASH 填写到 .env 文件。


## 4.设置代理
1.编辑 .env 文件开启代理 USE_PROXY_FROM_FILE=True

2.编辑 bot/config/proxies.txt 文件添加代理服务器，例http://127.0.0.1:7890


## 5.创建会话
```shell
Select an action:

    1. Run clicker
    2. Create session

> 2

Enter the session name (press Enter to exit): 随便填入会话名称
Welcome to Pyrogram (version 2.0.106)
Pyrogram is free software and comes with ABSOLUTELY NO WARRANTY. Licensed
under the terms of the GNU Lesser General Public License v3.0 (LGPL-3.0).

Enter phone number or bot token: 填入手机号获取验证码 +区号
```

## 6.运行

Select an action:
```shell
    1. Run clicker
    2. Create session

> 1
```


# Linux 手动安装
```shell
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # 填写你的telegram API_ID和API_HASH，其余的采用默认
python3 main.py
```

您还可以使用参数进行快速启动，例如：
```shell
~/OkxRacerBot >>> python3 main.py --action (1/2)
# Or
~/OkxRacerBot >>> python3 main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```

# Windows 手动安装
```shell
git clone https://github.com/Desamod/OkxRacerBot.git
cd OkxRacerBot

python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# 填写你的telegram API_ID和API_HASH，其余的采用默认
python main.py
```

您还可以使用参数进行快速启动，例如：
```shell
~/OkxRacerBot >>> python main.py --action (1/2)
# Or
~/OkxRacerBot >>> python main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```
[![Static Badge](https://img.shields.io/badge/Telegram-Channel-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/desforge_crypto)

