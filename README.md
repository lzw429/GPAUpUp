# 东北大学 GPA 提醒

使用 `Python 3`

## 功能
- 定期查询 GPA
- 邮件通知 GPA 更新

## 依赖

 `requirements.txt` 列举了可能需要的模块
 
推荐使用 pip 安装，在 Linux 下可以使用如下命令

```sh
sudo apt-get install python-pip         
sudo pip install requests
sudo pip install schedule
sudo pip install pytesseract
```

## 设置

账户密码等信息在 `GLOBAL` 变量中。

发送提醒的邮箱需要 pop3 服务，然后将授权码写到 `GLOBAL\['SEND_PASS'\]` 中

对于定时设置，参考链接：[python用schedule模块实现定时任务](https://blog.csdn.net/zd147896325/article/details/80003982)
