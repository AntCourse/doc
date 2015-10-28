# 课程列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getCourList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 pid | 否 | 字符串 | 父级id，返回父级及其子集信息
 type | 否 | 字符串 | 预留参数

###返回结果示例

```javascript
  {
  "message": "成功",
  "result": {
    "courId": 2,
    "courName": "数学",
    "courProfile": "数学",
    "child": [
      {
        "address": "",
        "id": 5,
        "name": "数学课程1",
        "pid": "2",
        "profile": "",
        "type": "1"
      },
      {
        "address": "",
        "id": 6,
        "name": "数学课程2",
        "pid": "2",
        "profile": "",
        "type": "1"
      }
    ]
  },
  "apicode": 10000
}
```
