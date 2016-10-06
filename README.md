# Zabbix3-LineNotify
Line Notify Notification from Zabbix 3.x

## Env
- Zabbix 3.0
- CentOS Linux release 7.2.1511 (Core)

## Install Steps

```
[Zabbix-Server]$ cd /usr/lib/zabbix/alertscripts    # AlertScriptsPath
[Zabbix-Server]$ git clone https://github.com/kenzo0107/zabbix3-linenotify
[Zabbix-Server]$ mv zabbix3-slack/line_notify.sh .
[Zabbix-Server]$ rm -r zabbix3-linenotify
[Zabbix-Server]$ chmod 755 line_notify.sh
```

### Media Types Setting
![Imgur](http://i.imgur.com/mE5dEXI.png)

### Users > Media
[Imgur](http://i.imgur.com/ovDFnTq.png)
