
# 获取视频对应的测试题
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getSubList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 pointId | 是 | 字符串 | 知识点Id | 1

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
    },
    {
      "id": 6,
      "question": "设\\[m\\ ,n\\]是小于20的质数，满足条件$\\left| m-n \\right|=2$的$\\left| m-n \\right|$共有（    ）.",
      "type": null,
      "degree": null,
      "hint": null,
      "allcount": 6,
      "rightcount": 0,
      "avgtime": 1,
      "optionList": [
        {
          "id": 26,
          "sid": null,
          "type": "",
          "content": "2组",
          "isanswer": null
        },
        {
          "id": 27,
          "sid": null,
          "type": "",
          "content": "3组",
          "isanswer": null
        },
        {
          "id": 28,
          "sid": null,
          "type": "",
          "content": "4组",
          "isanswer": null
        },
        {
          "id": 29,
          "sid": null,
          "type": "",
          "content": "5组",
          "isanswer": null
        },
        {
          "id": 30,
          "sid": null,
          "type": "",
          "content": "6组",
          "isanswer": null
        }
      ]
    },
    {
      "id": 7,
      "question": "若$\\sqrt{{{(a-60)}^{2}}}+\\left| b+90 \\right|={{(c-130)}^{10}}=0$，则$a+b+c$的值是（  ）。",
      "type": null,
      "degree": null,
      "hint": null,
      "allcount": 16,
      "rightcount": 2,
      "avgtime": 1,
      "optionList": [
        {
          "id": 31,
          "sid": null,
          "type": "",
          "content": "0",
          "isanswer": null
        },
        {
          "id": 32,
          "sid": null,
          "type": "",
          "content": "280",
          "isanswer": null
        },
        {
          "id": 33,
          "sid": null,
          "type": "",
          "content": "100",
          "isanswer": null
        },
        {
          "id": 34,
          "sid": null,
          "type": "",
          "content": "-100",
          "isanswer": null
        },
        {
          "id": 35,
          "sid": null,
          "type": "",
          "content": "无法确定",
          "isanswer": null
        }
      ]
    },
    {
      "id": 8,
      "question": "设实数$x,y$适合等式${{x}^{2}}-4xy+4{{y}^{2}}+\\sqrt{3}x+\\sqrt{3}y-6=0$，则$x+y$的最大值为（  ）。",
      "type": "",
      "degree": 0,
      "hint": "",
      "allcount": 17,
      "rightcount": 2,
      "avgtime": 1,
      "optionList": [
        {
          "id": 36,
          "sid": null,
          "type": "",
          "content": "$\\frac{\\sqrt{3}}{2}$$$",
          "isanswer": null
        },
        {
          "id": 37,
          "sid": null,
          "type": "",
          "content": "$\\frac{2\\sqrt{3}}{3}$",
          "isanswer": null
        },
        {
          "id": 38,
          "sid": null,
          "type": "",
          "content": "$2\\sqrt{3}$",
          "isanswer": null
        },
        {
          "id": 39,
          "sid": null,
          "type": "",
          "content": "$3\\sqrt{2}$",
          "isanswer": null
        },
        {
          "id": 40,
          "sid": null,
          "type": "",
          "content": "$3\\sqrt{3}$",
          "isanswer": null
        }
      ]
    },
    {
      "id": 9,
      "question": "已知$a,b,c$是不完全相等的任意实数，若$x={{a}^{2}}-bc$，$y={{b}^{2}}-ac$，$z={{c}^{2}}-ab$，则$z$（  ）。",
      "type": "",
      "degree": 0,
      "hint": "",
      "allcount": 0,
      "rightcount": 0,
      "avgtime": 0,
      "optionList": [
        {
          "id": 41,
          "sid": null,
          "type": "",
          "content": "都大于0",
          "isanswer": null
        },
        {
          "id": 42,
          "sid": null,
          "type": "",
          "content": "至少有一个大于0",
          "isanswer": null
        },
        {
          "id": 43,
          "sid": null,
          "type": "",
          "content": "至少有一个小于0",
          "isanswer": null
        },
        {
          "id": 44,
          "sid": null,
          "type": "",
          "content": "都不小于0",
          "isanswer": null
        },
        {
          "id": 45,
          "sid": null,
          "type": "",
          "content": "",
          "isanswer": null
        }
      ]
    },
    {
      "id": 10,
      "question": "$\\left| 3x+2 \\right|+2{{x}^{2}}-12xy+18{{y}^{2}}=0$，则$2y-3x=$（  ）。",
      "type": "",
      "degree": 0,
      "hint": "",
      "allcount": 14,
      "rightcount": 1,
      "avgtime": 2,
      "optionList": [
        {
          "id": 46,
          "sid": null,
          "type": "",
          "content": "$-\\frac{14}{9}$$$",
          "isanswer": null
        },
        {
          "id": 47,
          "sid": null,
          "type": "",
          "content": "$-\\frac{2}{9}$",
          "isanswer": null
        },
        {
          "id": 48,
          "sid": null,
          "type": "",
          "content": "$0$",
          "isanswer": null
        },
        {
          "id": 49,
          "sid": null,
          "type": "",
          "content": "$\\frac{2}{9}$",
          "isanswer": null
        },
        {
          "id": 50,
          "sid": null,
          "type": "",
          "content": "$\\frac{14}{9}$",
          "isanswer": null
        }
      ]
    }
  ],
  "apicode": 10000
}
