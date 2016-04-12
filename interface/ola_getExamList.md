
# 模考／真题列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /exam/getExamList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 courseId | 是 | 字符串 | 课程id，返回本级及其子集信息
 type | 是 | 字符串 | 1 模考 2 真题

###返回结果示例

```javascript
  {
  "message": "成功",
  "result": [
    {
      "cid": 1,
      "coverpoint": 23,
      "degree": 1,
      "name": "数学模考一",
      "target": 100
    },
    {
      "cid": 1,
      "coverpoint": 23,
      "degree": 1,
      "name": "数学模考二",
      "target": 100
    }
  ],
  "apicode": 10000
}
```
