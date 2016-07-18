# 消息列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /message/getMessageList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userId | 是 | 字符串 | 
 messageId | 否 | 字符串 | 当前页最后一条的id
 pageSize | 否 | 字符串 | 每页条数
 
###返回结果示例

```javascript
{
    "message": "成功",
    "result": [
        {
            "content": "消息1",
            "id": 1,
            "otherId": 0,
            "status": 0,
            "title": "消息",
            "type": 1,
            "time": "2016-07-18 11:00:52",
            "imageUrl": "1466843757205.jpg"
        },
        {
            "content": "消息3",
            "id": 3,
            "otherId": 188,
            "status": 1,
            "title": "消息",
            "type": 3,
            "time": "2016-07-15 11:01:24",
            "imageUrl": "http://banner.ufile.ucloud.com.cn/banner4.jpg"
        },
        {
            "content": "消息2",
            "id": 2,
            "otherId": 54,
            "status": 1,
            "title": "消息",
            "type": 2,
            "time": "2016-07-12 11:01:09",
            "imageUrl": "http://math.ufile.ucloud.com.cn/basicmath1.jpg"
        }
    ],
    "apicode": 10000
}
