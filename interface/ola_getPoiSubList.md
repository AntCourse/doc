
# 获取知识点对应的测试题
 相关信息 | 内容
 ------ | ------
 访问类型 | POST
 访问地址 | /cour/getPoiSubList

###请求参数

 参数名称 | 是否必填 | 类型 | 说明 | 示例数据
 ------ | ------ | ------ | ------ | ------ | ------
 pointId | 是 | 字符串 | 知识点Id | 131

###返回结果示例

```javascript

{
  "message": "成功",
  "result": [
    {
      "id": 840,
      "question": "如图所示，长方形纸片沿EF折叠后，若$\\angle EFB=65$，则$\\angle AE{D}'$为（  ）．",
      "type": null,
      "degree": null,
      "hint": "根据折叠原理，\n$\\angle {D}'EF=\\angle DEF,\\angle EF{C}'=\\angle EFC=\\angle EFB+\\angle {C}'FB={{180}^{\\circ }}-{{60}^{\\circ }}={{115}^{\\circ }},$\n故$\\angle {D}'EF={{180}^{\\circ }}-\\angle EF{C}'={{65}^{\\circ }},\\angle AE{D}'={{180}^{\\circ }}-2\\angle {D}'EF={{50}^{\\circ }}$.",
      "allcount": 0,
      "rightcount": 0,
      "avgtime": 0,
      "pic": "http://math.ufile.ucloud.com.cn/pm_3.JPG",
      "hintpic": null,
      "videourl": "http://olamath.ufile.ucloud.com.cn/tiku_6/jw_3.mp4",
      "optionList": [
        {
          "id": 4196,
          "sid": null,
          "type": null,
          "content": "${{50}^{\\circ }}$",
          "isanswer": "1"
        },
        {
          "id": 4197,
          "sid": null,
          "type": null,
          "content": "${{55}^{\\circ }}$",
          "isanswer": "0"
        },
        {
          "id": 4198,
          "sid": null,
          "type": null,
          "content": "${{60}^{\\circ }}$",
          "isanswer": "0"
        },
        {
          "id": 4199,
          "sid": null,
          "type": null,
          "content": "${{65}^{\\circ }}$",
          "isanswer": "0"
        },
        {
          "id": 4200,
          "sid": null,
          "type": null,
          "content": "${{75}^{\\circ }}$",
          "isanswer": "0"
        }
      ]
    },
    {
      "id": 841,
      "question": "正方形ABCD的边长为$a$，以AB、BC、CD、DA分别为直径画半圆，这四个半圆弧所围成的阴影部分的面积为（  ）．",
      "type": null,
      "degree": null,
      "hint": "显然一个“花瓣”的面积为一个半圆的面积减去一个直角三角形的面积，则阴影部\n分的面积为$4\\times \\left( \\frac{1}{2}\\cdot \\text{ }\\!\\!\\pi\\!\\!\\text{ }{{\\left( \\frac{a}{2} \\right)}^{2}}-\\frac{1}{4}{{a}^{2}} \\right)=\\frac{\\text{ }\\!\\!\\pi\\!\\!\\text{ }-2}{2}{{a}^{2}}$.",
      "allcount": 0,
      "rightcount": 0,
      "avgtime": 0,
      "pic": "http://math.ufile.ucloud.com.cn/pm_4.JPG",
      "hintpic": null,
      "videourl": "http://olamath.ufile.ucloud.com.cn/tiku_6/jw_5.mp4",
      "optionList": [
        {
          "id": 4201,
          "sid": null,
          "type": null,
          "content": "$\\text{( }\\!\\!\\pi\\!\\!\\text{ }-2\\text{)}{{a}^{\\text{2}}}$",
          "isanswer": "0"
        },
        {
          "id": 4202,
          "sid": null,
          "type": null,
          "content": "$\\text{( }\\!\\!\\pi\\!\\!\\text{ }-1\\text{)}{{a}^{\\text{2}}}$",
          "isanswer": "0"
        },
        {
          "id": 4203,
          "sid": null,
          "type": null,
          "content": "$\\frac{\\text{ }\\!\\!\\pi\\!\\!\\text{ }-2}{2}{{a}^{\\text{2}}}$",
          "isanswer": "1"
        },
        {
          "id": 4204,
          "sid": null,
          "type": null,
          "content": "$\\frac{\\text{ }\\!\\!\\pi\\!\\!\\text{ }-2}{2}{{a}^{\\text{2}}}$",
          "isanswer": "0"
        },
        {
          "id": 4205,
          "sid": null,
          "type": null,
          "content": "$\\frac{\\text{ }\\!\\!\\pi\\!\\!\\text{ }-1}{2}{{a}^{\\text{2}}}$",
          "isanswer": "0"
        }
      ]
    },
    {
      "id": 842,
      "question": "如图所示，四边形$ABCD$中，点$E$、$F$分别在BC、CD上，FC，FE=2EB，已知${{S}_{\\Delta ADF}}=m$，${{S}_{ABCD}}=n(nm)$，则${{S}_{ABCD}}$等于（  ）．",
      "type": null,
      "degree": null,
      "hint": "显然${{S}_{ABCD}}={{S}_{\\Delta ADF}}+{{S}_{\\Delta AFC}}+{{S}_{\\Delta ACE}}+{{S}_{\\Delta ABE}}$，而${{S}_{\\Delta AFC}}={{S}_{\\Delta ADF}}=m$，${{S}_{\\Delta ACE}}={{S}_{ABCD}}-{{S}_{\\Delta AFC}}=n-m$，${{S}_{\\Delta ABE}}=\\frac{1}{2}{{S}_{\\Delta ACE}}=\\frac{n-m}{2}$，故${{S}_{ABCD}}=\\frac{3n-m}{2}$．",
      "allcount": 0,
      "rightcount": 0,
      "avgtime": 0,
      "pic": "http://math.ufile.ucloud.com.cn/pm_5.JPG",
      "hintpic": null,
      "videourl": "http://olamath.ufile.ucloud.com.cn/tiku_6/jw_6.mp4",
      "optionList": [
        {
          "id": 4206,
          "sid": null,
          "type": null,
          "content": "$\\frac{3n-m}{2}$",
          "isanswer": "0"
        },
        {
          "id": 4207,
          "sid": null,
          "type": null,
          "content": "$\\frac{3n+m}{2}$",
          "isanswer": "1"
        },
        {
          "id": 4208,
          "sid": null,
          "type": null,
          "content": "$\\frac{3n+3m}{2}$",
          "isanswer": "0"
        },
        {
          "id": 4209,
          "sid": null,
          "type": null,
          "content": "$\\frac{3n-3m}{2}$",
          "isanswer": "0"
        },
        {
          "id": 4210,
          "sid": null,
          "type": null,
          "content": "$\\frac{3n+2m}{2}$",
          "isanswer": "0"
        }
      ]
    },
    {
      "id": 843,
      "question": "如图所示，在边长为2的菱形ABCD中，$\\angle B={{45}^{\\circ }}$，AE为BC边上的高，将$\\Delta ABE$沿AE翻折后得$\\Delta A{B}'E$，则$\\Delta A{B}'E$与四边形AECD重叠部分的面积为（  ）．",
      "type": null,
      "degree": null,
      "hint": "显然有$AE=BE=\\sqrt{2}$，$CE=2-\\sqrt{2}$，${B}'C=2\\sqrt{2}-2$而$\\Delta AE{B}'=\\Delta FC{B}'$是等腰直角三角形，所以重叠部分的面积为${{S}_{AECF}}={{S}_{\\Delta AE{B}'}}-{{S}_{\\Delta FC{B}'}}=\\frac{1}{2}\\times {{\\left( \\sqrt{2} \\right)}^{2}}-\\frac{1}{2}\\times $${{\\left( 2-\\sqrt{2} \\right)}^{2}}=2\\sqrt{2}-2$．",
      "allcount": 0,
      "rightcount": 0,
      "avgtime": 0,
      "pic": "http://math.ufile.ucloud.com.cn/pm_6.JPG",
      "hintpic": null,
      "videourl": "http://olamath.ufile.ucloud.com.cn/tiku_6/jw_8.mp4",
      "optionList": [
        {
          "id": 4211,
          "sid": null,
          "type": null,
          "content": "$\\sqrt{2}-1$",
          "isanswer": "0"
        },
        {
          "id": 4212,
          "sid": null,
          "type": null,
          "content": "$2-\\sqrt{2}$",
          "isanswer": "0"
        },
        {
          "id": 4213,
          "sid": null,
          "type": null,
          "content": "$\\sqrt{2}-2$",
          "isanswer": "1"
        },
        {
          "id": 4214,
          "sid": null,
          "type": null,
          "content": "$2\\sqrt{2}-1$",
          "isanswer": "0"
        },
        {
          "id": 4215,
          "sid": null,
          "type": null,
          "content": "$2+\\sqrt{2}$",
          "isanswer": "0"
        }
      ]
    },
    {
      "id": 844,
      "question": "如图所示，由四个相同的直角三角形与中间的小正方形拼成的一个大正方形．若大正方形的面积是13，小正方形的面积是1，直角三角形的较长直角边为$a$，较短直角边为$b$．则${{a}^{3}}+{{b}^{3}}$的值为（  ）．",
      "type": null,
      "degree": null,
      "hint": "$\\left\\{ \\begin{align}& {{a}^{2}}+{{b}^{2}}=13 \\\\ & {{\\left( a-b \\right)}^{2}}=1 \\\\ \\end{align} \\right.\\Rightarrow \\left\\{ \\begin{align}& a=3 \\\\ & b=2 \\\\ \\end{align} \\right.\\Rightarrow {{a}^{3}}+{{b}^{4}}=43.$",
      "allcount": 0,
      "rightcount": 0,
      "avgtime": 0,
      "pic": "http://math.ufile.ucloud.com.cn/pm_10.JPG",
      "hintpic": null,
      "videourl": "http://olamath.ufile.ucloud.com.cn/tiku_6/jw_12.mp",
      "optionList": [
        {
          "id": 4216,
          "sid": null,
          "type": null,
          "content": "35",
          "isanswer": "0"
        },
        {
          "id": 4217,
          "sid": null,
          "type": null,
          "content": "43",
          "isanswer": "1"
        },
        {
          "id": 4218,
          "sid": null,
          "type": null,
          "content": "89",
          "isanswer": "0"
        },
        {
          "id": 4219,
          "sid": null,
          "type": null,
          "content": "97",
          "isanswer": "0"
        },
        {
          "id": 4220,
          "sid": null,
          "type": null,
          "content": "90",
          "isanswer": "0"
        }
      ]
    },
    {
      "id": 845,
      "question": "如图所示，BD，CF将长方形ABCD分成4块，$\\Delta DEF$的面积是4，$\\Delta CED$的面积是6，则四边形ABEF的面积是（  ）．",
      "type": null,
      "degree": null,
      "hint": "有$\\Delta DEF$和$\\Delta DEC$等高，面积的比等于底边的比得到$EF:FC=4:6=2:3$，再由$\\Delta DEF\\sim \\Delta BEC$，根据相似三角形面积的比等于相似比的平方得到${{S}_{\\Delta DEF}}:{{S}_{\\Delta BEC}}=4:9$，得${{S}_{\\Delta BEC}}=9$，即${{S}_{\\Delta ABD}}={{S}_{\\Delta BCD}}=6+9=15$．从而${{S}_{ABEF}}=15-{{S}_{\\Delta DEF}}=11$．即为11．",
      "allcount": 0,
      "rightcount": 0,
      "avgtime": 0,
      "pic": "http://math.ufile.ucloud.com.cn/pm_11.JPG",
      "hintpic": null,
      "videourl": "http://olamath.ufile.ucloud.com.cn/tiku_6/jw_15.mp",
      "optionList": [
        {
          "id": 4221,
          "sid": null,
          "type": null,
          "content": "9",
          "isanswer": "0"
        },
        {
          "id": 4222,
          "sid": null,
          "type": null,
          "content": "10",
          "isanswer": "0"
        },
        {
          "id": 4223,
          "sid": null,
          "type": null,
          "content": "11",
          "isanswer": "1"
        },
        {
          "id": 4224,
          "sid": null,
          "type": null,
          "content": "12",
          "isanswer": "0"
        },
        {
          "id": 4225,
          "sid": null,
          "type": null,
          "content": "14",
          "isanswer": "0"
        }
      ]
    },
    {
      "id": 846,
      "question": "如图所示，已知正方形纸片ABCD，$M$、$N$分别是AD、BC的中点，把BC边向上翻折，使点$C$恰好落在MN上的点$P$处，BQ为折痕，则$\\angle PBQ$等于（  ）．",
      "type": null,
      "degree": null,
      "hint": "根据题意，可知$\\Delta ABQ\\cong \\Delta BPQ$，有$BC=BP$，$\\angle CB{{Q}_{1}}=\\angle 3PBQ$，在$\\Delta BNP$中，$BN=\\frac{1}{2}BC=\\frac{1}{2}BP$，从而$\\angle BNP={{30}^{\\circ }}$，则$\\angle PBN={{60}^{\\circ }}$，又$\\angle CBQ=\\angle PBQ$，则$\\angle PBQ={{30}^{\\circ }}$．",
      "allcount": 0,
      "rightcount": 0,
      "avgtime": 0,
      "pic": "http://math.ufile.ucloud.com.cn/pm_12.JPG",
      "hintpic": null,
      "videourl": null,
      "optionList": [
        {
          "id": 4226,
          "sid": null,
          "type": null,
          "content": "${{15}^{\\circ }}$",
          "isanswer": "0"
        },
        {
          "id": 4227,
          "sid": null,
          "type": null,
          "content": "${{30}^{\\circ }}$",
          "isanswer": "1"
        },
        {
          "id": 4228,
          "sid": null,
          "type": null,
          "content": "${{45}^{\\circ }}$",
          "isanswer": "0"
        },
        {
          "id": 4229,
          "sid": null,
          "type": null,
          "content": "${{60}^{\\circ }}$",
          "isanswer": "0"
        },
        {
          "id": 4230,
          "sid": null,
          "type": null,
          "content": "${{75}^{\\circ }}$",
          "isanswer": "0"
        }
      ]
    },
    {
      "id": 847,
      "question": "如图所示的图形中，所有的四边形都是正方形，所有的三角形都是直角三角形，其中最大的正方形的边长为7，则正方形$A$、$B$、$C$、$D$的面积和是（  ）．",
      "type": null,
      "degree": null,
      "hint": "设$A$、$B$、$C$、$D$的边长分别为；$x$、$y$、$z$、$\\omega $，则根据勾股定理，有${{x}^{2}}+{{y}^{2}}+{{z}^{2}}+{{\\omega }^{2}}={{7}^{2}}$，而${{x}^{2}}$、${{y}^{2}}$、${{z}^{2}}$、${{\\omega }^{2}}$恰为$A$、$B$、$C$、$D$的面积，故其面积和为49．",
      "allcount": 0,
      "rightcount": 0,
      "avgtime": 0,
      "pic": "http://math.ufile.ucloud.com.cn/pm_13.JPG",
      "hintpic": null,
      "videourl": null,
      "optionList": [
        {
          "id": 4231,
          "sid": null,
          "type": null,
          "content": "48",
          "isanswer": "0"
        },
        {
          "id": 4232,
          "sid": null,
          "type": null,
          "content": "49",
          "isanswer": "1"
        },
        {
          "id": 4233,
          "sid": null,
          "type": null,
          "content": "50",
          "isanswer": "0"
        },
        {
          "id": 4234,
          "sid": null,
          "type": null,
          "content": "51",
          "isanswer": "0"
        },
        {
          "id": 4235,
          "sid": null,
          "type": null,
          "content": "52",
          "isanswer": "0"
        }
      ]
    },
    {
      "id": 848,
      "question": "如图所示，梯形ABCD被对角线分为4个小三角形，已知$\\Delta AOB$和$\\Delta BOC$的面积分别为$25\\text{c}{{\\text{m}}^{2}}$和$35\\text{c}{{\\text{m}}^{2}}$，那么梯形的面积是144．\n（1）梯形为等腰梯形．\n（2）梯形为直角梯形．",
      "type": null,
      "degree": null,
      "hint": "条件（1），显然有${{S}_{\\Delta AOB}}=35$，而$\\Delta ABO$与$\\Delta ABC$同底，所以其高的比为5:12，则$\\Delta AOB$与$\\Delta COD$高的比为5:7，又$\\Delta AOB\\sim \\Delta DOC$，故${{S}_{\\Delta COD}}=49$，所以梯形的面积为144，充分；同理，条件（2）也充分．",
      "allcount": 0,
      "rightcount": 0,
      "avgtime": 0,
      "pic": "http://math.ufile.ucloud.com.cn/pm_18.JPG",
      "hintpic": null,
      "videourl": null,
      "optionList": [
        {
          "id": 4236,
          "sid": null,
          "type": null,
          "content": "条件（1）充分，但条件（2）不充分",
          "isanswer": "0"
        },
        {
          "id": 4237,
          "sid": null,
          "type": null,
          "content": "条件（2）充分，但条件（1）不充分",
          "isanswer": "0"
        },
        {
          "id": 4238,
          "sid": null,
          "type": null,
          "content": "条件（1）和（2）单独都不充分，但条件（1）和条件（2）联合起来充分",
          "isanswer": "0"
        },
        {
          "id": 4239,
          "sid": null,
          "type": null,
          "content": "条件（1）充分，条件（2）也充分",
          "isanswer": "1"
        },
        {
          "id": 4240,
          "sid": null,
          "type": null,
          "content": "条件（1）和条件（2）单独都不充分，条件（1）和条件（2）联合起来也不充分",
          "isanswer": "0"
        }
      ]
    },
    {
      "id": 849,
      "question": "矩形ABCD中，$\\angle EFC={{90}^{\\circ }}$，CF平分$\\angle DCE$，则矩形的面积为96．\n（1）${{S}_{\\Delta CDF}}:{{S}_{\\Delta FAE}}=16:9$\n（2）$CD=8$",
      "type": null,
      "degree": null,
      "hint": "过$F$做$C{E}'$的垂线$FP$，有$\\text{Rt}\\Delta CDF\\cong \\text{Rt}\\Delta CPF,\\angle CFP=\\angle CFD$，\n$CP=CD=8$，又$\\angle {E}'FC={{90}^{\\circ }}$，则$\\angle EFP=\\angle FCP=\\angle AFE$，从而$\\text{Rt}\\Delta AFE=\\text{Rt}\\Delta PFE$．显然单独的条件（1）（2）显然不充分；\n考虑联合，则有${{S}_{\\Delta CFP}}:{{S}_{\\Delta EFP}}=16:9$，故有$\\frac{EP}{CP}=\\frac{9}{16}=\\frac{EP}{8}\\Rightarrow EP=\\frac{9}{2}$，根据射影定理有$P{{F}^{2}}=EP\\cdot CP\\Rightarrow PF=6$故$AD=2PF=12$，所以矩形面积为$12\\times 8=96$，充分．",
      "allcount": 0,
      "rightcount": 0,
      "avgtime": 0,
      "pic": "http://math.ufile.ucloud.com.cn/pm_19.JPG",
      "hintpic": "http://math.ufile.ucloud.com.cn/pm_19_jx.JPG",
      "videourl": "http://olamath.ufile.ucloud.com.cn/tiku_6/jt_3.mp4",
      "optionList": [
        {
          "id": 4241,
          "sid": null,
          "type": null,
          "content": "条件（1）充分，但条件（2）不充分",
          "isanswer": "0"
        },
        {
          "id": 4242,
          "sid": null,
          "type": null,
          "content": "条件（2）充分，但条件（1）不充分",
          "isanswer": "0"
        },
        {
          "id": 4243,
          "sid": null,
          "type": null,
          "content": "条件（1）和（2）单独都不充分，但条件（1）和条件（2）联合起来充分",
          "isanswer": "1"
        },
        {
          "id": 4244,
          "sid": null,
          "type": null,
          "content": "条件（1）充分，条件（2）也充分",
          "isanswer": "0"
        },
        {
          "id": 4245,
          "sid": null,
          "type": null,
          "content": "条件（1）和条件（2）单独都不充分，条件（1）和条件（2）联合起来也不充分",
          "isanswer": "0"
        }
      ]
    },
    {
      "id": 850,
      "question": "如图，在ABCD中，$AB=10$，$AD=6$，在AB上取一点$F$，使$\\Delta CBF\\sim \\Delta CDE$.\n（1）$E$是AD的中点．    \n（2）$BF=1.8$．",
      "type": null,
      "degree": null,
      "hint": "要想$\\Delta CBF\\sim \\Delta CDE$，已知$\\angle B=\\angle D$，故再知道一个角相等或者$\\angle B$两边对应成比例即可．$AB=10$，$AD=6$，则从边长角度考虑，只要$\\frac{DE}{CD}=\\frac{BF}{BC}$，显然单独的条件（1）、（2）不充分;\n考虑联合．有$DE=3$，经演算，恰好满足$\\frac{DE}{CD}=\\frac{BF}{BC}$，从而$\\Delta CBF\\sim \\Delta CDE$.",
      "allcount": 0,
      "rightcount": 0,
      "avgtime": 0,
      "pic": "http://math.ufile.ucloud.com.cn/pm_20.JPG",
      "hintpic": null,
      "videourl": "http://olamath.ufile.ucloud.com.cn/tiku_6/jt_4.mp4",
      "optionList": [
        {
          "id": 4246,
          "sid": null,
          "type": null,
          "content": "条件（1）充分，但条件（2）不充分",
          "isanswer": "0"
        },
        {
          "id": 4247,
          "sid": null,
          "type": null,
          "content": "条件（2）充分，但条件（1）不充分",
          "isanswer": "0"
        },
        {
          "id": 4248,
          "sid": null,
          "type": null,
          "content": "条件（1）和（2）单独都不充分，但条件（1）和条件（2）联合起来充分",
          "isanswer": "1"
        },
        {
          "id": 4249,
          "sid": null,
          "type": null,
          "content": "条件（1）充分，条件（2）也充分",
          "isanswer": "0"
        },
        {
          "id": 4250,
          "sid": null,
          "type": null,
          "content": "条件（1）和条件（2）单独都不充分，条件（1）和条件（2）联合起来也不充分",
          "isanswer": "0"
        }
      ]
    },
    {
      "id": 851,
      "question": "在矩形$\\text{ABCD}$中，$\\text{BE=DF}$，能确定原矩形面积与四边形$\\text{AECF}$的面积之比为$\\text{3:2}$.\n（1）$\\text{BE:EA=1:2}$   \n（2）$\\text{AB=6}$，$\\text{BC=3}$，$\\text{CE=}\\sqrt{\\text{13}}$",
      "type": null,
      "degree": null,
      "hint": "设边长$CD=a$，$CB=b$，$BE=DF=x$，则题干要求推出$\\frac{ab}{(a-x)b}=\\frac{3}{2}$，即$a=3x$.\n由条件（1），$\\frac{a}{a-x}=\\frac{1}{2}$，可知$a=3x$，即条件（1）是充分的.\n由条件（2），$AB=CD=a=6$，$CB=b=3$，$CE=\\sqrt{13}$，由勾股定理，$BE=x=\\sqrt{C{{E}^{2}}-C{{B}^{2}}}=\\sqrt{13-9}=2$，从而$a=3x$成立，因而条件（2）也是充分的.",
      "allcount": 0,
      "rightcount": 0,
      "avgtime": 0,
      "pic": "http://math.ufile.ucloud.com.cn/pm_23.JPG",
      "hintpic": null,
      "videourl": null,
      "optionList": [
        {
          "id": 4251,
          "sid": null,
          "type": null,
          "content": "条件（1）充分，但条件（2）不充分",
          "isanswer": "0"
        },
        {
          "id": 4252,
          "sid": null,
          "type": null,
          "content": "条件（2）充分，但条件（1）不充分",
          "isanswer": "0"
        },
        {
          "id": 4253,
          "sid": null,
          "type": null,
          "content": "条件（1）和（2）单独都不充分，但条件（1）和条件（2）联合起来充分",
          "isanswer": "0"
        },
        {
          "id": 4254,
          "sid": null,
          "type": null,
          "content": "条件（1）充分，条件（2）也充分",
          "isanswer": "1"
        },
        {
          "id": 4255,
          "sid": null,
          "type": null,
          "content": "条件（1）和条件（2）单独都不充分，条件（1）和条件（2）联合起来也不充分",
          "isanswer": "0"
        }
      ]
    },
    {
      "id": 852,
      "question": "如图所示，在矩形ABCD中，BE=DF，能确定原矩形的面积与四边形AECF的面\n积之比为3:2．\n（1）$BE:EA=1:2$．\n（2）$AB=6$，$BC=3$，$CE=\\sqrt{13}$",
      "type": null,
      "degree": null,
      "hint": "条件（1），设$AE=2x$，$BE=x$.则${{S}_{ABCF}}=(2x+x)\\times AD=3x\\cdot AD$，${{S}_{AECF}}=2x\\cdot AD$，${{S}_{ABCD}}:{{S}_{AECF}}=(2x+x)\\times AD:(2x\\cdot AD)=3:2$，满足；\n条件（2），显然${{S}_{ABCD}}=18$，$CE=\\sqrt{13}$，则$CE=\\sqrt{C{{E}^{2}}-B{{C}^{2}}}=2$，故$AE=4$，${{S}_{AECF}}=3\\times 4=12$，${{S}_{ABCD}}:{{S}_{AECF}}=18:12=3:2$满足．",
      "allcount": 0,
      "rightcount": 0,
      "avgtime": 0,
      "pic": "http://math.ufile.ucloud.com.cn/pm_28.JPG",
      "hintpic": null,
      "videourl": null,
      "optionList": [
        {
          "id": 4256,
          "sid": null,
          "type": null,
          "content": "条件（1）充分，但条件（2）不充分",
          "isanswer": "0"
        },
        {
          "id": 4257,
          "sid": null,
          "type": null,
          "content": "条件（2）充分，但条件（1）不充分",
          "isanswer": "0"
        },
        {
          "id": 4258,
          "sid": null,
          "type": null,
          "content": "条件（1）和（2）单独都不充分，但条件（1）和条件（2）联合起来充分",
          "isanswer": "0"
        },
        {
          "id": 4259,
          "sid": null,
          "type": null,
          "content": "条件（1）充分，条件（2）也充分",
          "isanswer": "1"
        },
        {
          "id": 4260,
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
