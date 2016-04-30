
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
    "address": "",
    "id": 1,
    "name": "数学",
    "pid": "0",
    "profile": "数学",
    "subAllNum": 6,
    "type": "1",
    "child": [
      {
        "address": "http://www.mykepu.com:8080/pic/course/math/1.png",
        "id": 47,
        "name": "基础课程",
        "pid": "1",
        "profile": "",
        "subAllNum": 0,
        "type": "2",
        "child": [
          {
            "address": "http://www.mykepu.com:8080/pic/course/math/1.png",
            "id": 54,
            "name": "数学1-1",
            "pid": "47",
            "profile": "数学1-1",
            "subAllNum": 0,
            "type": "2",
            "subNum": 0
          },
          {
            "address": "http://www.mykepu.com:8080/pic/course/math/2.png",
            "id": 55,
            "name": "数学1-2",
            "pid": "47",
            "profile": "",
            "subAllNum": 0,
            "type": "2",
            "subNum": 0
          }
        ],
        "subNum": 0
      },
      {
        "address": "http://www.mykepu.com:8080/pic/course/math/2.png",
        "id": 51,
        "name": "高级课程",
        "pid": "1",
        "profile": "",
        "subAllNum": 0,
        "type": "2",
        "child": [
          {
            "address": "http://www.mykepu.com:8080/pic/course/math/3.png",
            "id": 56,
            "name": "数学2-1",
            "pid": "51",
            "profile": "",
            "subAllNum": 0,
            "type": "2",
            "subNum": 0
          }
        ],
        "subNum": 0
      },
      {
        "address": "http://www.mykepu.com:8080/pic/course/math/3.png",
        "id": 52,
        "name": "付费课程",
        "pid": "1",
        "profile": "",
        "subAllNum": 0,
        "type": "2",
        "child": [
          {
            "address": "http://www.mykepu.com:8080/pic/course/math/4.png",
            "id": 57,
            "name": "数学3-1",
            "pid": "52",
            "profile": "",
            "subAllNum": 0,
            "type": "2",
            "subNum": 0
          }
        ],
        "subNum": 0
      }
    ],
    "subNum": 0
  },
  "apicode": 10000
}
