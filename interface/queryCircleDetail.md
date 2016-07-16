# 帖子详情
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /circle/queryCircleDetail

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 circleId | 是 | 字符串 | 
 
###返回结果示例

```javascript
{
    "message": "成功",
    "result": {
        "content": "员工太少！！！！领导真多！！！！！",
        "courseId": 0,
        "id": 442,
        "imageGids": "71d462f3-7e17-4afb-8cfd-67632577e32a",
        "location": "北京市海淀区",
        "praiseNumber": 2,
        "readNumber": 1,
        "title": "欧拉圈",
        "type": 2,
        "userId": 382,
        "videoId": 0,
        "userName": "小欧0992",
        "userAvatar": "1466843757205.jpg",
        "time": "2016-07-15 14:21:03",
        "commentList": [
            {
                "content": "哈哈",
                "id": 28,
                "location": "北京市,海淀区",
                "postId": 442,
                "praiseNumber": 0,
                "toUserId": "",
                "type": 2,
                "userId": 381,
                "userName": "小欧4738",
                "userAvatar": "9afc50f4-7a7c-4d21-ac49-d6fee973d575",
                "time": "2016-07-16 07:24:31"
            },
            {
                "content": "哈哈",
                "id": 27,
                "location": "北京市,海淀区",
                "postId": 442,
                "praiseNumber": 0,
                "toUserId": "",
                "type": 2,
                "userId": 382,
                "userName": "小欧0992",
                "userAvatar": "1466843757205.jpg",
                "time": "2016-07-15 15:09:41"
            }
        ]
    },
    "apicode": 10000
}
