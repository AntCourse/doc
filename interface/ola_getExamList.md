
# 模考／真题列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /exam/getExamList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 courseId | 是 | 字符串 | 课程id
 type | 是 | 字符串 | 1 模考 2 真题

###返回结果示例

```javascript

{
  "message": "成功",
  "result": [
    {
      "id": 1,
      "cid": 1,
      "name": "2016数学真题",
      "target": 100,
      "degree": 1,
      "coverpoint": 10,
      "type": "1"
    },
    {
      "id": 2,
      "cid": 1,
      "name": "2015数学真题",
      "target": 88,
      "degree": 1,
      "coverpoint": 23,
      "type": "1"
    },
    {
      "id": 3,
      "cid": 1,
      "name": "2014数学真题",
      "target": 79,
      "degree": 1,
      "coverpoint": 1,
      "type": "1"
    },
    {
      "id": 4,
      "cid": 1,
      "name": "2013数学真题",
      "target": 98,
      "degree": 1,
      "coverpoint": 2,
      "type": "1"
    },
    {
      "id": 5,
      "cid": 1,
      "name": "2012数学真题",
      "target": 95,
      "degree": 1,
      "coverpoint": 3,
      "type": "1"
    },
    {
      "id": 6,
      "cid": 1,
      "name": "2011数学真题",
      "target": 99,
      "degree": 1,
      "coverpoint": 4,
      "type": "1"
    },
    {
      "id": 7,
      "cid": 1,
      "name": "2010数学真题",
      "target": 100,
      "degree": 1,
      "coverpoint": 1,
      "type": "1"
    },
    {
      "id": 8,
      "cid": 1,
      "name": "2009数学真题",
      "target": 100,
      "degree": 1,
      "coverpoint": 1,
      "type": "1"
    }
  ],
  "apicode": 10000
}

```
