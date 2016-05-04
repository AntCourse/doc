# 知识型谱列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getStatisticsList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userid | 是 | 字符串 |
 type | 是 | 字符串 | 1 用于考点的课程列表 2 用户视频的课程列表

###返回结果示例

```javascript
{
  "message": "成功",
  "result": [
    {
      "id": 1,
      "name": "数学",
      "child": [
        {
          "address": "http://www.mykepu.com:8080/pic/course/math/1.png",
          "id": 7,
          "name": "算数",
          "pid": "1",
          "profile": "算数",
          "subAllNum": 6,
          "type": "1"
        },
        {
          "address": "http://www.mykepu.com:8080/pic/course/math/2.png",
          "id": 8,
          "name": "应用题",
          "pid": "1",
          "profile": "应用题",
          "subAllNum": 0,
          "type": "1"
        },
        {
          "address": "http://www.mykepu.com:8080/pic/course/math/3.png",
          "id": 36,
          "name": "整数",
          "pid": "1",
          "profile": "整数",
          "subAllNum": 0,
          "type": "1"
        },
        {
          "address": "http://www.mykepu.com:8080/pic/course/math/4.png",
          "id": 37,
          "name": "函数",
          "pid": "1",
          "profile": "函数",
          "subAllNum": 0,
          "type": "1"
        },
        {
          "address": "http://www.mykepu.com:8080/pic/course/math/5.png",
          "id": 38,
          "name": "方程与不等式",
          "pid": "1",
          "profile": "方程与不等式",
          "subAllNum": 0,
          "type": "1"
        },
        {
          "address": "http://www.mykepu.com:8080/pic/course/math/6.png",
          "id": 39,
          "name": "数列",
          "pid": "1",
          "profile": "数列",
          "subAllNum": 0,
          "type": "1"
        },
        {
          "address": "http://www.mykepu.com:8080/pic/course/math/7.png",
          "id": 40,
          "name": "平面几何",
          "pid": "1",
          "profile": "平面几何",
          "subAllNum": 0,
          "type": "1"
        },
        {
          "address": "http://www.mykepu.com:8080/pic/course/math/8.png",
          "id": 41,
          "name": "立体几何",
          "pid": "1",
          "profile": "立体几何",
          "subAllNum": 0,
          "type": "1"
        },
        {
          "address": "http://www.mykepu.com:8080/pic/course/math/9.png",
          "id": 42,
          "name": "解析几何",
          "pid": "1",
          "profile": "解析几何",
          "subAllNum": 0,
          "type": "1"
        },
        {
          "address": "http://www.mykepu.com:8080/pic/course/math/10.png",
          "id": 44,
          "name": "排列组合",
          "pid": "1",
          "profile": "排列组合",
          "subAllNum": 0,
          "type": "1"
        },
        {
          "address": "http://www.mykepu.com:8080/pic/course/math/11.png",
          "id": 45,
          "name": "概率",
          "pid": "1",
          "profile": "概率",
          "subAllNum": 0,
          "type": "1"
        }
      ]
    },
    {
      "id": 2,
      "name": "英语",
      "child": [
        {
          "address": "http://www.mykepu.com:8080/pic/course/english/1.png",
          "id": 10,
          "name": "核心词汇",
          "pid": "2",
          "profile": "核心词汇",
          "subAllNum": 0,
          "type": "1"
        },
        {
          "address": "http://www.mykepu.com:8080/pic/course/english/9.png",
          "id": 25,
          "name": "阅读",
          "pid": "2",
          "profile": "阅读",
          "subAllNum": 0,
          "type": "1"
        },
        {
          "address": "http://www.mykepu.com:8080/pic/course/english/2.png",
          "id": 28,
          "name": "长难句分析",
          "pid": "2",
          "profile": "长难句分析",
          "subAllNum": 0,
          "type": "1"
        }
      ]
    },
    {
      "id": 3,
      "name": "逻辑",
      "child": [
        {
          "address": "http://www.mykepu.com:8080/pic/course/logic/2.png",
          "id": 29,
          "name": "分析推理",
          "pid": "3",
          "profile": "分析推理",
          "subAllNum": 0,
          "type": "1"
        },
        {
          "address": "http://www.mykepu.com:8080/pic/course/logic/1.png",
          "id": 30,
          "name": "日常推理",
          "pid": "3",
          "profile": "日常推理",
          "subAllNum": 0,
          "type": "1"
        },
        {
          "address": "http://www.mykepu.com:8080/pic/course/logic/3.png",
          "id": 31,
          "name": "形式逻辑",
          "pid": "3",
          "profile": "形式逻辑",
          "subAllNum": 0,
          "type": "1"
        }
      ]
    },
    {
      "id": 4,
      "name": "写作",
      "child": [
        {
          "address": "http://www.mykepu.com:8080/pic/course/write/1.png",
          "id": 32,
          "name": "论证有效性分析",
          "pid": "4",
          "profile": "论证有效性分析",
          "subAllNum": 0,
          "type": "1"
        },
        {
          "address": "http://www.mykepu.com:8080/pic/course/write/2.png",
          "id": 33,
          "name": "论说文",
          "pid": "4",
          "profile": "论说文",
          "subAllNum": 0,
          "type": "1"
        }
      ]
    },
    {
      "id": 5,
      "name": "面试",
      "child": [
        {
          "address": "http://www.mykepu.com:8080/pic/course/interview/1.png",
          "id": 46,
          "name": "面试",
          "pid": "5",
          "profile": "面试",
          "subAllNum": 0,
          "type": "1"
        }
      ]
    }
  ],
  "apicode": 10000
}
