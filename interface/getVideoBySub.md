# 获取测试题的相关视频
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getVideoBySub

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 subjectId | 是 | 字符串 | 试题id
 
###返回结果示例

```javascript
{
  "message": "成功",
  "result": [
    {
      "id": 1,
      "name": "视频1",
      "content": null,
      "address": "www.baidu.com",
      "playCount": 1,
      "timeSpan": 10,
      "weight": null
    },
    {
      "id": 2,
      "name": "视频2",
      "content": null,
      "address": "www.baidu.com",
      "playCount": 0,
      "timeSpan": 20,
      "weight": null
    },
    {
      "id": 1,
      "name": "视频1",
      "content": null,
      "address": "www.baidu.com",
      "playCount": 1,
      "timeSpan": 10,
      "weight": null
    },
    {
      "id": 3,
      "name": "视频3",
      "content": null,
      "address": "www.baidu.com",
      "playCount": 1,
      "timeSpan": 30,
      "weight": null
    },
    {
      "id": 1,
      "name": "视频1",
      "content": null,
      "address": "www.baidu.com",
      "playCount": 1,
      "timeSpan": 10,
      "weight": null
    }
  ],
  "apicode": 10000
}

```
