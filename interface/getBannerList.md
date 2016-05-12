# 课程首页banner
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getBannerList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------

###返回结果示例
{
  "message": "成功",
  "result": [
    {
      "id": 61,
      "type": "2", // 课程文件夹
      "name": "方程与不等式",
      "profile": null,
      "address": "http://math.ufile.ucloud.com.cn/basicmath5.jpg",
      "pid": "47",
      "playcount": 1000,
      "subAllNum": 8,
      "totalTime": "63分钟",
      "isBanner": 1
    },
    {
      "id": 72,
      "type": "3",  //文章链接
      "name": "2017MPAcc管理类联考“车票”你抢到了吗？",
      "profile": "http://mp.weixin.qq.com/s?__biz=MzIwMzI4MjE0OA==&mid=2247483722&idx=1&sn=bac4810d18a5ed226ddb251f207d7534&scene=0#wechat_redirect",
      "address": "http://image.baidu.com/search/detail?ct=503316480&z=undefined&tn=baiduimagedetail&ipn=d&word=%E5%AD%A6%E4%B9%A0%20%E7%BE%8E%E5%A5%B3&step_word=&ie=utf-8&in=&cl=2&lm=-1&st=undefined&cs=735005700,150294",
      "pid": null,
      "playcount": null,
      "subAllNum": null,
      "totalTime": null,
      "isBanner": 1
    }
  ],
  "apicode": 10000
}
