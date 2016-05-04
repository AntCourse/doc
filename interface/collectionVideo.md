

# 课程列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /collection/collectionVideo

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userId | 是 | 字符串 | 用户id
 videoId | 是 | 字符串 | 视频Id
 courseId | 是 | 字符串 | 课程id
 state | 是 | 字符串 | 1 收藏 0 取消

###返回结果示例

```javascript
{
  "message": "成功",
  "apicode": 10000
}
