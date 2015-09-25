# 课程列表-三级
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getCourListSpe

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 pid | 是 | 字符串 | 课程id，返回本级，子集及子集所包含的知识点
 type | 否 | 字符串 | 预留参数

###返回结果示例

```javascript
  {
  "message": "成功",
  "result": {
    "courId": 5,
    "courName": "数学课程1",
    "profile":"数学课程1",
    "children": [
      {
        "childId": 7,
        "childName": "数学课程1-1",
        "pointList": [
          {
            "content": "知识点11",
            "courseId": 7,
            "id": 1,
            "name": "知识点1",
            "type": ""
          },
          {
            "content": "知识点22",
            "courseId": 7,
            "id": 2,
            "name": "知识点2",
            "type": ""
          }
        ]
      },
      {
        "childId": 8,
        "childName": "数学课程1-2",
        "pointList": [
          {
            "content": "知识点33",
            "courseId": 8,
            "id": 3,
            "name": "知识点3",
            "type": ""
          },
          {
            "content": "知识点44",
            "courseId": 8,
            "id": 4,
            "name": "知识点4",
            "type": ""
          }
        ]
      }
    ]
  },
  "apicode": 10000
}
```
