# 注册

入参：

```
username    用户名，8-40位，只允许使用数字、大小写英文字母和下划线
password    密码，8-40位，只允许使用数字、大小写英文字母和下划线
email   邮箱
```

出参：（成功时，失败都是统一的格式）

```
data: {
    msg:''  // 成功时发送注册成功信息
    redirecturl:'',     // 注册成功时，重定向到某个url
}
```