# 提交测试题的答案
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/checkAnswer

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userId | 否 | 字符串 | 用户id，用于记录做题日志
 answer | 是 | 字符串 | 答案，json格式[{"no":"序号","optId":"选项id","timeSpan":"秒"},{},...]
 type   | 是 | 字符串 | 试题类型，1 考点 2 题库（模考真题）
 
###返回结果示例

```javascript
{
	"message": "成功",
	"result": [{
		"no": "1",
		"isRight": "1",
		"avgAcc": "46%"
	}, {
		"no": "2",
		"isRight": "1",
		"avgAcc": "47%"
	}, {
		"no": "3",
		"isRight": "1",
		"avgAcc": "48%"
	}],
	"apicode": 10000
}

```
