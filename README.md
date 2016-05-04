### 极速学院


工作模块 | 工作项 | 端口编号 
------ | ------ | ------ | -------- | ------- | ------- 
用户 | | | | |
* | :one:用户登陆 | /user/[login](./interface/login.md) 
* | :one:登出 |  /user/[loginOut](./interface/loginOut.md) 
* | :one:用户注册 | /user/[reg](./interface/reg.md) 
* | :one:获取短信验证码 | /user/[getYzmByPhone](./interface/getYzmByPhone.md) 
* | :one:根据id修改用户信息 | /user/[update](./interface/update.md)
* | :one:根据id查询用户的信息 | /user/[queryUser](./interface/queryUser.md)
* | :one:修改密码 | /user/[modifypasswd](./interface/modifypasswd.md) 
* | :one:用户签到 | /user/[userSignIn](./interface/userSignIn.md) 
* | :one:上传图片 | /user/[fileUpload](./interface/fileUpload.md) 
课程 | | | | |
* | :one:课程列表-两级 | /cour/[getCourList](./interface/getCourList.md) 
* | :one:课程列表-三级 | /cour/[getCourListSpe](./interface/getCourListSpe.md) 
* | :one:知识点列表 | /cour/[getPointList](./interface/getPointList.md) 
* | :one:知识点详细信息 | /cour/[getPointDetail](./interface/getPointDetail.md) 
* | :one:知识点对应的视频 | /cour/[getVideoByPoi](./interface/getVideoByPoi.md) 
* | :one:视频信息更新 | /cour/[updVideoInfo](./interface/updVideoInfo.md) 
* | :one:获取视频对应的测试题 | /cour/[getSubList](./interface/getSubList.md) 
* | :one:答案验证 | /cour/[checkAnswer](./interface/checkAnswer.md) 
* | :one:获取测试题的相关视频 | /cour/[getVideoBySub](./interface/getVideoBySub.md)
* | :one:获取推荐视频 | /cour/[getRecommendVideo](./interface/getRecommendVideo.md)
* | :one:知识点学习记录 | /cour/[setPointLog](./interface/setPointLog.md)


### 欧拉学院

工作模块 | 工作项 | 端口编号 
------ | ------ | ------ | -------- | ------- | ------- 
用户 | | | | |
* | :one:用户登陆 | /user/[login](./interface/login.md) 
* | :one:登出 |  /user/[loginOut](./interface/loginOut.md) 
* | :one:用户注册 | /user/[reg](./interface/reg.md) 
* | :one:获取短信验证码 | /user/[getYzmByPhone](./interface/getYzmByPhone.md) 
* | :one:根据id修改用户信息 | /user/[update](./interface/update.md)
* | :one:根据id查询用户的信息 | /user/[queryUser](./interface/queryUser.md)
* | :one:修改密码 | /user/[modifypasswd](./interface/modifypasswd.md) 
* | :one:用户签到 | /user/[userSignIn](./interface/userSignIn.md) 
* | :one:上传图片 | /user/[fileUpload](./interface/fileUpload.md)
考点 | | | | |
* | :one:课程列表 | /cour/[getCourList](./interface/ola_getCourList.md) 
* | :one:知识点对应的考点试题 | /cour/[getPoiSubList](./interface/ola_getPoiSubList.md)
* | :one:知识点详情 | /cour/[getPointDetail](./interface/getPointDetail.md) 
* | :one:提交测试题的答案 | /cour/[checkAnswer](./interface/checkAnswer.md) 
* | :one:获取试题答案 | /cour/[getSubjectAnswer](./interface/ola_getSubjectAnswer.md)
* | :one:获取试题提示 | /cour/[getSubjectAnswer](./interface/ola_getSubjectHint.md)
* | :one:知识点对应的视频 | /cour/[getVideoByPoi](./interface/ola_getVideoByPoi.md) 
模考 | | | | |
* | :one:真题／模考列表 | /exam/[getExamList](./interface/ola_getExamList.md) 
* | :one:真题／模考对应的试题 | /exam/[getExamSubList](./interface/ola_getExamSubList.md) 
视频 | | | | |
* | :one:课程列表 | /cour/[getCourList](./interface/ola_getCourList.md) 
* | :one:获取课程视频 | /cour/[getVideoByPoi](./interface/ola_getVideoByPoi.md)
* | :one:获取整套视频或题库 | /goods/[getGoodsList](./interface/getGoodsList.md)
* 欧拉圈| | | | |
* | :one:视频观看历史列表 | /cour/[getHistoryList](./interface/ola_getHistoryList.md) 
* 我的| | | | |
* | :one:知识型谱 | /cour/[getStatisticsList](./interface/getStatisticsList.md) 
* | :one:视频收藏列表 | /collection/[getCollectionByUserId](./interface/getCollectionByUserId.md) 
* 支付 | | | | |
* | :one:微信支付信息 | /pay/[getWXPayReq](./interface/getWXPayReq.md) 
* | :one:支付宝支付信息 | /pay/[getAliOrderInfo](./interface/getAliOrderInfo.md)
