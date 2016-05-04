# 用户收藏视频列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /collection/getCollectionByUserId

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userid | 是 | 字符串 |

###返回结果示例

```javascript
{
  "message": "成功",
  "result": [
    {
      "videoId": 9,
      "videoName": "大纲词汇分析02",
      "videoPic": "videoPic",
      "videoUrl": "http://olamath.ufile.ucloud.com.cn/2016yingyong/01_jichu_01.mp4",
      "courseId": 1,
      "coursePIc": ""
    },
    {
      "videoId": 9,
      "videoName": "大纲词汇分析02",
      "videoPic": "videoPic",
      "videoUrl": "http://olamath.ufile.ucloud.com.cn/2016yingyong/01_jichu_01.mp4",
      "courseId": 2,
      "coursePIc": ""
    }
  ],
  "apicode": 10000
}
