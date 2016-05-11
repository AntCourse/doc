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
      "videoId": 1,
      "videoName": "课时1：实数的概念",
      "videoUrl": "http://olamath.ufile.ucloud.com.cn/2016suanshu/01_gainian_01.mp4",
      "courseId": 54,
      "coursePic": "http://math.ufile.ucloud.com.cn/basicmath1.jpg",
      "timeStamp": "2:16:05",
      "subAllNum": 0
    }
  ],
  "apicode": 10000
}
