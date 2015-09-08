
# 获取视频对应的测试题
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getSubList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 videoId | 是 | 字符串 | 视频Id（如 1）

###返回结果示例

```javascript

{
    "message": "成功",
    "result": [
        {
            "id": 7,
            "question": "题目7",
            "type": null,
            "degree": null,
            "hint": null,
            "allcount": 0,
            "rightcount": 0,
            "avgtime": 0,
            "optionList": []
        },
        {
            "id": 2,
            "question": "题目2",
            "type": null,
            "degree": null,
            "hint": null,
            "allcount": 0,
            "rightcount": 0,
            "avgtime": 0,
            "optionList": [
                {
                    "id": 5,
                    "sid": null,
                    "type": null,
                    "content": "选项12",
                    "isanswer": null
                },
                {
                    "id": 6,
                    "sid": null,
                    "type": null,
                    "content": "选项2",
                    "isanswer": null
                },
                {
                    "id": 7,
                    "sid": null,
                    "type": null,
                    "content": "选项3",
                    "isanswer": null
                },
                {
                    "id": 8,
                    "sid": null,
                    "type": null,
                    "content": "选项4",
                    "isanswer": null
                }
            ]
        },
        {
            "id": 7,
            "question": "题目7",
            "type": null,
            "degree": null,
            "hint": null,
            "allcount": 0,
            "rightcount": 0,
            "avgtime": 0,
            "optionList": []
        },
        {
            "id": 6,
            "question": "题目6",
            "type": null,
            "degree": null,
            "hint": null,
            "allcount": 0,
            "rightcount": 0,
            "avgtime": 0,
            "optionList": []
        },
        {
            "id": 5,
            "question": "题目5",
            "type": null,
            "degree": null,
            "hint": null,
            "allcount": 0,
            "rightcount": 0,
            "avgtime": 0,
            "optionList": []
        }
    ],
    "apicode": 10000
}
