# 知识点列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getPointList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 courseId | 是 | 字符串 | 课程id
 userId | 否 | 字符串 | 用户id，用于判断各知识点用户是否已学
 
###返回结果示例

```javascript
{
  "message": "成功",
  "result": [
    {
      "id": 1,
      "name": "知识点1",
      "content": "知识点11",
      "type": null,
      "courseId": 7,
      "isLearn": "0"(1-已学，0-未学)
    },
    {
      "id": 2,
      "name": "知识点2",
      "content": "知识点22",
      "type": null,
      "courseId": 7,
      "isLearn": "1"
    }
  ],
  "apicode": 10000
}

```
