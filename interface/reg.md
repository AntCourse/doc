
# 用户注册
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /user/reg

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 phone | 是 | 字符串 | 手机号
 passwd | 是 | 字符串 | 密码
 code   | 是 |字符串  手机验证码

###返回结果示例

```javascript
 {
    "message": "成功",
    "data": {
        "id": 115,
        "name": null,
        "sex": null,
        "age": 0,
        "phone": "18911345832",
        "passwd": "541387e4ebdadf7c",
        "email": null,
        "birthday": null,
        "qq": null,
        "regtime": 1445581309000,
        "logintime": 1445581344309,
        "avator": null,
        "sign": null,
        "level": null,
        "honor": null,
        "learntime": null,
        "status": null,
        "examtype": null,
        "yzm": null,
        "isActive": 1,
        "realName": null,
        "infoPerfectLev": null
    },
    "apicode": 10000
}



```
