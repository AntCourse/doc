# 提交测试题的答案
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/checkAnswer

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 answer | 是 | 字符串 | 答案，json格式[{"no":"序号","optId":"选项id","timeSpan":"秒"},{},...]
 
###返回结果示例

```javascript
{
  "message": "成功",
  "result": [
    {
      "no": "1",
      "isRight": "1",
      "avgAcc": "100%",
      "avgTime": 10,
      "points": [
        {
          "content": "知识点11",
          "id": 1
        },
        {
          "content": "知识点22",
          "id": 2
        },
        {
          "content": "知识点33",
          "id": 3
        },
        {
          "content": "知识点11",
          "id": 1
        },
        {
          "content": "知识点11",
          "id": 1
        }
      ]
    }
  ],
  "apicode": 10000
}

```
