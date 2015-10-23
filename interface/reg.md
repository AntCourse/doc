
# 用户注册
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /user/reg

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 phone和email | 是 | 字符串 | 其中一个必填
 passwd | 是 | 字符串 | 密码
 code   | 是 |字符串  手机验证码

###返回结果示例

```javascript
 {
    "message": "成功",
    "user": {
        "id": 108,
        "name": null,
        "sex": null,
        "age": 0,
        "phone": "18911345831",
        "passwd": "123123",
        "email": null,
        "birthday": null,
        "qq": null,
        "regtime": 1442751441694,
        "logintime": null,
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
        "infoPerfectLev": null,
        "userSession": "9B35F6A68C2C615BD5FEE720DFF52C2B"
    },
    "apicode": 10000
}



```
