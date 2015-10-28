# 获取推荐视频
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getRecommendVideo

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 subjectIds | 是 | 字符串 | 错误试题id，多个用逗号分隔
 
###返回结果示例

```javascript
{
  "message": "成功",
  "result": {
    "id": 1,
    "name": "分数与小数",
    "content": null,
    "address": "http://www.mykepu.com:8080/video/math/1/1",
    "playCount": 1,
    "timeSpan": 10,
    "weight": "10"
  },
  "apicode": 10000
}

```
