

# 获取支付宝支付订单信息
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /pay/getAliOrderInfo

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 price | 是 | 字符串 | 打赏金额 |
 courseId | 否 | 字符串 | courseId |

###请求示例
```javascript
{
    "price":"金额"
   "courseId": "courseId"
}
```

###返回结果示例

```javascript
  {
  "code": "1",
  "message": "操作成功",
  "result_data": {
    "orderInfo": "partner=\"2088122694938433\"&seller_id=\"webmaster@medkr.com\"&out_trade_no=\"1426101594\"&subject=\"打赏\"&body=\"订单号：1426101594\"&total_fee=\"1\"&notify_url=\"http://localhost:8080/SD/reward/paySuccessCallBack\"&service=\"mobile.securitypay.pay\"&payment_type=\"1\"&_input_charset=\"utf-8\"&it_b_pay=\"1d\"&return_url=\"http://www.tianjiandao.com\"",
    "orderNo": "1426101594"
  }
}


```
