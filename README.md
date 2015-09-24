### 接口说明


工作模块 | 工作项 | 端口编号 
------ | ------ | ------ | -------- | ------- | ------- 
用户 | | | | |
* | :one:用户登陆 | /user/[login](./interface/login.md) 
* | :one:用户注册 | /user/[reg](./interface/reg.md) 
* | :one:获取短信验证码 | /user/[getYzmByPhone](./interface/getYzmByPhone.md) 
* | :one:信息修改 | /user/[update](./interface/update.md)
* | :one:用户查询 | /user/[queryUser](./interface/queryUser.md) 
* | :one:邮箱获取验证码 | /user/[getYzmByEmail](./interface/getYzmByEmail.md) 
* | :one:查询手机验证码是否过期 | /user/[phoneIsInvalid](./interface/phoneIsInvalid.md) 
* | :one:用户唯一性验证 | /user/[userUnique](./interface/userUnique.md) 
* | :one:修改密码 | /user/[modifypasswd](./interface/modifypasswd.md) 
* | :one:用户签到 | /user/[userSignIn](./interface/userSignIn.md) 
课程 | | | | |
* | :one:课程列表-两级 | /cour/[getCourList](./interface/getCourList.md) 
* | :one:课程列表-三级 | /cour/[getCourListSpe](./interface/getCourListSpe.md) 
* | :one:知识点列表 | /cour/[getPointList](./interface/getPointList.md) 
* | :one:知识点对应的视频 | /cour/[getVideoByPoi](./interface/getVideoByPoi.md) 
* | :one:视频信息更新 | /cour/[updVideoInfo](./interface/updVideoInfo.md) 
* | :one:获取视频对应的测试题 | /cour/[getSubList](./interface/getSubList.md) 
* | :one:答案验证 | /cour/[checkAnswer](./interface/checkAnswer.md) 
* | :one:获取测试题的相关视频 | /cour/[getVideoBySub](./interface/getVideoBySub.md)
