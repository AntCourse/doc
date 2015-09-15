

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
			"id": 102,
			"name": "丢丢大哲哲",
			"sex": "9",
			"age": 22,
			"phone": "15311450124",
			"passwd": "echo1",
			"email": null,
			"birthday": 1450195200000,
			"qq": "747819855",
			"regtime": 1438685526000,
			"logintime": 1438745680000,
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
	},
	"apicode": 10000
}



```
