# 获取视频观看历史记录列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getHistotyList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 videoId | 否 | 字符串 | 当前页最后一条的id
 pageSize | 否 | 字符串 | 每页条数
 
###返回结果示例

```javascript

{
  "message": "成功",
  "result": [
    {
      "userName": "晋成公",
      "userAvatar": "1452319877991.jpg",
      "videoId": 1,
      "videoName": "古典概率",
      "courseId": "1",
      "time": "2016-04-28 08:58:45"
    },
    {
      "userName": "赵建菲",
      "userAvatar": "",
      "videoId": 9,
      "videoName": "大纲词汇分析02",
      "courseId": "1",
      "time": "2016-04-28 08:59:48"
    }
  ],
  "apicode": 10000
}
