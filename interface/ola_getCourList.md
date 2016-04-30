
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
        "id": 7,
        "name": "算数",
        "pid": "1",
        "profile": "算数",
        "subAllNum": 6,
        "type": "1",
        "child": [
          {
            "address": "",
            "id": 53,
            "name": "算数1-1",
            "pid": "7",
            "profile": "算数1-1",
            "subAllNum": 6,
            "type": "1",
            "subNum": 0
          }
        ],
        "subNum": 0
      },
      {
        "address": "http://www.mykepu.com:8080/pic/course/math/2.png",
        "id": 8,
        "name": "应用题",
        "pid": "1",
        "profile": "应用题",
        "subAllNum": 0,
        "type": "1",
        "subNum": 0
      },
      {
        "address": "http://www.mykepu.com:8080/pic/course/math/3.png",
        "id": 36,
        "name": "整数",
        "pid": "1",
        "profile": "整数",
        "subAllNum": 0,
        "type": "1",
        "subNum": 0
      },
      {
        "address": "http://www.mykepu.com:8080/pic/course/math/4.png",
        "id": 37,
        "name": "函数",
        "pid": "1",
        "profile": "函数",
        "subAllNum": 0,
        "type": "1",
        "subNum": 0
      },
      {
        "address": "http://www.mykepu.com:8080/pic/course/math/5.png",
        "id": 38,
        "name": "方程与不等式",
        "pid": "1",
        "profile": "方程与不等式",
        "subAllNum": 0,
        "type": "1",
        "subNum": 0
      },
      {
        "address": "http://www.mykepu.com:8080/pic/course/math/6.png",
        "id": 39,
        "name": "数列",
        "pid": "1",
        "profile": "数列",
        "subAllNum": 0,
        "type": "1",
        "subNum": 0
      },
      {
        "address": "http://www.mykepu.com:8080/pic/course/math/7.png",
        "id": 40,
        "name": "平面几何",
        "pid": "1",
        "profile": "平面几何",
        "subAllNum": 0,
        "type": "1",
        "subNum": 0
      },
      {
        "address": "http://www.mykepu.com:8080/pic/course/math/8.png",
        "id": 41,
        "name": "立体几何",
        "pid": "1",
        "profile": "立体几何",
        "subAllNum": 0,
        "type": "1",
        "subNum": 0
      },
      {
        "address": "http://www.mykepu.com:8080/pic/course/math/9.png",
        "id": 42,
        "name": "解析几何",
        "pid": "1",
        "profile": "解析几何",
        "subAllNum": 0,
        "type": "1",
        "subNum": 0
      },
      {
        "address": "http://www.mykepu.com:8080/pic/course/math/10.png",
        "id": 44,
        "name": "排列组合",
        "pid": "1",
        "profile": "排列组合",
        "subAllNum": 0,
        "type": "1",
        "subNum": 0
      },
      {
        "address": "http://www.mykepu.com:8080/pic/course/math/11.png",
        "id": 45,
        "name": "概率",
        "pid": "1",
        "profile": "概率",
        "subAllNum": 0,
        "type": "1",
        "subNum": 0
      }
    ],
    "subNum": 0
  },
  "apicode": 10000
}
