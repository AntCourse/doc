
# 获取微信支付订单信息
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /reward/getWXPayReq

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 price | 是 | 字符串 | 打赏金额 |
 experGid | 是 | 字符串 | 专家gid |

###请求示例
```javascript
{
    "price":"打赏金额"
   "experGid": "专家gid"
}
```

###返回结果示例

```javascript
  {
  "code": 1,
  "message": "成功",
  "result_data": {
    "appid": "wxbb88b0b8e23e130f",
    "noncestr": "fq65RyFPMljlmroV",
    "package": "Sign=WXPay",
    "partnerid": "1315757101",
    "prepayid": "wx201604211423210acdd0c7290282579590",
    "sign": "500C92EA164521C1C8171A924B11480D",
    "timestamp": "1461219800"
  }
}


```
