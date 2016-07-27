# 直播列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /broadcast/getBroadcastList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 broadcastId | 否 | 字符串 | 当前页最后一条的id
 pageSize | 否 | 字符串 | 每页条数
 
###返回结果示例

```javascript
{
    "message": "成功",
    "result": [
        {
            "broadcastId": 2,
            "name": "直播2",
            "userName": "小欧0992",
            "userAvatar": "1466843757205.jpg",
            "time": "2016-09-01 11:30:00"
        },
        {
            "broadcastId": 1,
            "name": "直播1",
            "userName": "小欧4738",
            "userAvatar": "664c3a2d-8ddd-4acc-a0c3-5382f625cbb5",
            "time": "2015-08-05 10:00:00"
        }
    ],
    "apicode": 10000
}
