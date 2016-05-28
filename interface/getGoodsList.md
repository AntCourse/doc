
# 获取整套视频或题库列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /goods/getGoodsList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 type | 是 | 字符串 | 1 视频 2 题库
 
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
      "leanstage": "6月13日－12月31日",
      "name": "2016年数学基础课程",
      "org": "由幂学教育和欧拉学院版权所有",
      "paynum": 10,
      "price": 100,
      "suitto": "全国",
      "totaltime": 128,
      "type": "1",
      "url": "",
      "videonum": 27
    },
    {
      "attentionnum": 0,
      "detail": "幂学教育全新推出全日制会计专业硕士辅导课程,会计专业硕士考研资料,会计硕士考研分数线,mpacc复试分数线,会计硕士招生院校等信息,",
      "id": 2,
      "image": "http://math.ufile.ucloud.com.cn/feemath2.jpg",
      "leanstage": "",
      "name": "2016年数学真题密训课程",
      "org": "由幂学教育和欧拉学院版权所有",
      "paynum": 10,
      "price": 100,
      "suitto": "",
      "totaltime": 128,
      "type": "1",
      "url": "",
      "videonum": 24
    },
    {
      "attentionnum": 0,
      "detail": "幂学教育全新推出全日制会计专业硕士辅导课程,会计专业硕士考研资料,会计硕士考研分数线,mpacc复试分数线,会计硕士招生院校等信息,",
      "id": 3,
      "image": "",
      "leanstage": "",
      "name": "2016年写作真题密训",
      "org": "由幂学教育和欧拉学院版权所有",
      "paynum": 10,
      "price": 100,
      "suitto": "",
      "totaltime": 0,
      "type": "1",
      "url": "",
      "videonum": 0
    },
    {
      "attentionnum": 0,
      "detail": "幂学教育全新推出全日制会计专业硕士辅导课程,会计专业硕士考研资料,会计硕士考研分数线,mpacc复试分数线,会计硕士招生院校等信息,",
      "id": 4,
      "image": "",
      "leanstage": "",
      "name": "2016年逻辑真题密训课程",
      "org": "由幂学教育和欧拉学院版权所有",
      "paynum": 10,
      "price": 100,
      "suitto": "",
      "totaltime": 0,
      "type": "1",
      "url": "",
      "videonum": 0
    },
    {
      "attentionnum": 0,
      "detail": "幂学教育全新推出全日制会计专业硕士辅导课程,会计专业硕士考研资料,会计硕士考研分数线,mpacc复试分数线,会计硕士招生院校等信息,",
      "id": 5,
      "image": "",
      "leanstage": "",
      "name": "2016年y英语真题密训",
      "org": "由幂学教育和欧拉学院版权所有",
      "paynum": 10,
      "price": 100,
      "suitto": "",
      "totaltime": 0,
      "type": "1",
      "url": "",
      "videonum": 0
    }
  ],
  "apicode": 10000
}
