# 获取知识点详细信息
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getPointDetail

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 pointId | 是 | 字符串 | 知识点id
 
###返回结果示例

```javascript
{
  "message": "成功",
  "result": {
    "id": 1,
    "name": "分数与小数",
    "content": "分数与小数",
    "type": null,
    "courseId": 7
  },
  "apicode": 10000
}

```
