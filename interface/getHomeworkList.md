# 作业列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /homework/getHomeworkList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userId | 是 | 字符串 | 
 homeworkId | 否 | 字符串 | 当前页最后一条的id
 pageSize | 否 | 字符串 | 每页条数
 
###返回结果示例

```javascript
{
    "message": "成功",
    "result": [
        {
            "id": 1,
            "name": "每周一练",
            "count": "10",
            "userName": "小欧4738",
            "avatar": "664c3a2d-8ddd-4acc-a0c3-5382f625cbb5",
            "groupId": "1",
            "groupName": "欧拉学习群",
            "time": "2016-08-02 17:50"
        }
    ],
    "apicode": 10000
}
