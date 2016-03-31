
# 课程列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getCourList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 pid | 是 | 字符串 | 课程id，返回本级及其子集信息
 type | 是 | 字符串 | 1 用于考点的课程列表 2 用户视频的课程列表

###返回结果示例

```javascript
  {
  "message": "成功",
  "result": {
    "courId": 1,
    "name": "英语",
    "profile": "英语",
    "child": [
      {
        "courId": 10,
        "name": "核心词汇",
        "pid": "1",
        "profile": "核心词汇",
        "type": "1",
        "address": "http://www.mykepu.com:8080/pic/course/english/1.png",
        "subList": [
          {
            "accuracy": 0,
            "content": "晨星成长计划",
            "courseId": 10,
            "id": 1,
            "isLearn": "",
            "name": "晨星成长计划",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "大纲词汇分析01",
            "courseId": 10,
            "id": 8,
            "isLearn": "",
            "name": "大纲词汇分析01",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "大纲词汇分析02",
            "courseId": 10,
            "id": 9,
            "isLearn": "",
            "name": "大纲词汇分析02",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "大纲词汇分析03",
            "courseId": 10,
            "id": 10,
            "isLearn": "",
            "name": "大纲词汇分析03",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "大纲词汇分析04",
            "courseId": 10,
            "id": 11,
            "isLearn": "",
            "name": "大纲词汇分析04",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "大纲词汇分析05",
            "courseId": 10,
            "id": 12,
            "isLearn": "",
            "name": "大纲词汇分析05",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "大纲词汇分析06",
            "courseId": 10,
            "id": 13,
            "isLearn": "",
            "name": "大纲词汇分析06",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "大纲词汇分析07",
            "courseId": 10,
            "id": 14,
            "isLearn": "",
            "name": "大纲词汇分析07",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "大纲词汇分析08",
            "courseId": 10,
            "id": 15,
            "isLearn": "",
            "name": "大纲词汇分析08",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "大纲词汇分析09",
            "courseId": 10,
            "id": 16,
            "isLearn": "",
            "name": "大纲词汇分析09",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "大纲词汇分析10",
            "courseId": 10,
            "id": 17,
            "isLearn": "",
            "name": "大纲词汇分析10",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "大纲词汇分析11",
            "courseId": 10,
            "id": 18,
            "isLearn": "",
            "name": "大纲词汇分析11",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "大纲词汇分析12",
            "courseId": 10,
            "id": 19,
            "isLearn": "",
            "name": "大纲词汇分析12",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "大纲词汇分析13",
            "courseId": 10,
            "id": 20,
            "isLearn": "",
            "name": "大纲词汇分析13",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "大纲词汇分析14",
            "courseId": 10,
            "id": 21,
            "isLearn": "",
            "name": "大纲词汇分析14",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "大纲词汇分析15",
            "courseId": 10,
            "id": 22,
            "isLearn": "",
            "name": "大纲词汇分析15",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "大纲词汇分析16",
            "courseId": 10,
            "id": 23,
            "isLearn": "",
            "name": "大纲词汇分析16",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "大纲词汇分析17",
            "courseId": 10,
            "id": 24,
            "isLearn": "",
            "name": "大纲词汇分析17",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          }
        ]
      },
      {
        "courId": 25,
        "name": "阅读",
        "pid": "1",
        "profile": "阅读",
        "type": "1",
        "address": "http://www.mykepu.com:8080/pic/course/english/9.png",
        "subList": []
      },
      {
        "courId": 28,
        "name": "长难句分析",
        "pid": "1",
        "profile": "长难句分析",
        "type": "1",
        "address": "http://www.mykepu.com:8080/pic/course/english/2.png",
        "subList": [
          {
            "accuracy": 0,
            "content": "长难句分析01",
            "courseId": 28,
            "id": 25,
            "isLearn": "",
            "name": "长难句分析01",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "长难句分析02",
            "courseId": 28,
            "id": 26,
            "isLearn": "",
            "name": "长难句分析02",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "长难句分析03",
            "courseId": 28,
            "id": 27,
            "isLearn": "",
            "name": "长难句分析03",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "长难句分析04",
            "courseId": 28,
            "id": 28,
            "isLearn": "",
            "name": "长难句分析04",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "长难句分析05",
            "courseId": 28,
            "id": 29,
            "isLearn": "",
            "name": "长难句分析05",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "长难句分析06",
            "courseId": 28,
            "id": 30,
            "isLearn": "",
            "name": "长难句分析06",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "长难句分析07",
            "courseId": 28,
            "id": 31,
            "isLearn": "",
            "name": "长难句分析07",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "长难句分析08",
            "courseId": 28,
            "id": 32,
            "isLearn": "",
            "name": "长难句分析08",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "长难句分析09",
            "courseId": 28,
            "id": 33,
            "isLearn": "",
            "name": "长难句分析09",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "长难句分析10",
            "courseId": 28,
            "id": 34,
            "isLearn": "",
            "name": "长难句分析10",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "长难句分析11",
            "courseId": 28,
            "id": 35,
            "isLearn": "",
            "name": "长难句分析11",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "长难句分析12",
            "courseId": 28,
            "id": 36,
            "isLearn": "",
            "name": "长难句分析12",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          },
          {
            "accuracy": 0,
            "content": "长难句分析13",
            "courseId": 28,
            "id": 37,
            "isLearn": "",
            "name": "长难句分析13",
            "subNum": 0,
            "type": "",
            "videoAddr": "",
            "videoId": ""
          }
        ]
      }
    ]
  },
  "apicode": 10000
}
```
