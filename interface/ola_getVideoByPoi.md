# 获取课程知识点对应的视频
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getVideoByPoi

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 pointId | 是 | 字符串 | 课程知识点id
 
###返回结果示例

```javascript
{
  "message": "成功",
  "result": [
    {
      "id": 10,
      "name": "第一学时：大纲词汇分析03",
      "content": "大纲词汇分析03",
      "address": "http://orthoday.ufile.ucloud.com.cn/test/genius_plan.mp4",
      "playCount": 105,
      "timeSpan": 0,
      "weight": null,
      "orgname": "幂学",
      "tname": "何敬",
      "isBanner": 0,
      "pic": null
    },
    {
      "id": 11,
      "name": "第二学时：大纲词汇分析04",
      "content": "大纲词汇分析04",
      "address": "http://orthoday.ufile.ucloud.com.cn/motion/sc01_1080p.flv",
      "playCount": 117,
      "timeSpan": 0,
      "weight": null,
      "orgname": "幂学",
      "tname": "何敬",
      "isBanner": 0,
      "pic": null
    },
    {
      "id": 12,
      "name": "第三学时：大纲词汇分析05",
      "content": "大纲词汇分析05",
      "address": "http://orthoday.ufile.ucloud.com.cn/test/genius_plan.mp4",
      "playCount": 92,
      "timeSpan": 0,
      "weight": null,
      "orgname": "幂学",
      "tname": "何敬",
      "isBanner": 0,
      "pic": null
    }
  ],
  "pointId": "54",
  "apicode": 10000
}

```
