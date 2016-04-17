
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
    "id": 1,
    "name": "数学",
    "profile": "数学",
    "child": [
      {
        "id": 47,
        "name": "数学1",
        "pid": "1",
        "type": "2",
        "address": "http://www.mykepu.com:8080/pic/course/math/1.png",
        "subList": [
          {
            "address": "http://www.mykepu.com:8080/pic/course/math/1.png",
            "id": 54,
            "name": "数学1-1",
            "pid": "47",
            "playcount": 0,
            "profile": "数学1-1",
            "type": "2"
          }
        ]
      },
      {
        "id": 51,
        "name": "数学2",
        "pid": "1",
        "type": "2",
        "address": "http://www.mykepu.com:8080/pic/course/math/2.png",
        "subList": []
      },
      {
        "id": 52,
        "name": "数学3",
        "pid": "1",
        "type": "2",
        "address": "http://www.mykepu.com:8080/pic/course/math/3.png",
        "subList": []
      }
    ]
  },
  "apicode": 10000
}
```
