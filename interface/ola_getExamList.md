
# 模考／真题列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /exam/getExamList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 courseId | 是 | 字符串 | 课程id
 type | 是 | 字符串 | 1 模考 2 真题
 usrId | 否 | 字符串 |

###返回结果示例

```javascript

{
  "message": "成功",
  "result": [
    {
      "cid": 1,
      "coverpoint": 4,
      "degree": 5,
      "id": 9,
      "name": "模考试题一",
      "target": 89,
      "type": "1",
      "rank": "123"
    },
    {
      "cid": 1,
      "coverpoint": 6,
      "degree": 5,
      "id": 10,
      "name": "模考试题二",
      "target": 11,
      "type": "1",
      "rank": "123"
    },
    {
      "cid": 1,
      "coverpoint": 7,
      "degree": 7,
      "id": 11,
      "name": "模考试题三",
      "target": 22,
      "type": "1",
      "rank": "123"
    },
    {
      "cid": 1,
      "coverpoint": 8,
      "degree": 4,
      "id": 12,
      "name": "模考试题四",
      "target": 33,
      "type": "1",
      "rank": "123"
    },
    {
      "cid": 1,
      "coverpoint": 9,
      "degree": 26,
      "id": 13,
      "name": "模考试题五",
      "target": 44,
      "type": "1",
      "rank": "123"
    },
    {
      "cid": 1,
      "coverpoint": 6,
      "degree": 7,
      "id": 14,
      "name": "模考试题六",
      "target": 55,
      "type": "1",
      "rank": "123"
    },
    {
      "cid": 1,
      "coverpoint": 5,
      "degree": 4,
      "id": 15,
      "name": "模考试题七",
      "target": 66,
      "type": "1",
      "rank": "123"
    },
    {
      "cid": 1,
      "coverpoint": 10,
      "degree": 1,
      "id": 16,
      "name": "模考试题八",
      "target": 77,
      "type": "1",
      "rank": "123"
    }
  ],
  "apicode": 10000
}

```
