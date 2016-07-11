# 图片上传
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /common/picUpload

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 imgData | 是 | 字符串 | 图片二进制字符串 | 
 imgAngle | 是 | 数字 | 拍摄角度 | 
 width | 否 | 数字 | 宽度 | 
 height | 否 | 字符串 | 高度 | 
 picType | 否 | 字符串 | 图片类型 | 

###请求示例
```javascript
{
   "imgData": "图片二进制字符串",
   "imgAngle": "拍摄角度",
   "width": "宽度",
   "height":"高度",
   "picType":"png"
}
```

###返回结果示例

```javascript
  {
     "code": 1,
     "message": "上传成功",
     "imgGid":"图片GID"
  }

```
