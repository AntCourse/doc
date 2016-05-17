# 获取课程知识点对应的视频
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getVideoByPoi

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 pointId | 是 | 字符串 | 课程知识点id
 userId | 否 | 字符串 | userId
 
###返回结果示例

```javascript
{
  "message": "成功",
  "result": {
    "pointId": "70",
    "isCollect": "0",
    "videoList": [
      {
        "address": "http://olamath.ufile.ucloud.com.cn/2016chuanjiang/07_jihe.mp4",
        "content": "",
        "id": 107,
        "isBanner": 0,
        "name": "课时1：几何考点预测及拿分策略Ⅰ",
        "orgname": "",
        "pic": "",
        "playCount": 9,
        "timeSpan": "0:54:44",
        "tname": "",
        "weight": "",
        "isfree":0   // 需开通会员
      },
      {
        "address": "http://olamath.ufile.ucloud.com.cn/2016chuanjiang/08_jihe.mp4",
        "content": "",
        "id": 108,
        "isBanner": 0,
        "name": "课时2：几何考点预测及拿分策略Ⅱ",
        "orgname": "",
        "pic": "",
        "playCount": 5,
        "timeSpan": "0:30:02",
        "tname": "",
        "weight": "",
        "isfree":1  //可观看
      }
    ]
  },
  "apicode": 10000
}

```
