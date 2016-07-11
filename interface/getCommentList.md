# 评论列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /comment/getCommentList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 postId | 是 | 字符串 | couserId或circle中的帖子Id
 type | 是 | 字符串 | 1 postId为课程 2 postId 为帖子
 
###返回结果示例

```javascript
{
    "message": "成功",
    "result": [
        {
            "commentId": 1,
            "userName": "小欧4738",
            "userAvatar": "664c3a2d-8ddd-4acc-a0c3-5382f625cbb5",
            "toUserName": "小欧0992",
            "content": "回复",
            "praiseNumber": 10,
            "time": "2016-07-11 16:02:51"
        }
    ],
    "apicode": 10000
}
