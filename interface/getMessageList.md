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
            "id": 3,
            "content": "消息3",
            "otherId": 2,
            "type": 3,
            "status": 0,
            "createTime": ""
        },
        {
            "id": 2,
            "content": "消息2",
            "otherId": 1,
            "type": 2,
            "status": 0,
            "createTime": ""
        }
    ],
    "apicode": 10000
}
