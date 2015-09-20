

# 根据id查询用户的信息
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /user/queryUser

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 id | 是 | 字符串 | 用户id 必填

###返回结果示例

```javascript
  {
    "message": "成功",
    "data": {
        "message": "成功",
        "data": {
            "id": 107,
            "name": null,
            "sex": null,
            "age": 0,
            "phone": "18911345831",
            "passwd": "123123",
            "email": null,
            "birthday": null,
            "qq": null,
            "regtime": 1442749553000,
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
            "userSession": "3AE499374352A801871EB3B53E721EFB"
        },
        "apicode": 10000
    },
    "apicode": 10000
}



```
