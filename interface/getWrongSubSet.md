# 错题集
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getWrongSubSet

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 cid | 是 | 字符串 | 课程id，返回本级及其子集信息
 type | 是 | 字符串 | 1 用于考点的课程列表 2 用户视频的课程列表
 userid | 否 | 字符串 

###返回结果示例

```javascript
{
  "message": "成功",
  "result": [
    {
      "id": 447,
      "question": "$m=\\sqrt{\\text{3}}-\\text{2}$\n（1）$m=\\frac{\\sqrt{\\text{3}}-3}{\\text{2}+\\sqrt{\\text{3}}}$ \n（2）$m=\\frac{\\text{1}-\\sqrt{\\text{3}}}{\\text{1}+\\sqrt{\\text{3}}}$",
      "type": null,
      "degree": null,
      "hint": "由（1）$m=\\frac{\\sqrt{\\text{3}}-}{\\text{2}+\\sqrt{\\text{3}}}\\text{3}=\\frac{(\\sqrt{\\text{3}}-\\text{3})(\\text{2}-\\sqrt{\\text{3}})}{(\\text{2}+\\sqrt{\\text{3}})(\\text{2}-\\sqrt{\\text{3}})}=\\text{5}\\sqrt{\\text{3}}-\\text{9}$，不充分；\n由（2）$m=\\frac{\\text{1}-\\sqrt{\\text{3}}}{\\text{1}+\\sqrt{\\text{3}}}=\\frac{(\\text{1}-\\sqrt{\\text{3}})(\\text{1}-\\sqrt{\\text{3}})}{(\\text{1}+\\sqrt{\\text{3}})(\\text{1}-\\sqrt{\\text{3}})}=\\sqrt{\\text{3}}-\\text{2}$，充分，选B.",
      "allcount": 1,
      "rightcount": 0,
      "avgtime": 0,
      "pic": null,
      "hintpic": null,
      "videourl": null,
      "optionList": [
        {
          "id": 2231,
          "sid": null,
          "type": null,
          "content": "条件（1）充分，但条件（2）不充分",
          "isanswer": "0"
        },
        {
          "id": 2232,
          "sid": null,
          "type": null,
          "content": "条件（2）充分，但条件（1）不充分",
          "isanswer": "1"
        },
        {
          "id": 2233,
          "sid": null,
          "type": null,
          "content": "条件（1）和（2）单独都不充分，但条件（1）和条件（2）联合起来充分",
          "isanswer": "0"
        },
        {
          "id": 2234,
          "sid": null,
          "type": null,
          "content": "条件（1）充分，条件（2）也充分",
          "isanswer": "0"
        },
        {
          "id": 2235,
          "sid": null,
          "type": null,
          "content": "条件（1）和条件（2）单独都不充分，条件（1）和条件（2）联合起来也不充分",
          "isanswer": "0"
        }
      ]
    },
    {
      "id": 448,
      "question": "$\\sqrt{(\\text{5}-x){{(x-\\text{3})}^{\\text{2}}}}=(x-\\text{3})\\sqrt{\\text{5}-x}$\n（1）$x\\ge \\text{3}$\n（2）$x\\le \\text{6}$",
      "type": null,
      "degree": null,
      "hint": "由题，$x-\\text{3}\\ge 0$和$\\text{5}-x\\ge 0$，得到$\\text{3}\\le x\\le \\text{5}$，两个条件单独均不充分，联合起来也不充分，故选E.",
      "allcount": 1,
      "rightcount": 0,
      "avgtime": 0,
      "pic": null,
      "hintpic": null,
      "videourl": null,
      "optionList": [
        {
          "id": 2236,
          "sid": null,
          "type": null,
          "content": "条件（1）充分，但条件（2）不充分",
          "isanswer": "0"
        },
        {
          "id": 2237,
          "sid": null,
          "type": null,
          "content": "条件（2）充分，但条件（1）不充分",
          "isanswer": "0"
        },
        {
          "id": 2238,
          "sid": null,
          "type": null,
          "content": "条件（1）和（2）单独都不充分，但条件（1）和条件（2）联合起来充分",
          "isanswer": "0"
        },
        {
          "id": 2239,
          "sid": null,
          "type": null,
          "content": "条件（1）充分，条件（2）也充分",
          "isanswer": "0"
        },
        {
          "id": 2240,
          "sid": null,
          "type": null,
          "content": "条件（1）和条件（2）单独都不充分，条件（1）和条件（2）联合起来也不充分",
          "isanswer": "1"
        }
      ]
    },
    {
      "id": 449,
      "question": "$m=-\\text{2}\\sqrt{\\text{6}}$\n（1）$m=\\text{4}\\sqrt{\\text{24}}-\\text{6}\\sqrt{\\text{54}}+\\text{3}\\sqrt{\\text{96}}-\\text{2}\\sqrt{\\text{150}}$\n（2）$m=\\text{4}\\sqrt{\\text{24}}-\\text{6}\\sqrt{\\text{54}}+\\text{3}\\sqrt{\\text{96}}$",
      "type": null,
      "degree": null,
      "hint": "由（1）\n$m=\\text{4}\\sqrt{2\\text{4}}-\\text{6}\\sqrt{\\text{54}}+\\text{3}\\sqrt{\\text{96}}-\\text{2}\\sqrt{\\text{150}}=\\text{4}\\cdot 2\\sqrt{\\text{6}}-\\text{6}\\cdot \\text{3}\\sqrt{\\text{6}}+\\text{3}\\cdot \\text{4}\\sqrt{\\text{6}}-2\\cdot \\text{5}\\sqrt{\\text{6}}=-\\text{8}\\sqrt{\\text{6}}$，不充分；由（2）\n$m=\\text{4}\\sqrt{\\text{24}}-\\text{6}\\sqrt{\\text{54}}+\\text{2}\\sqrt{\\text{96}}=\\text{4}\\cdot \\text{2}\\sqrt{\\text{6}}-\\text{6}\\cdot \\text{3}\\sqrt{\\text{6}}+\\text{2}\\cdot \\text{4}\\sqrt{\\text{6}}=-\\text{2}\\sqrt{\\text{6}}$，充分，选B.",
      "allcount": 1,
      "rightcount": 0,
      "avgtime": 0,
      "pic": null,
      "hintpic": null,
      "videourl": null,
      "optionList": [
        {
          "id": 2241,
          "sid": null,
          "type": null,
          "content": "条件（1）充分，但条件（2）不充分",
          "isanswer": "0"
        },
        {
          "id": 2242,
          "sid": null,
          "type": null,
          "content": "条件（2）充分，但条件（1）不充分",
          "isanswer": "1"
        },
        {
          "id": 2243,
          "sid": null,
          "type": null,
          "content": "条件（1）和（2）单独都不充分，但条件（1）和条件（2）联合起来充分",
          "isanswer": "0"
        },
        {
          "id": 2244,
          "sid": null,
          "type": null,
          "content": "条件（1）充分，条件（2）也充分",
          "isanswer": "0"
        },
        {
          "id": 2245,
          "sid": null,
          "type": null,
          "content": "条件（1）和条件（2）单独都不充分，条件（1）和条件（2）联合起来也不充分",
          "isanswer": "0"
        }
      ]
    },
    {
      "id": 451,
      "question": "$\\sqrt{\\frac{x}{x-\\text{2}}}=\\frac{\\sqrt{x}}{\\sqrt{x-\\text{2}}}$\n（1）$x\\le \\text{5}$\n（2）$x>\\text{3}$",
      "type": null,
      "degree": null,
      "hint": "题干只需$x>\\text{2}$即可，所以条件（2）充分，选B",
      "allcount": 1,
      "rightcount": 0,
      "avgtime": 0,
      "pic": null,
      "hintpic": null,
      "videourl": null,
      "optionList": [
        {
          "id": 2251,
          "sid": null,
          "type": null,
          "content": "条件（1）充分，但条件（2）不充分",
          "isanswer": "0"
        },
        {
          "id": 2252,
          "sid": null,
          "type": null,
          "content": "条件（2）充分，但条件（1）不充分",
          "isanswer": "1"
        },
        {
          "id": 2253,
          "sid": null,
          "type": null,
          "content": "条件（1）和（2）单独都不充分，但条件（1）和条件（2）联合起来充分",
          "isanswer": "0"
        },
        {
          "id": 2254,
          "sid": null,
          "type": null,
          "content": "条件（1）充分，条件（2）也充分",
          "isanswer": "0"
        },
        {
          "id": 2255,
          "sid": null,
          "type": null,
          "content": "条件（1）和条件（2）单独都不充分，条件（1）和条件（2）联合起来也不充分",
          "isanswer": "0"
        }
      ]
    },
    {
      "id": 452,
      "question": "$a+b=\\text{1}$\n（1）$b=\\frac{\\sqrt{{{a}^{\\text{2}}}-\\text{1}}+\\sqrt{\\text{1}-{{a}^{\\text{2}}}}}{a+\\text{1}}$\n（2）$b=\\frac{\\sqrt{{{a}^{\\text{2}}}-\\text{1}}+\\sqrt{\\text{1}-{{a}^{\\text{2}}}}}{a-\\text{1}}$",
      "type": null,
      "degree": null,
      "hint": "由（1）可得，分子$\\sqrt{{{a}^{\\text{2}}}-\\text{1}}\\ge 0$且$\\sqrt{\\text{1}-{{a}^{\\text{2}}}}\\ge 0\\Rightarrow a=\\pm 1$，又分母不能为零，故$a=\\text{1}$，$b=0$，充分；\n同理由（2）可得：$a=-\\text{1},b=0$，不充分，选A.",
      "allcount": 1,
      "rightcount": 0,
      "avgtime": 0,
      "pic": null,
      "hintpic": null,
      "videourl": null,
      "optionList": [
        {
          "id": 2256,
          "sid": null,
          "type": null,
          "content": "条件（1）充分，但条件（2）不充分",
          "isanswer": "1"
        },
        {
          "id": 2257,
          "sid": null,
          "type": null,
          "content": "条件（2）充分，但条件（1）不充分",
          "isanswer": "0"
        },
        {
          "id": 2258,
          "sid": null,
          "type": null,
          "content": "条件（1）和（2）单独都不充分，但条件（1）和条件（2）联合起来充分",
          "isanswer": "0"
        },
        {
          "id": 2259,
          "sid": null,
          "type": null,
          "content": "条件（1）充分，条件（2）也充分",
          "isanswer": "0"
        },
        {
          "id": 2260,
          "sid": null,
          "type": null,
          "content": "条件（1）和条件（2）单独都不充分，条件（1）和条件（2）联合起来也不充分",
          "isanswer": "0"
        }
      ]
    }
  ],
  "apicode": 10000
}
