# 首页列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /home/getHomeList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 
###返回结果示例

```javascript
{
    "message": "成功",
    "result": {
        "bannerList": [
            {
                "id": 2,
                "name": "",
                "objectId": 0,
                "pic": "",
                "type": 2,
                "url": ""
            },
            {
                "id": 1,
                "name": "",
                "objectId": 0,
                "pic": "",
                "type": 1,
                "url": ""
            }
        ],
        "questionList": [
            {
                "id": 5,
                "title": "56",
                "content": "sdf",
                "number": 2,
                "time": ""
            },
            {
                "id": 4,
                "content": "56",
                "number": 1,
                "time": ""
            }
        ],
        "goodsList": [
            {
                "attentionnum": 100,
                "detail": "对考试内容作全面细致的讲解,温故知新。",
                "id": 1,
                "image": "http://banner.ufile.ucloud.com.cn/logo_mx.png",
                "leanstage": "5月17日-12月31日",
                "name": "2017年数学周末班基础课程",
                "org": "幂学教育版权所有",
                "paynum": 939,
                "price": 1200,
                "status": 0,
                "suitto": "教材版本：《联考综合能力数学高分指南》",
                "totaltime": 2200,
                "type": "1",
                "url": "http://commodity.ufile.ucloud.com.cn/math.jpg",
                "videonum": 27
            },
            {
                "attentionnum": 100,
                "detail": "掌握主要复习要点，确保能够达到考试优良水平",
                "id": 2,
                "image": "http://banner.ufile.ucloud.com.cn/logo_mx.png",
                "leanstage": "5月17日-12月31日",
                "name": "2016年数学真题密训班课程",
                "org": "幂学教育版权所有",
                "paynum": 323,
                "price": 1000,
                "status": 0,
                "suitto": "教材版本：《数学历年真题名家详解》",
                "totaltime": 1980,
                "type": "1",
                "url": "http://commodity.ufile.ucloud.com.cn/math.jpg",
                "videonum": 24
            }
        ]
    },
    "apicode": 10000
}
