# 未读消息数
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /message/getUnreadCount

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userId | 是 | 字符串 | 
 
###返回结果示例

```javascript
{
    "message": "成功",
    "result": 1,  //未读数
    "apicode": 10000
}
