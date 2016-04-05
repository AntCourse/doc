
# 课程列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getCourList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 pid | 是 | 字符串 | 课程id，返回本级及其子集信息
 type | 是 | 字符串 | 1 用于考点的课程列表 2 用户视频的课程列表

###返回结果示例

```javascript
  {
	"message": "成功",
	"result": {
		"courId": 1,
		"name": "数学",
		"profile": "数学",
		"child": [{
			"courId": 7,
			"name": "算数",
			"pid": "1",
			"profile": "算数",
			"type": "1",
			"address": "http://www.mykepu.com:8080/pic/course/math/1.png",
			"subList": [{
				"address": "",
				"id": 53,
				"name": "算数1-1",
				"pid": "7",
				"playcount": 0,
				"profile": "算数1-1",
				"type": "1"
			}]
		}, {
			"courId": 8,
			"name": "应用题",
			"pid": "1",
			"profile": "应用题",
			"type": "1",
			"address": "http://www.mykepu.com:8080/pic/course/math/2.png",
			"subList": []
		}, {
			"courId": 36,
			"name": "整数",
			"pid": "1",
			"profile": "整数",
			"type": "1",
			"address": "http://www.mykepu.com:8080/pic/course/math/3.png",
			"subList": []
		}, {
			"courId": 37,
			"name": "函数",
			"pid": "1",
			"profile": "函数",
			"type": "1",
			"address": "http://www.mykepu.com:8080/pic/course/math/4.png",
			"subList": []
		}, {
			"courId": 38,
			"name": "方程与不等式",
			"pid": "1",
			"profile": "方程与不等式",
			"type": "1",
			"address": "http://www.mykepu.com:8080/pic/course/math/5.png",
			"subList": []
		}, {
			"courId": 39,
			"name": "数列",
			"pid": "1",
			"profile": "数列",
			"type": "1",
			"address": "http://www.mykepu.com:8080/pic/course/math/6.png",
			"subList": []
		}, {
			"courId": 40,
			"name": "平面几何",
			"pid": "1",
			"profile": "平面几何",
			"type": "1",
			"address": "http://www.mykepu.com:8080/pic/course/math/7.png",
			"subList": []
		}, {
			"courId": 41,
			"name": "立体几何",
			"pid": "1",
			"profile": "立体几何",
			"type": "1",
			"address": "http://www.mykepu.com:8080/pic/course/math/8.png",
			"subList": []
		}, {
			"courId": 42,
			"name": "解析几何",
			"pid": "1",
			"profile": "解析几何",
			"type": "1",
			"address": "http://www.mykepu.com:8080/pic/course/math/9.png",
			"subList": []
		}, {
			"courId": 44,
			"name": "排列组合",
			"pid": "1",
			"profile": "排列组合",
			"type": "1",
			"address": "http://www.mykepu.com:8080/pic/course/math/10.png",
			"subList": []
		}, {
			"courId": 45,
			"name": "概率",
			"pid": "1",
			"profile": "概率",
			"type": "1",
			"address": "http://www.mykepu.com:8080/pic/course/math/11.png",
			"subList": []
		}]
	},
	"apicode": 10000
}
```
