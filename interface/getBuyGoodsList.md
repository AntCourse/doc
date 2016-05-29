# 获取已购买视频列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /goods/getBuyGoodsList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 userId | 是 | 字符串 | userId
 
###返回结果示例

```javascript
{
  "message": "成功",
  "result": [
    {
      "attentionnum": 0,
      "detail": "幂学教育全新推出全日制会计专业硕士辅导课程,会计专业硕士考研资料,会计硕士考研分数线,mpacc复试分数线,会计硕士招生院校等信息,",
      "id": 1,
      "image": "http://math.ufile.ucloud.com.cn/feemath1.jpg",
      "leanstage": "5月17日-12月31日",
      "name": "2016年数学基础课程",
      "org": "由幂学教育和欧拉学院版权所有",
      "paynum": 10,
      "price": 100,
      "suitto": "教材版本：全部教材版本    适合地区：全国",
      "totaltime": 128,
      "type": "1",
      "url": "",
      "videonum": 27
    }
  ],
  "apicode": 10000
}
