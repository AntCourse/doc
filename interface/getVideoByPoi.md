# 获取知识点对应的视频
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getVideoByPoi

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 pointId | 是 | 字符串 | 知识点id
 
###返回结果示例

```javascript
{
  "message": "成功",
  "result": {
    "id": 1,
    "name": "视频1",
    "content": null,
    "address": "www.baidu.com",
    "playCount": 0,
    "timeSpan": 10,
    "weight": "10"
  },
  "pointId": "1",
  "apicode": 10000
}

```
