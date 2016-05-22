
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
 userid | 否 | 字符串 

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
    "totalTime": "",
    "type": "1",
    "child": [
      {
        "address": "http://www.mykepu.com:8080/pic/course/math/1.png",
        "id": 47,
        "name": "基础课程",
        "pid": "1",
        "profile": "",
        "subAllNum": 0,
        "totalTime": "",
        "type": "2",
        "child": [
          {
            "address": "http://math.ufile.ucloud.com.cn/basicmath1.jpg",
            "id": 54,
            "name": "算数",
            "pid": "47",
            "profile": "算数",
            "subAllNum": 20,
            "totalTime": "136分钟",
            "type": "2",
            "subNum": 0,
            "playcount": 1000
          },
          {
            "address": "http://math.ufile.ucloud.com.cn/basicmath2.jpg",
            "id": 55,
            "name": "应用题",
            "pid": "47",
            "profile": "",
            "subAllNum": 15,
            "totalTime": "108分钟",
            "type": "2",
            "subNum": 0,
            "playcount": 1000
          },
          {
            "address": "http://math.ufile.ucloud.com.cn/basicmath3.jpg",
            "id": 59,
            "name": "代数",
            "pid": "47",
            "profile": "",
            "subAllNum": 16,
            "totalTime": "77分钟",
            "type": "2",
            "subNum": 0,
            "playcount": 1000
          },
          {
            "address": "http://math.ufile.ucloud.com.cn/basicmath5.jpg",
            "id": 61,
            "name": "方程与不等式",
            "pid": "47",
            "profile": "",
            "subAllNum": 8,
            "totalTime": "63分钟",
            "type": "2",
            "subNum": 0,
            "playcount": 1000
          },
          {
            "address": "http://math.ufile.ucloud.com.cn/basicmath6.jpg",
            "id": 62,
            "name": "数列",
            "pid": "47",
            "profile": "",
            "subAllNum": 9,
            "totalTime": "68分钟",
            "type": "2",
            "subNum": 0,
            "playcount": 1000
          },
          {
            "address": "http://math.ufile.ucloud.com.cn/basicmath7.jpg",
            "id": 63,
            "name": "平面几何",
            "pid": "47",
            "profile": "",
            "subAllNum": 6,
            "totalTime": "56分钟",
            "type": "2",
            "subNum": 0,
            "playcount": 1000
          },
          {
            "address": "http://math.ufile.ucloud.com.cn/basicmath8.jpg",
            "id": 64,
            "name": "立体几何",
            "pid": "47",
            "profile": "",
            "subAllNum": 3,
            "totalTime": "24分钟",
            "type": "2",
            "subNum": 0,
            "playcount": 1000
          },
          {
            "address": "http://math.ufile.ucloud.com.cn/basicmath9.jpg",
            "id": 65,
            "name": "解析几何",
            "pid": "47",
            "profile": "",
            "subAllNum": 10,
            "totalTime": "81分钟",
            "type": "2",
            "subNum": 0,
            "playcount": 1000
          },
          {
            "address": "http://math.ufile.ucloud.com.cn/basicmath10.jpg",
            "id": 66,
            "name": "排列组成",
            "pid": "47",
            "profile": "",
            "subAllNum": 7,
            "totalTime": "52分钟",
            "type": "2",
            "subNum": 0,
            "playcount": 1000
          },
          {
            "address": "http://math.ufile.ucloud.com.cn/basicmath4.jpg",
            "id": 69,
            "name": "概率",
            "pid": "47",
            "profile": "",
            "subAllNum": 6,
            "totalTime": "39分钟",
            "type": "2",
            "subNum": 0,
            "playcount": 1000
          }
        ],
        "subNum": 0
      },
      {
        "address": "http://www.mykepu.com:8080/pic/course/math/2.png",
        "id": 51,
        "name": "系统课程",
        "pid": "1",
        "profile": "",
        "subAllNum": 0,
        "totalTime": "",
        "type": "2",
        "child": [
          {
            "address": "http://math.ufile.ucloud.com.cn/systemmath1.jpg",
            "id": 56,
            "name": "敬请期待",
            "pid": "51",
            "profile": "",
            "subAllNum": 0,
            "totalTime": "",
            "type": "2",
            "subNum": 0,
            "playcount": 1000
          },
          {
            "address": "http://math.ufile.ucloud.com.cn/systemmath1.jpg",
            "id": 57,
            "name": "敬请期待",
            "pid": "51",
            "profile": "",
            "subAllNum": 0,
            "totalTime": "",
            "type": "2",
            "subNum": 0,
            "playcount": 1000
          }
        ],
        "subNum": 0
      },
      {
        "address": "http://www.mykepu.com:8080/pic/course/math/3.png",
        "id": 52,
        "name": "串讲课程",
        "pid": "1",
        "profile": "",
        "subAllNum": 0,
        "totalTime": "",
        "type": "2",
        "child": [
          {
            "address": "http://math.ufile.ucloud.com.cn/basicmath1.jpg",
            "id": 60,
            "name": "算数考点预测及拿分策略",
            "pid": "52",
            "profile": "",
            "subAllNum": 2,
            "totalTime": "48分钟",
            "type": "2",
            "subNum": 0,
            "playcount": 1000
          },
          {
            "address": "http://math.ufile.ucloud.com.cn/basicmath2.jpg",
            "id": 67,
            "name": "应用题考点预测及拿分策略",
            "pid": "52",
            "profile": "",
            "subAllNum": 2,
            "totalTime": "42分钟",
            "type": "2",
            "subNum": 0,
            "playcount": 1000
          },
          {
            "address": "http://math.ufile.ucloud.com.cn/basicmath3.jpg",
            "id": 68,
            "name": "代数与数列考点预测及拿分策略",
            "pid": "52",
            "profile": "",
            "subAllNum": 2,
            "totalTime": "54分钟",
            "type": "2",
            "subNum": 0,
            "playcount": 1000
          },
          {
            "address": "http://math.ufile.ucloud.com.cn/basicmath7.jpg",
            "id": 70,
            "name": "几何考点预测及拿分策略",
            "pid": "52",
            "profile": "",
            "subAllNum": 2,
            "totalTime": "84分钟",
            "type": "2",
            "subNum": 0,
            "playcount": 1000
          },
          {
            "address": "http://math.ufile.ucloud.com.cn/basicmath4.jpg",
            "id": 71,
            "name": "数据分析考点预测及拿分策略",
            "pid": "52",
            "profile": "",
            "subAllNum": 1,
            "totalTime": "38分钟",
            "type": "2",
            "subNum": 0,
            "playcount": 1000
          }
        ],
        "subNum": 0
      }
    ],
    "subNum": 0
  },
  "apicode": 10000
}
