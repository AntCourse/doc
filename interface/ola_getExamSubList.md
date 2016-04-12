

# 模考／真题的题目列表
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /exam/getExamSubList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 examId | 是 | 字符串 | 模考／真题id

###返回结果示例

```javascript
  {
  "message": "成功",
  "result": [
    {
      "id": 1,
      "question": "已知$\\left| a \\right|=5\\ ,\\ \\left| b \\right|=7\\ ,\\ ab<0$，则$\\left| a-b \\right|=$（    ）.",
      "type": null,
      "degree": null,
      "hint": "123",
      "allcount": 53,
      "rightcount": 24,
      "avgtime": 1,
      "optionList": [
        {
          "id": 1,
          "sid": null,
          "type": "",
          "content": "2",
          "isanswer": null
        },
        {
          "id": 2,
          "sid": null,
          "type": "",
          "content": "-2",
          "isanswer": null
        },
        {
          "id": 3,
          "sid": null,
          "type": "",
          "content": "12",
          "isanswer": null
        },
        {
          "id": 4,
          "sid": null,
          "type": "",
          "content": "-2",
          "isanswer": null
        },
        {
          "id": 5,
          "sid": null,
          "type": "",
          "content": "",
          "isanswer": null
        }
      ]
    },
    {
      "id": 2,
      "question": "已知${{t}^{2}}-3t-18\\le 0$，则$\\left| t+4 \\right|+\\left| t-6 \\right|=$（   ）.",
      "type": null,
      "degree": null,
      "hint": null,
      "allcount": 191,
      "rightcount": 48,
      "avgtime": 1,
      "optionList": [
        {
          "id": 6,
          "sid": null,
          "type": "",
          "content": "$2t-2$",
          "isanswer": null
        },
        {
          "id": 7,
          "sid": null,
          "type": "",
          "content": "10",
          "isanswer": null
        },
        {
          "id": 8,
          "sid": null,
          "type": "",
          "content": "3",
          "isanswer": null
        },
        {
          "id": 9,
          "sid": null,
          "type": "",
          "content": "$2t+2$",
          "isanswer": null
        },
        {
          "id": 10,
          "sid": null,
          "type": "",
          "content": "",
          "isanswer": null
        }
      ]
    },
    {
      "id": 3,
      "question": "已知$\\left| \\frac{5x-3}{2x+5} \\right|=\\left| \\frac{3-5x}{2x+5} \\right|$，则实数$x$的取值范围是（    ）.",
      "type": null,
      "degree": null,
      "hint": null,
      "allcount": 21,
      "rightcount": 1,
      "avgtime": 1,
      "optionList": [
        {
          "id": 11,
          "sid": null,
          "type": "",
          "content": "$x<-\\frac{5}{2}$或$x\\ge \\frac{3}{5}$",
          "isanswer": null
        },
        {
          "id": 12,
          "sid": null,
          "type": "",
          "content": "$-\\frac{5}{2}\\le x\\le \\frac{3}{5}$",
          "isanswer": null
        },
        {
          "id": 13,
          "sid": null,
          "type": "",
          "content": "$-\\frac{5}{2}< x\\le \\frac{3}{5}$",
          "isanswer": null
        },
        {
          "id": 14,
          "sid": null,
          "type": "",
          "content": "$-\\frac{3}{5}\\le x<\\frac{5}{2}$",
          "isanswer": null
        },
        {
          "id": 15,
          "sid": null,
          "type": "",
          "content": "以上结论均不正确",
          "isanswer": null
        }
      ]
    },
    {
      "id": 4,
      "question": "设$a\\ ,\\ b\\ ,\\ c$为整数，且${{\\left| a-b \\right|}^{20}}+{{\\left| c-a \\right|}^{41}}=1$，则$\\left| a-b \\right|+\\left| a-c \\right|+$$\\left| b-c \\right|=$（    ）.",
      "type": null,
      "degree": null,
      "hint": null,
      "allcount": 16,
      "rightcount": 7,
      "avgtime": 2,
      "optionList": [
        {
          "id": 16,
          "sid": null,
          "type": "",
          "content": "2",
          "isanswer": null
        },
        {
          "id": 17,
          "sid": null,
          "type": "",
          "content": "3",
          "isanswer": null
        },
        {
          "id": 18,
          "sid": null,
          "type": "",
          "content": "4",
          "isanswer": null
        },
        {
          "id": 19,
          "sid": null,
          "type": "",
          "content": "-3",
          "isanswer": null
        },
        {
          "id": 20,
          "sid": null,
          "type": "",
          "content": "-2",
          "isanswer": null
        }
      ]
    },
    {
      "id": 5,
      "question": "设$a\\ ,\\ b\\ ,\\ c$是小于12的三个不同的质数（素数），且$\\left| a-b \\right|+\\left| b-c \\right|+$$\\left| c-a \\right|=8$，则$a+b+c=$（    ）.",
      "type": null,
      "degree": null,
      "hint": null,
      "allcount": 16,
      "rightcount": 1,
      "avgtime": 1,
      "optionList": [
        {
          "id": 21,
          "sid": null,
          "type": "",
          "content": "10",
          "isanswer": null
        },
        {
          "id": 22,
          "sid": null,
          "type": "",
          "content": "12",
          "isanswer": null
        },
        {
          "id": 23,
          "sid": null,
          "type": "",
          "content": "14",
          "isanswer": null
        },
        {
          "id": 24,
          "sid": null,
          "type": "",
          "content": "15",
          "isanswer": null
        },
        {
          "id": 25,
          "sid": null,
          "type": "",
          "content": "19",
          "isanswer": null
        }
      ]
    }
  ],
  "apicode": 10000
}
```
