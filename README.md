## 设置

1. 先[申请测试号](https://mp.weixin.qq.com/debug/cgi-bin/sandbox?t=sandbox/login)
2. 关注测试号获取用户，也就是微信号(不是普通的微信号，在面板中查看)
3. 后台创建模板，格式可以按照我的，如果修改，请同步修改weixin.php中的代码; 标题随意

```
{{title.DATA}}
提醒时间:{{time.DATA}}
消息:{{msg.DATA}}
```

4. 把msg.php上传到自己的空间或者中，当然用我的也可以(http://域名/msg.php?title=标题(可选值)&time=提交时间&msg=推送内容);
5. weixin.php第61行修改

## 推送

http://xxx.xxx/weixin.php?msg=测试提交

---

项目地址https://github.com/Mxy123h/WeixinPush
