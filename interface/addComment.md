# 添加评论
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /comment/addComment

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userId | 是 | 字符串 | 
 postId | 是 | 字符串 |  课程Id 或 帖子Id
 toUserId | 否 | 字符串 | 
 content | 否 | 字符串 | 
 location | 否 | 字符串 | 
 type | 否 | 字符串 |   1 课程评论 2 帖子评论
 
###返回结果示例

```javascript
{
  "message": "成功",
  "apicode": 10000
}
