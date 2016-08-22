
# 学生所在群列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /homework/getUserGroupList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userId | 是 | 字符串 | 
 
###返回结果示例

```javascript
{
    "message": "成功",
    "result": [
        {
            "createUser": 0,
            "id": 1,
            "avatar": "",
            "name": "欧拉学习群",
            "time": "2016-08-02 17:48"
        }
    ],
    "apicode": 10000
}
