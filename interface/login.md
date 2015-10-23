
# 用户登录
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /user/login

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 phone | 是 | 字符串 | 手机号
 passwd | 是 | 字符串 | 密码

###返回结果示例

```javascript
  {
    "message": "成功",
    "data": {
        "id": 0,
        "name": null,
        "sex": null,
        "age": 0,
        "phone": "15311450124",
        "passwd": "123123",
        "email": null,
        "birthday": null,
        "qq": null,
        "regtime": null,
        "logintime": 1445257362174,
        "avator": null,
        "sign": null,
        "level": null,
        "honor": null,
        "learntime": null,
        "status": null,
        "examtype": null,
        "yzm": null,
        "isActive": 0,
        "realName": null,
        "infoPerfectLev": null
    },
    "apicode": 10000
}



```
