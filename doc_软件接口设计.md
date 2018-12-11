**目 录**

[1 用户鉴权部分接口](#用户鉴权部分接口)


[1.1 修改密码](#修改密码)

[1.1 修改登录名](#修改登录名)

[1.1 注册](#注册)

[1.2 注册手机号码校验](#注册手机号码校验)

[1.3 登录](#登录)

[1.4 注销](#注销)

[2 个人信息部分接口](#个人信息部分接口)

[2.2 实名认证](#实名认证)

[2.3 查看个人信息](#查看个人信息)

[2.4 修改电话](#修改电话)

[2.5 查询用户所在植保队列表](#查询用户所在植保队列表)

[2.6 选择当前团队](#选择当前团队)

[2.7 我的执照列表](#我的执照列表)

[2.8 设置地址](#设置地址)

[2.9 设置发票抬头](#设置发票抬头)

[2.10 申请发票](#申请发票)

[2.11 创建地址](#创建地址)

[2.12 更新地址](#更新地址)

[2.13 查询地址列表](#查询地址列表)

[2.14 查询地址详情](#查询地址详情)

[2.15 删除地址](#删除地址)

[2.15 用户头像上传(未登记)](#用户头像上传(未登记))


[3 消息部分接口](#消息部分接口)

[3.1 设置消息提醒](#设置消息提醒)

[3.2 未读消息总数](#未读消息总数)

[3.3 订单消息列表](#订单消息列表)

[3.4 团队消息列表](#团队消息列表)

[3.5 联盟消息列表](#联盟消息列表)

[3.6 设备消息列表](#设备消息列表)

[3.7 消息列表](#消息列表)

[4 团队管理部分接口](#团队管理部分接口)

[4.1 创建植保队](#创建植保队)

[4.2 团队列表](#团队列表)

[4.3 植保队详情](#植保队详情)

[4.4 团队申请列表](#团队申请列表)

[4.5 申请加入团队列表](#申请加入团队列表)

[4.6 申请审批](#申请审批)

[4.7 团队logo修改](#团队logo修改)

[4.8 团队订单列表](#团队订单列表)

[4.9 团队认证](#团队认证)

[4.10 植保队成员列表](#植保队成员列表)

[4.11 队长权限转让](#队长权限转让)

[4.12 解散团队](#解散团队)

[4.13 团队邀请](#团队邀请)

[4.14 队员当前任务列表](#队员当前任务列表)

[4.15 队员所在团队作业统计](#队员所在团队作业统计)

[4.16 查询队员任务列表](#查询队员任务列表)

[4.17 团队认证详情](#团队认证详情)

[4.18 申请加入植保队](#申请加入植保队)

[5 作业统计部分接口](#作业统计部分接口)

[5.1 团队作业统计](#团队作业统计)

[5.2 团队作业记录统计](#团队作业记录统计)

[5.3 团队月作业曲线图](#团队月作业曲线图)

[5.4 团队日作业曲线图](#团队日作业曲线图)

[5.5 团队农作物柱状图](#团队农作物柱状图)

[5.6 团队地区作业记录](#团队地区作业记录)

[5.7 团队设备作业统计](#团队设备作业统计)

[5.8 团队人员作业统计](#团队人员作业统计)

[5.9 团队订单统计](#团队订单统计)

[5.10 用户作业统计](#用户作业统计)

[5.11 用户作业记录统计](#用户作业记录统计)

[5.12 用户月作业曲线图](#用户月作业曲线图)

[5.13 用户日作业曲线图](#用户日作业曲线图)

[5.14 用户农作物柱状图](#用户农作物柱状图)

[5.15 用户地区作业记录](#用户地区作业记录)

[5.16 用户设备作业统计](#用户设备作业统计)

[5.17 用户订单统计](#用户订单统计)


[6 设备管理部分接口](#设备管理部分接口)

[6.1 无人机列表](#无人机列表)

[6.2 设备详情](#设备详情)

[6.3 设备转移](#设备转移)

[6.4 设备维护](#设备维护)

[6.5 无人机设备报废](#无人机设备报废)

[6.6 设备作业信息列表](#设备作业信息列表)

[6.7 设备使用记录统计](#设备使用记录统计)

[6.8 设备使用记录列表](#设备使用记录列表)

[6.9 设备维护记录列表](#设备维护记录列表)

[6.10 设备流转记录列表](#设备流转记录列表)

[6.11 RTK列表](#rtk列表)

[6.12 RTK设备详情](#rtk设备详情)

[6.13 RTK设备流转记录列表](#rtk设备流转记录列表)

[6.14 设备自用](#设备自用)

[6.15 设备设置共享团队](#设备设置共享团队)

[6.16 查询设备共享团队列表](#查询设备共享团队列表)

[6.17 查询团队设备列表](#查询团队设备列表)

[6.18 分配设备](#分配设备)

[6.19 千寻账号绑定](#千寻账号绑定)

[6.20 千寻账号解绑](#千寻账号解绑)

[6.21 微信端查询可绑定千寻账号列表](#微信端查询可绑定千寻账号列表)

[6.22 APP端查询可绑定千寻账号列表](#APP端查询可绑定千寻账号列表)

[6.23 查询已租赁设备列表](#查询已租赁设备列表)

[6.24 根据设备ID,团队ID查询已分配队员列表](#根据设备ID,团队ID查询已分配队员列表)

[6.25 设备问题类型字典表](#设备问题类型字典表)

[6.26 无人机类型字典表](#无人机类型字典表)

[6.27 获取RTK流量详情](#获取RTK流量详情)

[6.28 千寻账号详情](#千寻账号详情)

[6.29 RTK设备报废](#RTK设备报废)


[7 联盟管理部分接口](#联盟管理部分接口)

[7.1 创建联盟](#创建联盟)

[7.2 编辑联盟](#编辑联盟)

[7.3 联盟列表](#联盟列表)

[7.4 联盟详情](#联盟详情)

[7.5 联盟团队列表](#联盟团队列表)

[7.6 邀请加入联盟](#邀请加入联盟)

[7.7 联盟申请加入](#联盟申请加入)

[7.8 联盟申请列表](#联盟申请列表)

[7.9 审批联盟申请](#审批联盟申请)

[7.10 解散联盟(未登记)](#解散联盟(未登记))

[7.11	盟主权限转让(未登记)](#盟主权限转让(未登记))

[7.12	退出联盟(未登记)](#退出联盟(未登记))

[7.13	移除联盟团队(未登记)](#移除联盟团队(未登记))

[8 个人中心部分接口](#个人中心部分接口)

[8.1 沙盘统计（未登记）](#沙盘统计未登记)

[8.2 我的订单列表（未登记）](#我的订单列表未登记)

[8.3 市级行政区列表](#市级行政区列表)

[8.4 根据地区ID获取用户地块列表（此接口作废）](#根据地区id获取用户地块列表此接口作废)

[8.5 地块设备作业详情（未登记）](#地块设备作业详情未登记)

[8.6 新建反馈](#新建反馈)

[8.7 反馈详情列表](#反馈详情列表)

[9 订单管理部分接口](#订单管理部分接口)

[9.1 主页（作业统计）](#主页作业统计)

[9.2 主页（订单统计）](#主页订单统计)

[9.3 订单管理(列表)](#订单管理列表)

[9.4 创建订单](#创建订单)

[9.5 农药列表](#农药列表)

[9.6 农作物类型列表](#农作物类型列表)

[9.7 订单详情](#订单详情)

[9.8 申请作业数量](#申请作业数量)

[9.9 参与团队列表](#参与团队列表)

[9.10 订单申请列表](#订单申请列表)

[9.11 审核加入作业申请接口](#审核加入作业申请接口)

[9.12 参与团队详情接口](#参与团队详情接口)

[9.13 停止作业接口](#停止作业接口)

[9.14 订单作业设备列表接口](#订单作业设备列表接口)

[9.15 订单卫星地图列表](#订单卫星地图列表)

[9.16 订单地块详情](#订单地块详情)

[9.17 招募状态改变接口](#招募状态改变接口)

[9.18 订单完成接口](#订单完成接口)

[10 订单执行部分接口](#订单执行部分接口)

[10.1 订单列表](#订单列表)

[10.2 订单详情](#订单详情-1)

[10.3 查询用户所属团队列表](#查询用户所属团队列表)

[10.4 查询用户所属联盟列表](#查询用户所属联盟列表)

[10.5 创建订单](#创建订单-1)

[10.6 编辑订单](#编辑订单)

[10.7 飞手所属团队列表](#飞手所属团队列表)

[10.8 订单申请](#订单申请)

[10.9 我的订单列表](#我的订单列表)

[10.10 订单申请列表](#订单申请列表-1)

[10.11 订单地块列表](#订单地块列表)

[10.12 订单地块详情](#订单地块详情-1)

[10.13 修改订单申请审核状态](#修改订单申请审核状态)

[10.14 农药列表](#农药列表-1)

[10.15 农作物列表](#农作物列表)

[10.16 参与团队列表](#参与团队列表-1)

[10.17 参与团队详情](#参与团队详情)

[10.18 订单作业设备列表接口](#订单作业设备列表接口-1)

[10.19 查询团队成员列表接口](#查询团队成员列表接口)

[10.20 分派队员接口](#分派队员接口)

[10.21 订单招募状态修改接口](#订单招募状态修改接口)

[10.22 分享订单](#分享订单)

[10.23 申请加入订单数量](#申请加入订单数量)

[11 基站管理APP部分接口](#基站管理app部分接口)

[11.1 消息列表](#消息列表-1)

[11.2 置消息已读](#置消息已读)

[11.3 千寻账号列表](#千寻账号列表)

[11.4 千寻账号删除](#千寻账号删除)

[11.5 基准点列表](#基准点列表)

[11.6 新增基准点](#新增基准点)

[11.7 删除基准点](#删除基准点)

[11.8 检测RTK更新](#检测rtk更新)

[11.9 检测APP更新](#检测app更新)

[11.10 RTK固件下载](#rtk固件下载)

[11.11 RTK列表](#rtk列表)

[12 测绘APP部分接口](#测绘app部分接口)

[12.1 新增地块](#新增地块)

[12.2 地块列表](#地块列表)

[12.3 地块列表](#地块详细信息)

[12.4 删除地块](#删除地块)

[12.4 未完成任务列表](#未完成任务列表)

[12.5 历史任务列表](#历史任务列表)

[12.6 修改任务状态](#修改任务状态)

[12.7 获取禁飞区](#获取禁飞区)

[13 作业APP部分接口](#作业app部分接口)

[13.1 获取附近的任务列表](#获取附近的任务列表)

[13.2 历史任务列表](#历史任务列表)

[13.3 任务状态切换](#任务状态切换)

[13.4 任务详情](#任务详情)

[13.5 地块作业信息下载](#地块作业信息下载)

[13.6 地块作业信息上传](#地块作业信息上传)

[13.7 架次轨迹信息上传](#架次轨迹信息上传)

用户鉴权部分接口
================

修改密码
-------

### 程序描述

修改密码。

### 功能

修改密码。

### 性能

网络环境稳定的情况下10秒内响应

### 请求方式

>   POST

### 请求地址

>   /api/userForApp/updatePasswordByCodeCheck

### 输入

>   格式: FORM表单

>   列表:

| 参数名           | 类型   | 中文意义           | 说明            |
|------------------|--------|--------------------|-----------------|
| phone            | String | 用户手机号         |                 |
| password         | String | 登录密码           |                 |
| textCode    | String | 手机验证码         |                 |


### 输出

>   格式: JSON

>   示例:

{"status":{"code":0,"reasonPhrase":"SUCCESS"}}


修改登录名
--------

### 程序描述

修改登录名。

### 功能

修改登录名。

### 性能

网络环境稳定的情况下10秒内响应

### 请求方式

>   POST

### 请求地址

>   /api/userForApp/updateLoginName

### 输入

>   格式: FORM表单

>   列表:

| 参数名           | 类型   | 中文意义           | 说明            |
|------------------|--------|--------------------|-----------------|
| phone            | String | 用户手机号         |                 |
| password         | String | 登录密码           |                 |

### 输出

>   格式: JSON

>   示例:

{"status":{"code":0,"reasonPhrase":"SUCCESS"}}


注册
----

### 程序描述

注册农业植保账号。

### 功能

注册农业植保账号。

### 性能

网络环境稳定的情况下10秒内响应

### 请求方式

>   POST

### 请求地址

>   /api/userForApp/register

### 输入

>   格式: FORM表单

>   列表:

| 参数名           | 类型   | 中文意义           | 说明            |
|------------------|--------|--------------------|-----------------|
| phone            | String | 用户手机号         |                 |
| password         | String | 登录密码           |                 |
| validate_code    | String | 手机验证码         |                 |
| is_validate_code | String | 是否校验手机验证码 | 1:校验;0:不校验 |

>   示例:

>   {

>   “phone”:”\*\*\*\*”,

>   “password” : ”\*\*\*\*”,

>   “is_validate_code”:”0”

>   }

### 输出

>   格式: JSON

>   示例:

{"status":{"code":0,"reasonPhrase":"SUCCESS"}}

注册手机号码校验
----------------

### 程序描述

校验注册手机号码是否已经注册。

### 功能

校验注册手机号码是否已经注册。

### 性能

网络环境稳定的情况下10秒内响应

### 请求方式

>   GET

### 请求地址

>   /checkmobile

### 输入

>   列表:

| 参数名 | 类型   | 中文意义   | 说明 |
|--------|--------|------------|------|
| mobile | String | 用户手机号 |      |

### 输出

>   格式: JSON

>   示例:

{"status":{"code":0,"reasonPhrase":"SUCCESS"},

“data”:”0”//0:未注册;1:已注册

}

登录
----

### 程序描述

登录认证。

### 功能

登录认证，返回登录用户信息。

### 性能

网络环境稳定的情况下10秒内响应

### 请求方式

>   POST

### 请求地址

>   /api/login?username=18410109583&password=123456&clientType=app&loginType=password

### 输入

| 参数名     | 类型   | 中文意义   | 说明               |
|------------|--------|------------|--------------------|
| username   | String | 用户手机号 |                    |
| password   | String | 登录密码   |                    |
| clientType | String | 客户端类型 | app/微信固定为app  |
| loginType  | String | 登录类型   | loginType=password |

### 输出

>   格式: JSON

>   列表:

| 参数名      | 类型   | 中文意义     | 说明 |
|-------------|--------|--------------|------|
| id          | String | 用户ID       |      |
| loginName   | String | 登录手机号   |      |
| name        | String | 用户名称     |      |
| mobileLogin | String | 是否手机登录 |      |
| appLogin    | String | 是否应用登录 |      |
| companyId   | String | 公司ID       |      |
| sessionid   | String | sessionid    |      |

>   示例:

>   {

>   "status": {

>   "code": 0,

>   "reasonPhrase": "SUCCESS"

>   },

>   "data": {

>   "id": "b7a714dfa46a4768b681b68c51f58e32",

>   "loginName": "18410109583",

>   "name": "18410109583",

>   "mobileLogin": true,

>   "appLogin": true,

>   "companyId": "6b0c8c4d6a124027931a7250908f070b",

>   "new": false,

>   "groundStation": true,

>   "sessionid": "5c1ddc6b2bb64cbda250b545f334ce07"

>   }

>   }

注销
----

### 程序描述

登出当前登录用户。

### 功能

登出当前登录用户。

### 性能

无

### 请求方式

>   GET

### 请求地址

/api/logout

### 消息头

| 参数名     | 类型   | 中文意义   | 说明      |
|------------|--------|------------|-----------|
| clientType | String | 客户端类型 | 固定值app |

### 输入

| 参数名 | 类型   | 中文意义   | 说明 |
|--------|--------|------------|------|
| number | String | 登录手机号 |      |

### 输出

>   格式: JSON

>   示例:

{ "status":{"code":0,"reasonPhrase":"SUCCESS"}}

个人信息部分接口
================

图片上传
--------

### 程序描述

保存上传图片。

### 功能

保存上传图片。

### 性能

无

### 请求方式

>   POST

### 请求地址

/api/base/file/upload

### 输入

>   格式: multipart/form_data

>   列表:

| 参数名 | 类型   | 中文意义     | 说明 |
|--------|--------|--------------|------|
| file   | String | 图片表单信息 |      |

###  输出

>   列表:

| 参数名 | 类型   | 中文意义 | 说明 |
|--------|--------|----------|------|
| url    | String | 图片URL  |      |

JSON格式数据如下：

{“status":”{code=0, reasonPhrase=SUCCESS}","data":"{

“url”:”\*\*\*\*\*”

}"}

实名认证
--------

### 程序描述

用户实名认证。

### 功能

用户实名认证

### 性能

无

### 请求方式

>   POST

### 请求地址

>   /api/userForApp/authentication

### 输入

>   格式: JSON

| 参数名             | 类型   | 中文意义      | 说明              |
|--------------------|--------|---------------|-------------------|
| number             | String | 登录手机号    |                   |
| user_name          | String | 用户名称      |                   |
| cert_type          | String | 证件类型      |                   |
| cert_no            | String | 证件号码      |                   |
| is_ident           | String | 认证标识      | 0:未认证;1:已认证 |
| cert_img_front_url | String | 证件照正面URL |                   |
| cert_img_back_url  | String | 证件照反面URL |                   |

### 输出

JSON格式数据如下：

{“status":”{code=0, reasonPhrase=SUCCESS}"}

查看个人信息
------------

### 程序描述

查看个人信息。

### 功能

查看个人信息。

### 性能

无

### 请求方式

>   GET

### 请求地址

/api/userForApp/getUserInfo

### 输入

>   列表:

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| user_id | String | 用户ID   |      |

### 输出

>   列表

| 参数名     | 类型   | 中文意义     | 说明 |
|------------|--------|--------------|------|
| user_id    | String | 用户ID       |      |
| number     | String | 手机号       |      |
| login_name | String | 登录账号     |      |
| user_name  | String | 用户名称     |      |
| logo_url   | String | 头像URL      |      |
| code_url   | String | 二维码URL    |      |
| signature  | String | 个性签名     |      |
| email      | String | 电子邮箱地址 |      |
| user_type  | String | 电子邮箱地址 |      |
| team_list  | Array  | 团队信息列表 |      |

团队列表

| id            | String | 植保队用户关系表ID   |                |
|---------------|--------|----------------------|----------------|
| user_id       | String | 用户id               |                |
| team_id       | String | 植保队id             |                |
| team_name     | String | 植保队名称           |                |
| team_logo_url | String | 植保队logo           |                |
| current_flag  | String | 是否为当前植保队标记 | 0:否;1:是      |
| role_flag     | String | 在团队中的角色标识   | 0:队员;1:队长; |

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}",

"data":{

"user_id":"\*\*\*",

>   "number":"\*\*\*",

>   "login_name":"\*\*\*",

>   "user_name":"\*\*\*",

>   "logo_url":"\*\*\*",

>   "code_url":"\*\*\*",

>   "signature":"\*\*\*",

>   "email":"\*\*\*",

>   "team_list":[{

>   "id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "team_logo_url":"\*\*\*",

>   "current_flag":"\*\*\*",

>   "role_flag":"\*\*\*"

>   },{

>   "id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "team_logo_url":"\*\*\*",

>   "current_flag":"\*\*\*",

>   "role_flag":"\*\*\*"

>   }]

>   }}

修改电话
--------

### 程序描述

编辑个人信息。

### 功能

编辑个人信息。

### 性能

无

### 请求方式

>   POST

### 请求地址

>   /api/userForApp/updatePhoneNumber

### 输入

>   格式: JSON

>   列表:

| 参数名  | 类型   | 中文意义   | 说明 |
|---------|--------|------------|------|
| user_id | String | 用户ID     |      |
| number  | String | 登录手机号 |      |

### 输出

JSON格式数据如下：

{“status":”{code=0, reasonPhrase=SUCCESS}"}

查询用户所在植保队列表
----------------------

### 程序描述

查询用户所在植保队列表。

### 功能

根据用户ID查询用户所属植保队列表

### 性能

无

### 请求方式

>   GET

### 请求地址

>   /api/teamFlyer/findTeamsByUser/{user_id}

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| user_id | String | 用户ID   |      |

### 输出

>   列表

| 参数名        | 类型   | 中文意义             | 说明           |
|---------------|--------|----------------------|----------------|
| user_id       | String | 用户id               |                |
| team_id       | String | 植保队id             |                |
| team_name     | String | 植保队名称           |                |
| team_logo_url | String | 植保队logo           |                |
| current_flag  | String | 是否为当前植保队标记 | 0:否;1:是      |
| role_flag     | String | 在团队中的角色标识   | 0:队员;1:队长; |

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":{

"list":[{

>   "user_id":"\*\*\*",

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "team_logo_url":"\*\*\*",

>   "current_flag":"\*\*\*",

>   "role_flag":"\*\*\*"

>   },{

>   "user_id":"\*\*\*",

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "team_logo_url":"\*\*\*",

>   "current_flag":"\*\*\*",

>   "role_flag":"\*\*\*"

>   }]

}}

选择当前团队
------------

### 程序描述

从团队列表中选择当前植保队。

### 功能

从团队列表中选择当前植保队。

### 性能

无

### 请求方式

>   GET

### 请求地址

>   /api/teamFlyer/selectTeam/{team_id}/{user_id}

### 输入

| 参数名  | 类型   | 中文意义   | 说明 |
|---------|--------|------------|------|
| user_id | String | 用户ID     |      |
| team_id | String | 当前团队ID |      |

### 输出

| 参数名        | 类型   | 中文意义             | 说明           |
|---------------|--------|----------------------|----------------|
| team_id       | String | 植保队id             |                |
| team_name     | String | 植保队名称           |                |
| team_logo_url | String | 植保队logo           |                |
| current_flag  | String | 是否为当前植保队标记 | 0:否;1:是      |
| role_flag     | String | 用户在团队中的角色   | 0:队员;1:队长; |

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}",

"data":{

"team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "team_logo_url":"\*\*\*",

>   "current_flag":"\*\*\*",

"role_flag": 1 //0:队员;1:队长;2副队长…

}}

我的执照列表
------------

### 程序描述

查询用户持有执照列表。

### 功能

查询用户持有执照列表。

### 性能

无

### 请求方式

>   GET

### 请求地址

>   /api/flyerLicense/findUserLicense

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| user_id | String | 用户ID   |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名      | 类型   | 中文意义    | 说明 |
|-------------|--------|-------------|------|
| id          | String | 主键        |      |
| user_id     | String | 用户ID      |      |
| name        | String | 执照名称    |      |
| type        | String | 执照类型    |      |
| code        | String | 执照代码    |      |
| license_url | String | 执照照片URL |      |
| start_time  | String | 生效时间    |      |
| end_time    | String | 失效时间    |      |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

>   "list":[{

>   "id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "name":"\*\*\*",

>   "type":"\*\*\*",

>   "code":"\*\*\*",

>   "license_url":"\*\*\*",

>   "start_time":"\*\*\*",

>   "end_time":"\*\*\*"

>   },{

>   "id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "name":"\*\*\*",

>   "type":"\*\*\*",

>   "code":"\*\*\*",

>   "license_url":"\*\*\*",

>   "start_time":"\*\*\*",

>   "end_time":"\*\*\*"

>   }]

>   }

}

设置地址
--------

### 程序描述

设置个人通讯地址。

### 功能

设置个人通讯地址。

### 性能

无

### 请求方式

>   POST

### 请求地址

>   /api/userForApp/updateUserAddress

### 输入

>   格式: JSON

>   列表:

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| id      | String | 用户ID   |      |
| address | String | 通讯地址 |      |

### 输出

JSON格式数据如下：

{“status":”{code=0, reasonPhrase=SUCCESS}"}

设置发票抬头
------------

### 程序描述

设置发票抬头。

### 功能

设置发票抬头。

### 性能

无

### 请求方式

>   POST

### 输入

>   格式: JSON

>   列表:

| 参数名          | 类型   | 中文意义 | 说明               |
|-----------------|--------|----------|--------------------|
| user_id         | String |          | 登录用户ID         |
| company_name    | String |          | 公司名称(发票抬头) |
| company_address | String |          | 公司地址           |
| type            | String |          | 发票类型           |
| tax_no          | String |          | 税号               |

### 输出

JSON格式数据如下：

{“status":”{code=0, reasonPhrase=SUCCESS}"}

申请发票
--------

### 程序描述

申请发票。

### 功能

申请发票。

### 性能

无

### 请求方式

>   POST

### 输入

>   格式: JSON

>   列表:

| 参数名 | 类型 | 中文意义 | 说明 |
|--------|------|----------|------|
|        |      |          |      |
|        |      |          |      |

### 输出

JSON格式数据如下：

{“status":”{code=0, reasonPhrase=SUCCESS}"}

>   列表:

| 参数名 | 类型 | 中文意义 | 说明 |
|--------|------|----------|------|


创建地址
----------------

### 程序描述

创建用户通讯地址。

### 功能

创建用户通讯地址。

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名         | 类型    | 中文意义                 | 说明 |
|----------------|---------|--------------------------|------|
| user_id        | varchar | 用户ID                   |      |
| receiver       | varchar | 收货人名称               |      |
| connact_no     | varchar | 联系电话                 |      |
| area_id        | varchar | 行政区ID                 |      |
| address_detail | varchar | 详细地址                 |      |
| default_flag   | varchar | 是否是默认地址:0:否;1:是 |      |
| zip_code       | varchar | 邮编                     |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}"}

更新地址
----------------

### 程序描述

创建用户通讯地址。

### 功能

创建用户通讯地址。

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名         | 类型    | 中文意义                 | 说明 |
|----------------|---------|--------------------------|------|
| id             | varchar | 消息主键                 |      |
| receiver       | varchar | 收货人名称               |      |
| connact_no     | varchar | 联系电话                 |      |
| area_id        | varchar | 行政区ID                 |      |
| address_detail | varchar | 详细地址                 |      |
| default_flag   | varchar | 是否是默认地址:0:否;1:是 |      |
| zip_code       | varchar | 邮编                     |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}"}

查询地址列表
--------------------

### 程序描述

根据用户ID查询用户通讯地址列表。

### 功能

根据用户ID查询用户通讯地址列表。

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| user_id | String | 用户ID   |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名         | 类型    | 中文意义                 | 说明 |
|----------------|---------|--------------------------|------|
| id             | varchar | 消息主键                 |      |
| user_id        | varchar | 用户ID                   |      |
| receiver       | varchar | 收货人名称               |      |
| connact_no     | varchar | 联系电话                 |      |
| area_id        | varchar | 行政区ID                 |      |
| address_detail | varchar | 详细地址                 |      |
| default_flag   | varchar | 是否是默认地址:0:否;1:是 |      |
| zip_code       | varchar | 邮编                     |      |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

>   "list":[{

>   "id":"\*\*\*",

>   " user_id ":"\*\*\*",

>   " receiver ":"\*\*\*",

>   " connact_no ":"\*\*\*",

>   " area_id:"\*\*\*",

>   " default_flag ":"\*\*\*",

>   " zip_code ":"\*\*\*",

>   " address_detail ":"0"

>   },{

>   "id":"\*\*\*",

>   " user_id ":"\*\*\*",

>   " receiver ":"\*\*\*",

>   " connact_no ":"\*\*\*",

>   " area_id:"\*\*\*",

>   " default_flag ":"\*\*\*",

>   " zip_code ":"\*\*\*",

>   " address_detail ":"0"

>   }]

>   }

}

查询地址详情
--------------------

### 程序描述

根据ID查询用户通讯地址详情。

### 功能

根据ID查询用户通讯地址详情。

### 性能

无

### 请求方式

>   GET

### 输入

| 参数名 | 类型   | 中文意义       | 说明 |
|--------|--------|----------------|------|
| id     | String | 通讯地址主键ID |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名         | 类型    | 中文意义                 | 说明 |
|----------------|---------|--------------------------|------|
| id             | varchar | 消息主键                 |      |
| user_id        | varchar | 用户ID                   |      |
| receiver       | varchar | 收货人名称               |      |
| connact_no     | varchar | 联系电话                 |      |
| area_id        | varchar | 行政区ID                 |      |
| address_detail | varchar | 详细地址                 |      |
| default_flag   | varchar | 是否是默认地址:0:否;1:是 |      |
| zip_code       | varchar | 邮编                     |      |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

>   "id":"\*\*\*",

>   " user_id ":"\*\*\*",

>   " receiver ":"\*\*\*",

>   " connact_no ":"\*\*\*",

>   " area_id:"\*\*\*",

>   " default_flag ":"\*\*\*",

>   " zip_code ":"\*\*\*",

>   " address_detail ":"0"

>   }

}

删除地址
----------------

### 程序描述

根据ID查询用户通讯地址详情。

### 功能

根据ID查询用户通讯地址详情。

### 性能

无

### 请求方式

>   GET

### 输入

| 参数名 | 类型   | 中文意义       | 说明 |
|--------|--------|----------------|------|
| id     | String | 通讯地址主键ID |      |

### 输出

示例:

{ "status":{"code":0,"reasonPhrase":"SUCCESS"}}

用户头像上传(未登记)
-------------------

消息部分接口
============

设置消息提醒
------------

### 程序描述

设置消息提醒。

### 功能

设置消息提醒。

### 性能

无

### 请求方式

>   POST

### 请求地址

>   /api/userForApp/setMessageFlag

### 输入

>   格式: JSON

>   列表:

| 参数名       | 类型   | 中文意义 | 说明                         |
|--------------|--------|----------|------------------------------|
| user_id      | String |          | 登录用户ID                   |
| message_flag | String |          | 接收消息标识:0:接收;1:不接收 |

### 输出

JSON格式数据如下：

{“status":”{code=0, reasonPhrase=SUCCESS}"}

未读消息总数
------------

### 程序描述

分类(订单、联盟、团队、设备)查询未读消息总数。

### 功能

分类(订单、联盟、团队、设备)查询未读消息总数。

### 性能

无

### 请求方式

>   POST

### 请求地址

>   /api/plantInfoMessage/getUnreadMessageCount

### 输入

| 参数名       | 类型   | 中文意义     | 说明                                                |
|--------------|--------|--------------|-----------------------------------------------------|
| user_id      | String | 用户ID       |                                                     |
| message_type | String | 消息类型     | 0:订单;1:联盟;2:团队;3:设备                         |
| receive_type | String | 消息接收类型 | 接收类型(消息接收类型 1基站; 2测绘; 3作业 ;4微信端) |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"20"}

订单消息列表
------------

### 程序描述

分页查询用户订单消息列表。

### 功能

分页查询用户订单消息列表。

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名       | 类型   | 中文意义                      | 说明 |
|--------------|--------|-------------------------------|------|
| user_id      | String | 用户ID                        |      |
| page_count   | String | 每页数量                      |      |
| current_page | String | 当前页码                      |      |
| order_by     | String | 当前排序依据，默认为read_flag |      |
| order_model  | String | 当前排序方式，默认为1(desc)   |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名      | 类型   | 中文意义     | 说明          |
|-------------|--------|--------------|---------------|
| id          | String | 消息ID       |               |
| user_id     | String | 用户ID       |               |
| order_id    | String | 订单ID       |               |
| order_name  | String | 订单名称     |               |
| type        | String | 消息类型     |               |
| union_id    | String | 联盟ID       |               |
| union_name  | String | 联盟名称     |               |
| team_id     | String | 植保队ID     |               |
| team_name   | String | 植保队名称   |               |
| source_id   | String | 消息来源ID   |               |
| source_name | String | 消息来源名称 |               |
| read_flag   | String | 已读标识     | 0:未读;1:已读 |
| event_type  | String | 事件类型     |               |
| message     | String | 消息内容     |               |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

"total": 20,

>   "list":[{

>   "id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "order_id":"\*\*\*",

>   "order_name":"\*\*\*",

>   "type":"\*\*\*",

>   "union_id":"\*\*\*",

>   "union_name":"\*\*\*",

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "source_id":"\*\*\*",

>   "source_name":"\*\*\*",

>   "read_flag":"\*\*\*",

>   "event_type":"\*\*\*",

>   "message":"\*\*\*"

>   },{

>   "id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "order_id":"\*\*\*",

>   "order_name":"\*\*\*",

>   "type":"\*\*\*",

>   "union_id":"\*\*\*",

>   "union_name":"\*\*\*",

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "source_id":"\*\*\*",

>   "source_name":"\*\*\*",

>   "read_flag":"\*\*\*",

>   "event_type":"\*\*\*",

>   "message":"\*\*\*"

>   }]

>   }

}

团队消息列表
------------

### 程序描述

分页查询用户团队消息列表。

### 功能

分页查询用户团队消息列表。

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名       | 类型   | 中文意义                      | 说明 |
|--------------|--------|-------------------------------|------|
| user_id      | String | 用户ID                        |      |
| page_count   | String | 每页数量                      |      |
| current_page | String | 当前页码                      |      |
| order_by     | String | 当前排序依据，默认为read_flag |      |
| order_model  | String | 当前排序方式，默认为1(desc)   |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名      | 类型   | 中文意义     | 说明          |
|-------------|--------|--------------|---------------|
| id          | String | 消息ID       |               |
| user_id     | String | 用户ID       |               |
| order_id    | String | 订单ID       |               |
| order_name  | String | 订单名称     |               |
| type        | String | 消息类型     |               |
| union_id    | String | 联盟ID       |               |
| union_name  | String | 联盟名称     |               |
| team_id     | String | 植保队ID     |               |
| team_name   | String | 植保队名称   |               |
| source_id   | String | 消息来源ID   |               |
| source_name | String | 消息来源名称 |               |
| read_flag   | String | 已读标识     | 0:未读;1:已读 |
| event_type  | String | 事件类型     |               |
| message     | String | 消息内容     |               |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{"total": 20,

>   "list":[{

>   "id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "order_id":"\*\*\*",

>   "order_name":"\*\*\*",

>   "type":"\*\*\*",

>   "union_id":"\*\*\*",

>   "union_name":"\*\*\*",

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "source_id":"\*\*\*",

>   "source_name":"\*\*\*",

>   "read_flag":"\*\*\*",

>   "event_type":"\*\*\*",

>   "message":"\*\*\*"

>   },{

>   "id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "order_id":"\*\*\*",

>   "order_name":"\*\*\*",

>   "type":"\*\*\*",

>   "union_id":"\*\*\*",

>   "union_name":"\*\*\*",

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "source_id":"\*\*\*",

>   "source_name":"\*\*\*",

>   "read_flag":"\*\*\*",

>   "event_type":"\*\*\*",

>   "message":"\*\*\*"

>   }]

>   }

}

联盟消息列表
------------

### 程序描述

分页查询用户联盟消息列表。

### 功能

分页查询用户联盟消息列表。

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名       | 类型   | 中文意义                      | 说明 |
|--------------|--------|-------------------------------|------|
| user_id      | String | 用户ID                        |      |
| page_count   | String | 每页数量                      |      |
| current_page | String | 当前页码                      |      |
| order_by     | String | 当前排序依据，默认为read_flag |      |
| order_model  | String | 当前排序方式，默认为1(desc)   |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名      | 类型   | 中文意义     | 说明          |
|-------------|--------|--------------|---------------|
| id          | String | 消息ID       |               |
| user_id     | String | 用户ID       |               |
| order_id    | String | 订单ID       |               |
| order_name  | String | 订单名称     |               |
| type        | String | 消息类型     |               |
| union_id    | String | 联盟ID       |               |
| union_name  | String | 联盟名称     |               |
| team_id     | String | 植保队ID     |               |
| team_name   | String | 植保队名称   |               |
| source_id   | String | 消息来源ID   |               |
| source_name | String | 消息来源名称 |               |
| read_flag   | String | 已读标识     | 0:未读;1:已读 |
| event_type  | String | 事件类型     |               |
| message     | String | 消息内容     |               |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{"total": 20,

>   "list":[{

>   "id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "order_id":"\*\*\*",

>   "order_name":"\*\*\*",

>   "type":"\*\*\*",

>   "union_id":"\*\*\*",

>   "union_name":"\*\*\*",

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "source_id":"\*\*\*",

>   "source_name":"\*\*\*",

>   "read_flag":"\*\*\*",

>   "event_type":"\*\*\*",

>   "message":"\*\*\*"

>   },{

>   "id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "order_id":"\*\*\*",

>   "order_name":"\*\*\*",

>   "type":"\*\*\*",

>   "union_id":"\*\*\*",

>   "union_name":"\*\*\*",

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "source_id":"\*\*\*",

>   "source_name":"\*\*\*",

>   "read_flag":"\*\*\*",

>   "event_type":"\*\*\*",

>   "message":"\*\*\*"

>   }]

>   }

}

设备消息列表
------------

### 程序描述

分页查询用户设备消息列表。

### 功能

分页查询用户设备消息列表。

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名       | 类型   | 中文意义                      | 说明 |
|--------------|--------|-------------------------------|------|
| user_id      | String | 用户ID                        |      |
| page_count   | String | 每页数量                      |      |
| current_page | String | 当前页码                      |      |
| order_by     | String | 当前排序依据，默认为read_flag |      |
| order_model  | String | 当前排序方式，默认为1(desc)   |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名      | 类型   | 中文意义     | 说明          |
|-------------|--------|--------------|---------------|
| id          | String | 消息ID       |               |
| user_id     | String | 用户ID       |               |
| uav_id      | String | 设备ID       |               |
| uav_name    | String | 设备名称     |               |
| type        | String | 消息类型     |               |
| union_id    | String | 联盟ID       |               |
| union_name  | String | 联盟名称     |               |
| team_id     | String | 植保队ID     |               |
| team_name   | String | 植保队名称   |               |
| source_id   | String | 消息来源ID   |               |
| source_name | String | 消息来源名称 |               |
| read_flag   | String | 已读标识     | 0:未读;1:已读 |
| event_type  | String | 事件类型     |               |
| message     | String | 消息内容     |               |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{"total": 20,

>   "list":[{

>   "id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "uav_id":"\*\*\*",

>   "uav_name":"\*\*\*",

>   "type":"\*\*\*",

>   "union_id":"\*\*\*",

>   "union_name":"\*\*\*",

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "source_id":"\*\*\*",

>   "source_name":"\*\*\*",

>   "read_flag":"\*\*\*",

>   "event_type":"\*\*\*",

>   "message":"\*\*\*"

>   },{

>   "id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "uav_id":"\*\*\*",

>   "uav_name":"\*\*\*",

>   "type":"\*\*\*",

>   "union_id":"\*\*\*",

>   "union_name":"\*\*\*",

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "source_id":"\*\*\*",

>   "source_name":"\*\*\*",

>   "read_flag":"\*\*\*",

>   "event_type":"\*\*\*",

>   "message":"\*\*\*"

>   }]

>   }

}

消息列表
--------

### 程序描述

根据用户ID消息类型接收类型分页查询用户消息列表。

后台返回列表后自动将消息置为已读.

### 功能

根据用户ID消息类型接收类型分页查询用户消息列表。

后台返回列表后自动将消息置为已读.

### 性能

无

### 请求方式

>   POST

### 请求地址

>   /api/plantInfoMessage/getMessage

### 输入

| 参数名       | 类型   | 中文意义                                          | 说明 |
|--------------|--------|---------------------------------------------------|------|
| user_id      | String | 用户ID                                            |      |
| message_type | String | 消息类型(1订单,2团队,3联盟,4设备)                 |      |
| receive_type | String | 接收类型(消息接收类型 1基站 2测绘 3作业 4微信端)  |      |
| page_count   | String | 每页数量                                          |      |
| current_page | String | 当前页码                                          |      |
| order_by     | String | 当前排序依据，默认为read_flag升序,create_date降序 |      |
| order_model  | String | 当前排序方式，默认为1(desc)                       |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名       | 类型      | 中文意义                                         | 说明                                             |
|--------------|-----------|--------------------------------------------------|--------------------------------------------------|
| id           | varchar   | 主键                                             | 主键                                             |
| user_id      | varchar   | 登录用户ID                                       | 登录用户ID                                       |
| type         | int       | 消息类型(1订单,2团队,3联盟,4设备)                | 消息类型(1订单,2团队,3联盟,4设备)                |
| source_id    | varchar   | 消息来源ID                                       | 消息来源ID                                       |
| message      | varchar   | 消息内容                                         | 消息内容                                         |
| read_flag    | int       | 已读标识:0:未读;1:已读                           | 已读标识:0:未读;1:已读                           |
| receive_type | varchar   | 接收类型(消息接收类型 1基站 2测绘 3作业 4微信端) | 接收类型(消息接收类型 1基站 2测绘 3作业 4微信端) |
| create_date  | timestamp |                                                  | 创建时间                                         |
| system_time  | timestamp | 系统时间戳ss                                     |                                                  |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

"total": 20,

"system_time":"系统时间",

>   "list":[{

>   "id":"\*\*\*",

>   "user_id":"\*\*\*",

>   " type ":"\*\*\*",

>   " source_id ":"\*\*\*",

>   " message ":"\*\*\*",

>   " read_flag ":"\*\*\*",

>   " create_date ":"\*\*\*",

>   " receive_type ":"\*\*\*"

>   },{

>   "id":"\*\*\*",

>   "user_id":"\*\*\*",

>   " type ":"\*\*\*",

>   " source_id ":"\*\*\*",

>   " message ":"\*\*\*",

>   " read_flag ":"\*\*\*",

>   " create_date ":"\*\*\*",

>   " receive_type ":"\*\*\*"

>   }]

>   }

}

团队管理部分接口
================

创建植保队
----------

### 程序描述

创建植保队。

### 功能

创建植保队。

### 性能

无

### 请求方式

>   POST

### 请求地址

>    api/protection/save


### 输入

| 参数名    | 类型   | 中文意义   | 说明 |
|-----------|--------|------------|------|
| user_id   | String | 用户id     |      |
| team_name | String | 植保队名称 |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS},data:{ team_id":"***"}"}

团队列表
--------

### 程序描述

查询用户所在团队列表。

### 功能

查询用户所在团队列表。

### 性能

无

### 请求方式

>   GET

### 请求地址

>    api/protection/findTeamList

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| user_id | String | 用户ID   |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名        | 类型   | 中文意义       | 说明                        |
|---------------|--------|----------------|-----------------------------|
| user_id       | String | 用户ID         |                             |
| team_id       | String | 团队ID         |                             |
| team_name     | String | 团队名称       |                             |
| team_logo_url | String | 团队logo URL   |                             |
| leader_id     | String | 队长ID         |                             |
| leader_name   | String | 队长名称       |                             |
| member_count  | String | 队员数量       |                             |
| current_flag  | String | 当前植保队标记 | 0:非当前植保队;1:当前植保队 |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

>   "list":[{

>   "user_id":"\*\*\*",

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "team_logo_url":"\*\*\*",

>   "apply_count":"\*\*\*",

>   "leader_id":"\*\*\*",

>   "leader_name":"\*\*\*",

>   "member_count":"\*\*\*",

>   "current_flag":"\*\*\*"

>   },{

>   "user_id":"\*\*\*",

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "team_logo_url":"\*\*\*",

>   "apply_count":"\*\*\*",

>   "leader_id":"\*\*\*",

>   "leader_name":"\*\*\*",

>   "member_count":"\*\*\*",

>   "current_flag":"\*\*\*"

>   }]

>   }

}

植保队详情
----------

### 程序描述

根据植保队ID查看植保队详情。

### 功能

根据植保队ID查看植保队详情.

### 性能

无

### 请求方式

>   GET

### 请求地址

>    api/protection/getTeamInfo

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| team_id | String | 植保队ID |      |

### 输出

JSON格式数据如下：

{“status":”{code=0, reasonPhrase=SUCCESS}","data":"{}"}

data:List\<TeamInfo \>，其中FORM BEAN类名：TeamInfo

| 参数名        | 类型   | 中文意义             | 说明                             |
|---------------|--------|----------------------|----------------------------------|
| team_id       | String | 植保队id             |                                  |
| team_name     | String | 植保队名称           |                                  |
| team_logo_url | String | 植保队logo           |                                  |
| current_flag  | String | 是否为当前植保队标记 | 0:否;1:是                        |
| user_count    | String | 队员数量             |                                  |
| order_count   | String | 团队订单数量         |                                  |
| user_list     | Array  | 成员列表             |                                  |
| apply_count   | String | 申请入队人数         |                                  |
| status        | String | 认证状态             |  0.未认证，1.认证中， 2.认证通过 |

成员列表

| id        | String | 用户ID     |           |
|-----------|--------|------------|-----------|
| name      | String | 用户姓名   |           |
|       | String | 用户姓名   |           |
| is_leader | String | 是否是队长 | 0:否;1:是 |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

"team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "team_logo_url":"\*\*\*",

>   "current_flag":"\*\*\*",

>   "apply_count":"\*\*\*",

>   "user_count":"\*\*\*",

>   "order_count":"\*\*\*",

>   "status":"\*\*\*",

>   "user_list":

>   [{

"id":"\*\*\*\*",

>   "name":"\*\*\*\*",

>   "is_leader":"1"

},

{

"id":"\*\*\*\*",

>   "name":"\*\*\*\*",

>   "is_leader":"0"

}

]}

}

团队申请列表
------------

### 程序描述

查询团队申请人员数量列表。

### 功能

查询团队申请人员数量列表。

### 性能

无

### 请求方式

>   GET

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| user_id | String | 用户ID   |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名        | 类型   | 中文意义     | 说明 |
|---------------|--------|--------------|------|
| team_id       | String | 团队ID       |      |
| team_name     | String | 团队名称     |      |
| team_logo_url | String | 团队logo URL |      |
| apply_count   | String | 待审核数量   |      |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

>   "list":[{

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "team_logo_url":"\*\*\*",

>   "apply_count":"0"

>   },{

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "team_logo_url":"\*\*\*",

>   "apply_count":"0"

>   }]

>   }

}

申请加入团队列表
----------------

### 程序描述

查询申请加入团队人员名单列表。

### 功能

查询申请加入团队人员名单列表。

### 性能

无

### 请求方式

>   POST

### 请求地址

>    api/protection/findApplyList


### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| team_id | String | 团队ID   |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名       | 类型   | 中文意义       | 说明                   |
|--------------|--------|----------------|------------------------|
| id           | String | 申请ID         |                        |
| team_id      | String | 申请加入团队ID |                        |
| user_id      | String | 飞手ID         |                        |
| user_name    | String | 飞手姓名       |                        |
| work_acreage | String | 作业经验       | 单位(亩)               |
| apply_status | String | 申请状态       | 0:待审核;1:通过;2:拒绝 |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

>   "list":[{

>   "id":"\*\*\*",

>   "team_id":"\*\*\*",

>   "flyer_id":"\*\*\*",

>   "flyer_name":"\*\*\*",

>   "work_acreage":"\*\*\*",

>   "apply_status":"0"

>   },{

>   "id":"\*\*\*",

>   "team_id":"\*\*\*",

>   "flyer_id":"\*\*\*",

>   "flyer_name":"\*\*\*",

>   "work_acreage":"\*\*\*",

>   "apply_status":"0"

>   }]

>   }

}

申请审批
--------

### 程序描述

审批加入申请。

### 功能

审批加入申请。

### 性能

无

### 请求方式

>   POST

### 请求地址

>    api/protection/applyApproval


### 输入

| 参数名   | 类型   | 中文意义   | 说明         |
|----------|--------|------------|--------------|
| apply_id | String | 申请加入ID |              |
| status   | int    | 审批状态   | 1:同意2:拒绝 |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}"}

团队logo修改
------------

### 程序描述

修改团队logo

### 功能

修改团队logo

### 性能

无

### 请求方式

>   POST

### 请求地址

>    api/protection/modifyLogo

### 输入

| 参数名   | 类型   | 中文意义 | 说明          |
|----------|--------|----------|---------------|
| team_id  | String | 植保队ID |               |
| logo_url | String | 审核状态 | 3:拒绝;1:同意 |

>   示例:

>   {

>   "team_id":"\*\*\*\*\*",

>   "logo_url”: "\*\*\*\*"

}

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}"}

团队订单列表
--------------------

### 程序描述

查询团队订单列表信息。

### 功能

查询团队订单列表信息

### 性能

无

### 请求方式

>   POST

### 请求地址

>    api/protection/findTeamOrderList

### 输入

| 参数名       | 类型   | 中文意义                        | 说明                                                      |
|--------------|--------|---------------------------------|-----------------------------------------------------------|
| team_id      | String | 植保队ID                        |                                                           |
| current_page | String | 当前分页，默认为1               |                                                           |
| order_by     | String | 当前排序依据，默认为create_time |                                                           |
| order_model  | String | 当前排序方式，默认为1(desc)     |                                                           |
| page_count   | String | 每页数量，默认为10              |                                                           |
| search       | String | 根据订单名称搜索相应订单        |                                                           |
| status       | String | 订单状态                        | 0:我发布的;1:我申请的(默认为空表示查询全部)               |
| sub_status   | String | 分类状态                        | 0:招募中;1:停止招募;2:已完成; 0:待审核;1:进行中;2:已完成; |

>   示例:

>   {

>   “team_id”:”\*\*\*\*”,

>   “current_page” : 1,

>   “order_by”:” create_time”,

>   “order_model” : 1,

>   “page_count”: 10,

>   “search”:”\*\*\*\*”,

>   }

### 输出

>   格式: JSON

>   列表:

| 参数名               | 类型   | 中文意义             | 说明                                              |
|----------------------|--------|----------------------|---------------------------------------------------|
| id                   | String | 订单id               |                                                   |
| order_name           | String | 订单名称             |                                                   |
| order_acreage        | String | 订单面积             |                                                   |
| order_unit_price     | String | 每亩价格             |                                                   |
| order_pesticide_type | String | 用药类型             |                                                   |
| order_create_time    | Date   | 创建时间             | 返回数据是毫秒                                    |
| order_time_start     | Date   | 开始时间             | 返回数据是毫秒                                    |
| order_time_end       | Date   | 结束时间             | 返回数据是毫秒                                    |
| order_position       | String | 作业地址             |                                                   |
| location             | String | 地址坐标             | 返回地块经纬度,以’,’分割                          |
| publish_type         | int    | 发布类型             | 0:大厅;1联盟;2:团队;3:个人                        |
| union_id             | String | 联盟ID               | publish_type为1时不为空                           |
| team_id              | String | 团队ID               | publish_type为1或2时不为空                        |
| ident_flag           | Int    | 团队认证标识         | 0:团队不需要认证 1:团队需要认证                   |
| offer_lunch          | Int    | 提供工作餐标识       | 0:不提供;1:提供                                   |
| offer_hotel          | Int    | 提供住宿标识         | 0:不提供;1:提供                                   |
| offer_charge         | Int    | 提供电池充电标识     | 0:不提供;1:提供                                   |
| offer_logistics      | Int    | 提供后勤服务         | 0:不提供;1:提供                                   |
| offer_pesticide      | Int    | 需求方包药           | 0:不包;1:包                                       |
| show_phone           | Int    | 对外显示手机号标识   | 0:不显示;1:显示                                   |
| show_data            | Int    | 对外公开作业数据标识 | 0:不公开;1:公开                                   |
| order_require        | Int    | 作业要求标识         | 0:不需要;1:需要                                   |
| order_fly_height     | String | 飞行高度             | 单位:米                                           |
| order_fly_velocity   | String | 飞行速度             | 米/秒                                             |
| order_remark         | String | 备注                 |                                                   |
| user_number          | String | 联系方式             | 农户手机                                          |
| publish_status       | Int    | 订单发布状态         | 0:招募中;1:停止招募;2:已完成                      |
| city_id              | String | 地块行政区ID         | 市级行政区ID                                      |
| order_pesticide      | String | 农药名称             |                                                   |
| contact_name         | String | 联系人姓名           |                                                   |
| contact_phone        | String | 联系人手机号         |                                                   |
| order_crop           | String | 订单作物             |                                                   |
| order_crop_type      | String | 作物类型             |                                                   |
| apply_acreage        | String | 申请面积             |                                                   |
| apply_time           | Date   | 申请时间             | 返回数据是毫秒                                    |
| apply_status         | String | 申请状态             | 0:待审核;1:进行中(同意);2:已完成;3:拒绝;(默认为0) |
| mapping_acreage      | String | 测绘面积             |                                                   |
| work_acreage         | String | 作业面积             |                                                   |
| update_by            | String | 更新人               |                                                   |
| update_date          | String | 更新时间             |                                                   |

>   示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{"total":13,

"list":[{

"id":"\*\*\*",

>   "order_name":"\*\*\*",

>   "order_acreage":"\*\*\*",

>   "order_unit_price":"\*\*\*",

>   "order_pesticide_type":"\*\*\*",

>   "order_create_time":"\*\*\*",

>   "order_time_start":"\*\*\*",

>   "order_time_end":"\*\*\*",

>   "order_position":"\*\*\*",

>   "location":"\*\*\*",

>   "publish_type":"\*\*\*",

>   "union_id":"\*\*\*",

>   "team_id":"\*\*\*",

>   "ident_flag":"\*\*\*",

>   "offer_lunch":"\*\*\*",

>   "offer_hotel":"\*\*\*",

>   "offer_charge":"\*\*\*",

>   "offer_logistics":"\*\*\*",

>   "offer_pesticide":"\*\*\*",

>   "show_phone":"\*\*\*",

>   "show_data":"\*\*\*",

>   "order_require":"\*\*\*",

>   "order_fly_height":"\*\*\*",

>   "order_fly_velocity":"\*\*\*",

>   "order_remark":"\*\*\*",

>   "user_number":"\*\*\*",

>   "publish_status":"\*\*\*",

>   "city_id":"\*\*\*",

>   "order_pesticide":"\*\*\*",

>   "contact_name":"\*\*\*",

>   "contact_phone":"\*\*\*",

>   "order_crop":"\*\*\*",

>   "order_crop_type":"\*\*\*",

>   "mapping_acreage":"\*\*\*",

>   "work_acreage":"\*\*\*",

>   "update_by":"\*\*\*",

>   "update_date":"\*\*\*"

},

{

"id":"\*\*\*",

>   "order_name":"\*\*\*",

>   "order_acreage":"\*\*\*",

>   "order_unit_price":"\*\*\*",

>   "order_pesticide_type":"\*\*\*",

>   "order_create_time":"\*\*\*",

>   "order_time_start":"\*\*\*",

>   "order_time_end":"\*\*\*",

>   "order_position":"\*\*\*",

>   "location":"\*\*\*",

>   "publish_type":"\*\*\*",

>   "union_id":"\*\*\*",

>   "team_id":"\*\*\*",

>   "ident_flag":"\*\*\*",

>   "offer_lunch":"\*\*\*",

>   "offer_hotel":"\*\*\*",

>   "offer_charge":"\*\*\*",

>   "offer_logistics":"\*\*\*",

>   "offer_pesticide":"\*\*\*",

>   "show_phone":"\*\*\*",

>   "show_data":"\*\*\*",

>   "order_require":"\*\*\*",

>   "order_fly_height":"\*\*\*",

>   "order_fly_velocity":"\*\*\*",

>   "order_remark":"\*\*\*",

>   "user_number":"\*\*\*",

>   "publish_status":"\*\*\*",

>   "city_id":"\*\*\*",

>   "order_pesticide":"\*\*\*",

>   "contact_name":"\*\*\*",

>   "contact_phone":"\*\*\*",

>   "order_crop":"\*\*\*",

>   "order_crop_type":"\*\*\*",

>   "mapping_acreage":"\*\*\*",

>   "work_acreage":"\*\*\*",

>   "update_by":"\*\*\*",

>   "update_date":"\*\*\*"

}

]}

}

团队认证
--------

### 程序描述

更新团队认证信息。

### 功能

更新团队认证信息。

### 性能

无

### 请求方式

>   POST

### 请求地址

>    api/protection/teamApprove

### 输入

| 参数名       | 类型   | 中文意义 | 说明 |
|--------------|--------|----------|------|
| team_id      | String | 团队ID   |      |
| team_name    | String | 团队名称 |      |
| company_name | String | 公司名称 |      |
| manager_name | String | 法人姓名 |      |
| license_code | String | 执照代码 |      |
| license_url  | String | 执照URL  |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

植保队成员列表
--------------

### 程序描述

根据植保队ID查询团队成员列表。

### 功能

根据植保队ID查询团队成员列表。

### 性能

无

### 请求方式

>   GET

### 请求地址

>    api/protection/findMemberList

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| team_id | String | 植保队ID |      |

### 输出

JSON格式数据如下：

{“status":”{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名    | 类型   | 中文意义           | 说明           |
|-----------|--------|--------------------|----------------|
| team_id   | String | 团队ID             |                |
| user_id   | String | 成员ID             |                |
| user_name | String | 成员名称           |                |
| role_flag | String | 用户在团队中的角色 | 0:队员;1:队长; |

示例:

{“status": {code=0, reasonPhrase=SUCCESS},"data":{

>   "list" : [{

>   "team_id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "user_name ":"\*\*\*",

>   "role_flag":"\*\*\*"

>   },{

>   "team_id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "user_name ":"\*\*\*",

>   "role_flag":"\*\*\*"

}]}}

队长权限转让
------------

### 程序描述

转让队长权限

### 功能

转让队长权限

### 性能

无

### 请求方式

>   POST

### 请求地址

>    api/protection/roleTransfer

### 输入

| 参数名  | 类型   | 中文意义   | 说明 |
|---------|--------|------------|------|
| team_id | String | 植保队ID   |      |
| user_id | String | 转让用户ID |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

解散团队
--------

### 程序描述

解散团队。

### 功能

解散团队。

### 性能

无

### 请求方式

>   GET

### 请求地址

>    api/protection/dismissTeam

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| team_id | String | 植保队ID |      |

### 输出

JSON格式数据如下：

{“status":”{code=0, reasonPhrase=SUCCESS}","data":"{}"}

团队邀请
--------

### 程序描述

邀请加入团队二维码。

### 功能

邀请加入团队二维码。

### 性能

网络环境稳定的情况下10秒内响应

### 请求方式

>   GET

### 请求地址

>    api/protection/teamInvite


### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| team_id | String | 植保队id |      |

### 输出

>   格式: JSON

>   列表:

| 参数名       | 类型   | 中文意义   | 说明 |
|--------------|--------|------------|------|
| team_id      | String | 植保队id   |      |
| team_name    | String | 植保队名称 |      |
| manager_name | String | 队长名称   |      |
| manager_id   | String | 队长ID     |      |
| manager_no   | String | 队长手机号 |      |
| code_image   | String | 二维码图片 |      |

>   示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

"team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "manager_name":"\*\*\*",

>   "manager_id":"\*\*\*",

>   "manager_no":"\*\*\*",

>   "code_image":"\*\*\*"

}

}

队员当前任务列表
--------------------------

### 程序描述

查询队员在当前团队中的当前作业任务。

### 功能

查询队员在当前团队中的当前作业任务。

### 性能

网络环境稳定的情况下10秒内响应

### 请求方式

>   GET

### 请求地址

>    api/protection/findTaskList

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| team_id | String | 植保队id |      |
| user_id | String | 用户ID   |      |

### 输出

>   格式: JSON

>   列表:

| 参数名          | 类型   | 中文意义   | 说明 |
|-----------------|--------|------------|------|
| team_id         | String | 植保队id   |      |
| team_name       | String | 植保队名称 |      |
| order_id        | String | 订单ID     |      |
| order_name      | String | 订单名称   |      |
| order_address   | String | 订单地址   |      |
| crop_name       | String | 农作物名称 |      |
| mapping_acreage | String | 测绘面积   |      |
| work_acreage    | String | 作业面积   |      |
| update_by       | String | 更新人     |      |
| update_time     | String | 更新时间   |      |

>   示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{"list":[{

"team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "order_id":"\*\*\*",

>   "order_name":"\*\*\*",

>   "order_address":"\*\*\*",

>   "crop_name":"\*\*\*",

>   "mapping_acreage":"\*\*\*",

>   "work_acreage":"\*\*\*",

>   "update_by":"\*\*\*",

>   "update_time":"\*\*\*"

},{

"team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "order_id":"\*\*\*",

>   "order_name":"\*\*\*",

>   "order_address":"\*\*\*",

>   "crop_name":"\*\*\*",

>   "mapping_acreage":"\*\*\*",

>   "work_acreage":"\*\*\*",

>   "update_by":"\*\*\*",

>   "update_time":"\*\*\*"

}]

}

}

队员所在团队作业统计
------------------------------

### 程序描述

统计队员所在团队中的总作业面积、参与订单数量、作业地块数、飞行时长

### 功能

统计队员所在团队中的总作业面积、参与订单数量、作业地块数、飞行时长

### 性能

无

### 请求方式

>   POST

### 请求地址

>    api/protection/workStatistics

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| user_id | String | 用户ID   |      |
| team_id | String | 团队ID   |      |

JSON格式数据如下：

{

"user_id":"\*\*\*",

"team_id":"\*\*\*"

}

### 输出

>   列表:

| 参数名       | 类型   | 中文意义 | 说明      |
|--------------|--------|----------|-----------|
| user_id      | String | 用户id   |           |
| block_count  | String | 作业地块 | 单位:个   |
| work_acreage | String | 作业面积 | 单位:亩   |
| fly_time     | String | 飞行时长 | 单位:小时 |
| total_order  | String | 订单数量 | 单位:个   |
| team_id      | String | 团队ID   |           |

JSON格式数据如下：

{

>   "status":"{code=0, reasonPhrase=SUCCESS}",

>   "data":{

"user_id":"\*\*\*",

>   "total_acreage":"\*\*\*",

>   "mapping_acreage":"\*\*\*",

>   "total_time":"\*\*\*",

>   "total_order":"\*\*\*"

}

}

查询队员任务列表
--------------------------

### 程序描述

分页查询队员在当前团队中的历史作业任务列表。

### 功能

分页查询队员在当前团队中的历史作业任务列表。

### 性能

网络环境稳定的情况下10秒内响应

### 请求方式

>   GET

### 输入

| 参数名       | 类型   | 中文意义                        | 说明                   |
|--------------|--------|---------------------------------|------------------------|
| team_id      | String | 植保队id                        |                        |
| user_id      | String | 用户ID                          | 为空时查询团队任务列表 |
| page_count   | String | 每页数量                        |                        |
| current_page | String | 当前页码                        |                        |
| order_by     | String | 当前排序依据，默认为update_time |                        |
| order_model  | String | 当前排序方式，默认为1(desc)     |                        |
| crop_name    | String | 订单作物名称                    | 模糊查询               |
| date         | String | 查询日期                        |                        |
| area_name    | String | 订单地区名称                    | 模糊查询               |

### 输出

>   格式: JSON

>   列表:

| 参数名           | 类型   | 中文意义   | 说明 |
|------------------|--------|------------|------|
| team_id          | String | 植保队id   |      |
| team_name        | String | 植保队名称 |      |
| order_id         | String | 订单ID     |      |
| order_name       | String | 订单名称   |      |
| order_address    | String | 订单地址   |      |
| crop_name        | String | 农作物名称 |      |
| mapping_acreage  | String | 测绘面积   |      |
| work_acreage     | String | 作业面积   |      |
| update_by        | String | 更新人     |      |
| update_time      | String | 更新时间   |      |
| finished_percent | String | 完成率     |      |

>   示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{"total": 20,

"list":[{

"team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "order_id":"\*\*\*",

>   "order_name":"\*\*\*",

>   "order_address":"\*\*\*",

>   "crop_name":"\*\*\*",

>   "mapping_acreage":"\*\*\*",

>   "work_acreage":"\*\*\*",

>   "update_by":"\*\*\*",

>   "finished_percent":"\*\*\*",

>   "update_time":"\*\*\*"

},{

"team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "order_id":"\*\*\*",

>   "order_name":"\*\*\*",

>   "order_address":"\*\*\*",

>   "crop_name":"\*\*\*",

>   "mapping_acreage":"\*\*\*",

>   "work_acreage":"\*\*\*",

>   "update_by":"\*\*\*",

>   "finished_percent":"\*\*\*",

>   "update_time":"\*\*\*"

}]

}

}

团队认证详情
---------------------

### 程序描述

根据植保队ID查看植保队认证信息。

### 功能

根据植保队ID查看植保队认证信息。

### 性能

无

### 请求方式

>   GET

### 请求地址

>    api/protection/findTeamAuthenticationInfo

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| team_id | String | 植保队ID |      |

### 输出

JSON格式数据如下：

{“status":”{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名       | 类型   | 中文意义               | 说明                             |
|--------------|--------|------------------------|----------------------------------|
| team_id      | String | 植保队id               |                                  |
| team_name    | String | 植保队名称             |                                  |
| manager_name | String | 法定代表人姓名         |                                  |
| company_name | String | 公司名称               |                                  |
| license_code | String | 营业执照统一信用代码   |                                  |
| license_url  | String | 营业执照副本电子版地址 |                                  |
| status       | String | 认证状态               |  0.未认证，1.认证中， 2.认证通过 |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

"team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   " manager_name ":"\*\*\*",

>   " company_name ":"\*\*\*",

>   " license_code ":"\*\*\*",

>   " license_url ":"\*\*\*",

>   " status ":"\*\*\*"

}

申请加入植保队
--------------

### 程序描述

加入植保队申请。

### 功能

>   查询当前用户是否已认证,如未认证则提示用户进行实名认证,否则添加飞手植保队关系申请。

### 性能

无

### 请求方式

>   POST

### 请求地址

>    api/protection/applyJoin

### 输入

| 参数名  | 类型   | 中文意义       | 说明 |
|---------|--------|----------------|------|
| team_id | String | 申请加入团队ID |      |
| user_id | String | 用户ID         |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}"}

作业统计部分接口
==========================

团队作业统计
------------

### 程序描述

按年、月、日统计总作业面积、总时长、作业效率、完成订单数

### 功能

按年、月、日统计总作业面积、总时长、作业效率、完成订单数

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名  | 类型   | 中文意义 | 说明                                    |
|---------|--------|----------|-----------------------------------------|
| team_id | String | 团队ID   |                                         |
| date    | String | 查询日期 | 年: 2018;年月:2018_11;年月日:2018_11_11 |

JSON格式数据如下：

{

"team \_id":"\*\*\*",

"date":"\*\*\*"

}

### 输出

>   列表:

| 参数名        | 类型   | 中文意义   | 说明       |
|---------------|--------|------------|------------|
| team_id       | String | 用户id     |            |
| total_acreage | String | 总作业面积 | 单位:亩    |
| efficiency    | String | 效率       | 单位:亩/天 |
| total_time    | String | 总时长     | 单位:小时  |
| total_order   | String | 订单数量   | 单位:个    |

JSON格式数据如下：

{

>   "status":"{code=0, reasonPhrase=SUCCESS}",

>   "data":{

"team_id":"\*\*\*",

>   "total_acreage":"\*\*\*",

>   "efficiency":"\*\*\*",

>   "total_time":"\*\*\*",

>   "total_order":"\*\*\*"

}

}

团队作业记录统计
----------------

### 程序描述

按年统计团队作业信息。

### 功能

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名  | 类型   | 中文意义 | 说明     |
|---------|--------|----------|----------|
| team_id | String | 用户ID   |          |
| date    | String | 查询日期 | 年: 2018 |

JSON格式数据如下：

{

"team_id":"\*\*\*",

"date":"\*\*\*"

}

### 输出

>   列表:

| 参数名       | 类型   | 中文意义     | 说明    |
|--------------|--------|--------------|---------|
| team_id      | String | 用户id       |         |
| area_count   | String | 作业区域个数 | 单位个  |
| crop_count   | String | 作物类别数量 | 单位:种 |
| order_count  | String | 作业订单数量 |         |
| worker_count | String | 作业人员数量 |         |

JSON格式数据如下：

{

>   "status":"{code=0, reasonPhrase=SUCCESS}",

>   "data":{

>   "team_id":"\*\*\*",

>   "area_count":"\*\*\*",

>   "crop_count":"\*\*\*"

}

}

团队月作业曲线图
----------------

### 程序描述

按年查询每月作业面积。

### 功能

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名  | 类型   | 中文意义 | 说明     |
|---------|--------|----------|----------|
| team_id | String | 团队ID   |          |
| date    | String | 查询日期 | 年: 2018 |

JSON格式数据如下：

{

"user_id":"\*\*\*",

"date":"\*\*\*"

}

### 输出

>   列表:

| 参数名       | 类型   | 中文意义 | 说明    |
|--------------|--------|----------|---------|
| user_id      | String | 用户id   |         |
| month        | String | 月份     |         |
| work_acreage | String | 作业面积 | 单位:亩 |

JSON格式数据如下：

{

>   "status":"{code=0, reasonPhrase=SUCCESS}",

>   "data":{"list":[{

>   "user_id":"\*\*\*",

>   "month":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   },{

>   "user_id":"\*\*\*",

>   "month":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   }]

}

}

团队日作业曲线图
----------------

### 程序描述

按月查询每日作业面积。

### 功能

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名  | 类型   | 中文意义 | 说明          |
|---------|--------|----------|---------------|
| team_id | String | 团队ID   |               |
| date    | String | 查询日期 | 年月: 2018_11 |

JSON格式数据如下：

{

"team_id":"\*\*\*",

"date":"\*\*\*"

}

### 输出

>   列表:

| 参数名       | 类型   | 中文意义 | 说明    |
|--------------|--------|----------|---------|
| team_id      | String | 用户id   |         |
| day          | String | 日期     |         |
| work_acreage | String | 作业面积 | 单位:亩 |

JSON格式数据如下：

{

>   "status":"{code=0, reasonPhrase=SUCCESS}",

>   "data":{"list":[{

>   "team_id":"\*\*\*",

>   "day":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   },{

>   "team_id":"\*\*\*",

>   "day":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   }]

}

}

团队农作物柱状图
----------------

### 程序描述

按年统计每种农作物作业面积。

### 功能

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名  | 类型   | 中文意义 | 说明     |
|---------|--------|----------|----------|
| team_id | String | 用户ID   |          |
| date    | String | 查询日期 | 年: 2018 |

JSON格式数据如下：

{

"user_id":"\*\*\*",

"date":"\*\*\*"

}

### 输出

>   列表:

| 参数名       | 类型   | 中文意义   | 说明    |
|--------------|--------|------------|---------|
| user_id      | String | 用户id     |         |
| crop_name    | String | 农作物名称 |         |
| work_acreage | String | 作业面积   | 单位:亩 |

JSON格式数据如下：

{

>   "status":"{code=0, reasonPhrase=SUCCESS}",

>   "data":{"list":[{

>   "user_id":"\*\*\*",

>   "crop_name":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   },{

>   "user_id":"\*\*\*",

>   "crop_name":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   }]

}

}

团队地区作业记录
----------------

### 程序描述

按年统计每地区作业面积。

### 功能

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名  | 类型   | 中文意义 | 说明     |
|---------|--------|----------|----------|
| team_id | String | 团队ID   |          |
| date    | String | 查询日期 | 年: 2018 |

JSON格式数据如下：

{

" team_id":"\*\*\*",

"date":"\*\*\*"

}

### 输出

>   列表:

| 参数名       | 类型   | 中文意义       | 说明    |
|--------------|--------|----------------|---------|
| team_id      | String | 团队id         |         |
| city         | String | 市级行政区名称 |         |
| work_acreage | String | 作业面积       | 单位:亩 |
| province     | String | 省级行政区名称 |         |
| area_name    | String | 县级行政区名称 |         |

JSON格式数据如下：

{

>   "status":"{code=0, reasonPhrase=SUCCESS}",

>   "data":{"list":[{

>   "team_id":"\*\*\*",

>   "city ":"\*\*\*",

>   "province":"\*\*\*",

>   "area_name":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   },{

>   "team_id":"\*\*\*",

>   "city ":"\*\*\*",

>   "province":"\*\*\*",

>   "area_name":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   }]

}

}

团队设备作业统计
----------------

### 程序描述

按日期统计团队设备作业面积。

### 功能

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名  | 类型   | 中文意义 | 说明           |
|---------|--------|----------|----------------|
| team_id | String | 团队ID   |                |
| date    | String | 查询日期 | 年_月: 2018_11 |
| type    | String | 查询类型 | 0:年;1:月;2:日 |

JSON格式数据如下：

{

"team_id":"\*\*\*",

"date":"\*\*\*"

}

### 输出

>   列表:

| 参数名       | 类型   | 中文意义 | 说明    |
|--------------|--------|----------|---------|
| team_id      | String | 团队id   |         |
| uav_id       | String | 飞机ID   |         |
| uav_name     | String | 飞机名称 |         |
| uav_code     | String | 飞机编码 |         |
| uav_type     | String | 飞机类型 |         |
| work_acreage | String | 作业面积 | 单位:亩 |

JSON格式数据如下：

{

>   "status":"{code=0, reasonPhrase=SUCCESS}",

>   "data":{"total": 2

>   "list":[{

>   "team_id":"\*\*\*",

>   "uav_id":"\*\*\*",

>   "uav_name":"\*\*\*",

>   "uav_code":"\*\*\*",

>   "uav_type":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   },{

>   "team_id":"\*\*\*",

>   "uav_id":"\*\*\*",

>   "uav_name":"\*\*\*",

>   "uav_code":"\*\*\*",

>   "uav_type":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   }]

}

}

团队人员作业统计
----------------

### 程序描述

按日期统计团队成员作业面积。

### 功能

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名  | 类型   | 中文意义 | 说明           |
|---------|--------|----------|----------------|
| team_id | String | 团队ID   |                |
| date    | String | 查询日期 | 年_月: 2018_11 |
| type    | String | 查询类型 | 0:年;1:月;2:日 |

JSON格式数据如下：

{

"team_id":"\*\*\*",

"date":"\*\*\*"

}

### 输出

>   列表:

| 参数名       | 类型   | 中文意义 | 说明    |
|--------------|--------|----------|---------|
| team_id      | String | 团队id   |         |
| user_id      | String | 飞机ID   |         |
| user_name    | String | 飞机名称 |         |
| work_acreage | String | 作业面积 | 单位:亩 |

JSON格式数据如下：

{

>   "status":"{code=0, reasonPhrase=SUCCESS}",

>   "data":{"total": 2

>   "list":[{

>   "team_id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "user_name":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   },{

>   "team_id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "user_name":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   }]

}

}

团队订单统计
------------

### 程序描述

按日统计用户订单。

### 功能

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名  | 类型   | 中文意义 | 说明                 |
|---------|--------|----------|----------------------|
| team_id | String | 用户ID   |                      |
| date    | String | 查询日期 | 年_月_日: 2018_11_11 |

JSON格式数据如下：

{

"team \_id":"\*\*\*",

"date":"\*\*\*"

}

### 输出

>   列表:

| 参数名       | 类型   | 中文意义 | 说明    |
|--------------|--------|----------|---------|
| team_id      | String | 用户id   |         |
| order_id     | String | 订单ID   |         |
| order_name   | String | 订单名称 |         |
| address      | String | 作业地址 |         |
| work_acreage | String | 作业面积 | 单位:亩 |

JSON格式数据如下：

{

>   "status":"{code=0, reasonPhrase=SUCCESS}",

>   "data":{"total": 2

>   "list":[{

>   "team_id":"\*\*\*",

>   "order_id":"\*\*\*",

>   "order_name":"\*\*\*",

>   "address":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   },{

>   "team_id":"\*\*\*",

>   "order_id":"\*\*\*",

>   "order_name":"\*\*\*",

>   "address":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   }]

}

}

用户作业统计
------------

### 程序描述

按年、月、日统计总作业面积、测绘面积、总时长、订单数

### 功能

按年、月、日统计总作业面积、测绘面积、总时长、订单数

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名  | 类型   | 中文意义 | 说明                                    |
|---------|--------|----------|-----------------------------------------|
| user_id | String | 用户ID   |                                         |
| date    | String | 查询日期 | 年: 2018;年月:2018_11;年月日:2018_11_11 |

JSON格式数据如下：

{

"user_id":"\*\*\*",

"date":"\*\*\*"

}

### 输出

>   列表:

| 参数名          | 类型   | 中文意义   | 说明       |
|-----------------|--------|------------|------------|
| user_id         | String | 用户id     |            |
| total_acreage   | String | 总作业面积 | 单位:亩    |
| mapping_acreage | String | 测绘面积   | 单位:亩    |
| total_time      | String | 总时长     | 单位:小时  |
| efficiency      | String | 作业效率   | 单位:亩/天 |

JSON格式数据如下：

{

>   "status":"{code=0, reasonPhrase=SUCCESS}",

>   "data":{

"user_id":"\*\*\*",

>   "total_acreage":"\*\*\*",

>   "mapping_acreage":"\*\*\*",

>   "total_time":"\*\*\*",

>   "efficiency":"\*\*\*"

}

}

用户作业记录统计
----------------

### 程序描述

按年统计用户作业信息。

### 功能

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名  | 类型   | 中文意义 | 说明     |
|---------|--------|----------|----------|
| user_id | String | 用户ID   |          |
| date    | String | 查询日期 | 年: 2018 |

JSON格式数据如下：

{

"user_id":"\*\*\*",

"date":"\*\*\*"

}

### 输出

>   列表:

| 参数名     | 类型   | 中文意义     | 说明    |
|------------|--------|--------------|---------|
| user_id    | String | 用户id       |         |
| area_count | String | 作业区域个数 | 单位个  |
| crop_count | String | 作物种类数量 | 单位:种 |

JSON格式数据如下：

{

>   "status":"{code=0, reasonPhrase=SUCCESS}",

>   "data":{

>   "user_id":"\*\*\*",

>   "area_count":"\*\*\*",

>   "crop_count":"\*\*\*"

}

}

用户月作业曲线图
----------------

### 程序描述

按年查询每月作业面积。

### 功能

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名  | 类型   | 中文意义 | 说明     |
|---------|--------|----------|----------|
| user_id | String | 用户ID   |          |
| date    | String | 查询日期 | 年: 2018 |

JSON格式数据如下：

{

"user_id":"\*\*\*",

"date":"\*\*\*"

}

### 输出

>   列表:

| 参数名       | 类型   | 中文意义 | 说明    |
|--------------|--------|----------|---------|
| user_id      | String | 用户id   |         |
| month        | String | 月份     |         |
| work_acreage | String | 作业面积 | 单位:亩 |

JSON格式数据如下：

{

>   "status":"{code=0, reasonPhrase=SUCCESS}",

>   "data":{"list":[{

>   "user_id":"\*\*\*",

>   "month":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   },{

>   "user_id":"\*\*\*",

>   "month":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   }]

}

}

用户日作业曲线图
----------------

### 程序描述

按月查询每日作业面积。

### 功能

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名  | 类型   | 中文意义 | 说明          |
|---------|--------|----------|---------------|
| user_id | String | 用户ID   |               |
| date    | String | 查询日期 | 年月: 2018_11 |

JSON格式数据如下：

{

"user_id":"\*\*\*",

"date":"\*\*\*"

}

### 输出

>   列表:

| 参数名       | 类型   | 中文意义 | 说明    |
|--------------|--------|----------|---------|
| user_id      | String | 用户id   |         |
| day          | String | 日期     |         |
| work_acreage | String | 作业面积 | 单位:亩 |

JSON格式数据如下：

{

>   "status":"{code=0, reasonPhrase=SUCCESS}",

>   "data":{"list":[{

>   "user_id":"\*\*\*",

>   "day":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   },{

>   "user_id":"\*\*\*",

>   "day":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   }]

}

}

用户农作物柱状图
----------------

### 程序描述

按年统计每种农作物作业面积。

### 功能

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名  | 类型   | 中文意义 | 说明     |
|---------|--------|----------|----------|
| user_id | String | 用户ID   |          |
| date    | String | 查询日期 | 年: 2018 |

JSON格式数据如下：

{

"user_id":"\*\*\*",

"date":"\*\*\*"

}

### 输出

>   列表:

| 参数名       | 类型   | 中文意义   | 说明    |
|--------------|--------|------------|---------|
| user_id      | String | 用户id     |         |
| crop_name    | String | 农作物名称 |         |
| work_acreage | String | 作业面积   | 单位:亩 |

JSON格式数据如下：

{

>   "status":"{code=0, reasonPhrase=SUCCESS}",

>   "data":{"list":[{

>   "user_id":"\*\*\*",

>   "crop_name":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   },{

>   "user_id":"\*\*\*",

>   "crop_name":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   }]

}

}

用户地区作业记录
----------------

### 程序描述

按年统计每地区作业面积。

### 功能

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名  | 类型   | 中文意义 | 说明     |
|---------|--------|----------|----------|
| user_id | String | 用户ID   |          |
| date    | String | 查询日期 | 年: 2018 |

JSON格式数据如下：

{

"user_id":"\*\*\*",

"date":"\*\*\*"

}

### 输出

>   列表:

| 参数名       | 类型   | 中文意义       | 说明    |
|--------------|--------|----------------|---------|
| user_id      | String | 用户id         |         |
| city_name    | String | 农作物名称     |         |
| city         | String | 市级行政区名称 |         |
| work_acreage | String | 作业面积       | 单位:亩 |
| province     | String | 省级行政区名称 |         |
| area_name    | String | 县级行政区名称 |         |

JSON格式数据如下：

{

>   "status":"{code=0, reasonPhrase=SUCCESS}",

>   "data":{"list":[{

>   "user_id":"\*\*\*",

>   "city ":"\*\*\*",

>   "province":"\*\*\*",

>   "area_name":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   },{

>   "user_id":"\*\*\*",

>   "city ":"\*\*\*",

>   "province":"\*\*\*",

>   "area_name":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   }]

}

}

用户设备作业统计
----------------

### 程序描述

按日期统计用户设备作业面积。

### 功能

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名  | 类型   | 中文意义 | 说明                                |
|---------|--------|----------|-------------------------------------|
| user_id | String | 用户ID   |                                     |
| date    | String | 查询日期 | 年_月: 2018_11;年_月_日: 2018_11_11 |

JSON格式数据如下：

{

"user_id":"\*\*\*",

"date":"\*\*\*"

}

### 输出

>   列表:

| 参数名       | 类型   | 中文意义 | 说明    |
|--------------|--------|----------|---------|
| user_id      | String | 用户id   |         |
| uav_id       | String | 飞机ID   |         |
| uav_name     | String | 飞机名称 |         |
| uav_code     | String | 飞机编码 |         |
| uav_type     | String | 飞机类型 |         |
| work_acreage | String | 作业面积 | 单位:亩 |

JSON格式数据如下：

{

>   "status":"{code=0, reasonPhrase=SUCCESS}",

>   "data":{"total": 2

>   "list":[{

>   "user_id":"\*\*\*",

>   "uav_id":"\*\*\*",

>   "uav_name":"\*\*\*",

>   "uav_code":"\*\*\*",

>   "uav_type":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   },{

>   "user_id":"\*\*\*",

>   "uav_id":"\*\*\*",

>   "uav_name":"\*\*\*",

>   "uav_code":"\*\*\*",

>   "uav_type":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   }]

}

}

用户订单统计
------------

### 程序描述

按日统计用户订单。

### 功能

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名  | 类型   | 中文意义 | 说明                 |
|---------|--------|----------|----------------------|
| user_id | String | 用户ID   |                      |
| date    | String | 查询日期 | 年_月_日: 2018_11_11 |

JSON格式数据如下：

{

"user_id":"\*\*\*",

"date":"\*\*\*"

}

### 输出

>   列表:

| 参数名       | 类型   | 中文意义 | 说明    |
|--------------|--------|----------|---------|
| user_id      | String | 用户id   |         |
| order_id     | String | 订单ID   |         |
| order_name   | String | 订单名称 |         |
| address      | String | 作业地址 |         |
| work_acreage | String | 作业面积 | 单位:亩 |

JSON格式数据如下：

{

>   "status":"{code=0, reasonPhrase=SUCCESS}",

>   "data":{"total": 2

>   "list":[{

>   "user_id":"\*\*\*",

>   "order_id":"\*\*\*",

>   "order_name":"\*\*\*",

>   "address":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   },{

>   "user_id":"\*\*\*",

>   "order_id":"\*\*\*",

>   "order_name":"\*\*\*",

>   "address":"\*\*\*",

>   "work_acreage":"\*\*\*"

>   }]

}

}

设备管理部分接口
==========================

无人机列表
----------

### 程序描述

分页查询用户[自用]无人机以及当前团队中分配给当前用户使用的无人机列表列表。

### 功能

分页查询用户[自用]无人机以及当前团队中分配给当前用户使用的无人机列表列表。

### 性能

无

### 请求方式

>   POST

### 请求地址

> /api/plantUav/findUavListByTeam

### 输入

| 参数名       | 类型   | 中文意义                         | 说明     |
|--------------|--------|------------------------------|----------|
| user_id      | String | 用户ID                        |          |
| type_id      | String | 设备类型                        |          |
| status       | String | 设备状态                        |          |
| page_count   | String | 每页数量                        |          |
| current_page | String | 当前页码                        |          |
| order_by     | String | 当前排序依据，默认为create_time   |          |
| order_model  | String | 当前排序方式，默认为1(desc)       |          |
| device_name  | String | 无人机名称                      | 模糊查询   |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名                 | 类型   | 中文意义                     | 说明        |
|-----------------------|-------|-----------------------------|-------------|
|id 	       			|String	|用户设备关系表ID	              |      |
|remarks 				|String	|备注	                      |      |
|createDate 			|String	|创建时间	                      |      |
|updateDate 			|String	|更新时间	                      |      |
|update_by 				|String	|创建者ID	                      |      |
|create_by 				|String	|修改者ID	                      |      |
|create_date			|String	|创建时间戳	                  |      |
|update_date			|String	|修改时间戳	                  |      |
|device_id 				|String	|设备ID	                      |      |
|device_name			|String	|设备名称	                      |      |
|owner_id 				|String	|所有者ID	                      |      |
|owner_name 			|String	|所有者姓名	                  |      |
|user_id 				|String	|使用者ID	                      |      |
|user_name 				|String	|使用者姓名	                  |      |
|office_id 				|String	|经销商ID	                      |      |
|own_flag 				|String	|所有权标识	0:使用;1:拥有;2:租用|      |
|sn 	                |String	|飞机串号，唯一标识码	          |      |
|autopilot_id 			|String	|飞控id	                      |      |
|prodection_type_id 	|String	|飞机产品的类别	              |      |
|type_id 				|String	|飞机类型id	                  |      |
|run_type_id 			|String	|飞机运行类型ID	              |      |
|number 				|String	|无人机编号	                  |      |
|category_id 			|String	|飞机用途分类id	              |      |
|is_lock 				|String	|飞机开解锁状态，5，解锁，4，加锁   |      |
|is_sale 				|String	|是否出售，1，已售，2未售 3租赁	　|      |
|cpn 					|String	|无人机运营商cpn编号	　        |      |
|reg 					|String	|国际登记标志或者注册码	　        |      |
|sale_id				|String	|分配id，卖给谁的用户id	　        |      |
|type_name				|String	|飞机类型名称	　                |      |
|run_type_name			|String	|飞机运行类型名称	　            |      |
|flow_total				|String	|流量卡总量	　                |      |
|flow_used				|String	|使用流量	　                    |      |
|flow_left				|String	|剩余流量	　                    |      |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

"total": 20,

>   "list":[{

>   "id":"\*\*\*",

>   "uav_id":"\*\*\*",

>   "uav_name":"\*\*\*",

>   "uav_logo_url":"\*\*\*",

>   "uav_code":"\*\*\*",

>   "own_user_id":"\*\*\*",

>   "own_user_name":"\*\*\*",

>   "uav_status":"\*\*\*""

>   },{

>   "id":"\*\*\*",

>   "uav_id":"\*\*\*",

>   "uav_name":"\*\*\*",

>   "uav_logo_url":"\*\*\*",

>   "uav_code":"\*\*\*",

>   "own_user_id":"\*\*\*",

>   "own_user_name":"\*\*\*",

>   "uav_status":"\*\*\*" }]

>   }

}

设备详情
--------

### 程序描述

根据无人机设备ID获取设备详情。

### 功能

根据无人机设备ID获取设备详情。

### 性能

无

### 请求方式

>   POST

### 请求地址

> /api/plantUav/getByDeviceId

### 输入

| 参数名     | 类型    | 中文意义  | 说明  |
|-----------|--------|---------|------|
| device_id | String | 设备ID   |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名                 | 类型   | 中文意义                     | 说明        |
|-----------------------|-------|------------------------------------------|
|id 	       			|String	|用户设备关系表ID	              |
|remarks 				|String	|备注	                      |
|createDate 			|String	|创建时间	                      |
|updateDate 			|String	|更新时间	                      |
|update_by 				|String	|创建者ID	                      |
|create_by 				|String	|修改者ID	                      |
|create_date			|String	|创建时间戳	                  |
|update_date			|String	|修改时间戳	                  |
|device_id 				|String	|设备ID	                      |
|device_name			|String	|设备名称	                      |
|owner_id 				|String	|所有者ID	                      |
|owner_name 			|String	|所有者姓名	                  |
|user_id 				|String	|使用者ID	                      |
|user_name 				|String	|使用者姓名	                  |
|office_id 				|String	|经销商ID	                      |
|own_flag 				|String	|所有权标识	0:使用;1:拥有;2:租用|
|sn 	                |String	|飞机串号，唯一标识码	          |
|autopilot_id 			|String	|飞控id	                      |
|prodection_type_id 	|String	|飞机产品的类别	              |
|type_id 				|String	|飞机类型id	                  |
|run_type_id 			|String	|飞机运行类型ID	              |
|number 				|String	|无人机编号	                  |
|category_id 			|String	|飞机用途分类id	              |
|is_lock 				|String	|飞机开解锁状态，5，解锁，4，加锁   |
|is_sale 				|String	|是否出售，1，已售，2未售 3租赁	　|
|cpn 					|String	|无人机运营商cpn编号	　        |
|reg 					|String	|国际登记标志或者注册码	　        |
|sale_id				|String	|分配id，卖给谁的用户id	　        |
|type_name				|String	|飞机类型名称	　                |
|run_type_name			|String	|飞机运行类型名称	　            |
|flow_total				|String	|流量卡总量	　                |
|flow_used				|String	|使用流量	　                    |
|flow_left				|String	|剩余流量	　                    |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

"uav_id":"\*\*\*",

>   "uav_name":"\*\*\*",

>   "uav_logo_url":"\*\*\*",

>   "uav_code":"\*\*\*",

>   "own_user_id":"\*\*\*",

>   "own_user_name":"\*\*\*",

>   "uav_status":"\*\*\*",

>   "uav_version":"\*\*\*",

>   "product_date":"\*\*\*",

>   "activate_date":"\*\*\*",

>   "binding_date":"\*\*\*",

>   "FC_SN":"\*\*\*",

>   "FC_ID":"\*\*\*",

>   "address":"\*\*\*",

>   "is_lock":"\*\*\*",

>   "is_lock_parameter":"\*\*\*"

}

设备转移
--------

### 程序描述

通过转移人账号查询转移人用户信息,

生成转移记录,

1.修改设备拥有者ID为转移人ID,

2.将该设备转移记录表中next_id为空的记录的next_id设置为新生成的记录的ID;

3.插入新生成的转移记录,这条记录的next_id为空。

1,2,3在同一事务中完成

### 功能

将设备转移给其他用户。

### 性能

无

### 请求方式

>   POST

### 请求地址

> /api/deviceExchange/exchange

### 输入

| 参数名         | 类型   | 中文意义    | 说明                              |
|---------------|-------|-----------|-----------------------------------|
|device_id		|String	|设备ID	   	|                                   |
|sell_id		|String	|售出人ID	    |(可为空:空时取当前登录用户ID)           |
|phone			|String	|转移人账号	|                                   |
|device_category|String	|设备类型	    |1:无人机,2:rtk基站,3:千寻账号     |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}"}

设备维护
--------

### 程序描述

设备维护。

### 功能

设备维护。

### 性能

无

### 请求方式

>   POST

### 请求地址

> /api/issue/publishIssue

### 输入

| 参数名          | 类型    | 中文意义  | 说明 |
|----------------|--------|---------|------|
| device_id      | String | 设备ID   |      |
| device_category| String | 设备类别  |1:无人机,2:rtk基站,3:千寻账号 |
| issue_type     | String | 问题类型  |      |
| issue_describe | String | 问题描述  |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}"}


无人机设备报废
----------------

### 程序描述

报废无人机设备。

### 功能

报废无人机设备。

### 性能

无

### 请求方式

>   POST

### 请求地址

>   /api/plantUav/abolish

### 输入

| 参数名      | 类型    | 中文意义  | 说明 |
|------------|--------|---------|------|
| device_id  | String | 设备ID   |      |
| remarks    | String | 备注信息  |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}"}


设备作业信息列表
----------------

### 程序描述

分页查询设备作业列表。

### 功能

分页查询设备作业列表。

### 性能

无

### 请求方式

>   POST

### 请求地址

>   /api/uavWorkRecord/findUavWorkRecord

### 输入

| 参数名       | 类型   | 中文意义                        | 说明 |
|--------------|--------|------------------------------|------|
| uav_id       | String | 无人机设备ID                          |      |
| page_count   | String | 每页数量                        |      |
| current_page | String | 当前页码                        |      |
| order_by     | String | 当前排序依据，默认为create_time |      |
| order_model  | String | 当前排序方式，默认为1(desc)     |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名       | 类型   | 中文意义     | 说明                    |
|--------------|--------|--------------|-------------------------|
| id           | String | ID           |                         |
| device_id    | String | 无人机ID     |                         |
| order_id     | String | 订单ID       |                         |
| order_name   | String | 订单名称     |                         |
| address      | String | 地址         |                         |
| start_time   | String | 开始作业时间 |                         |
| work_acreage | String | 作业面积     |                         |
| work_time     | String | 总时长       |                         |
| status       | String | 任务状态     | 0未喷洒 1作业中 2已完成 |
| order_apply_id| String | 订单ID       |                         |
| land_id      | String | 地块ID       |                         |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

"total": 20,

>   "list":[{

>   "id":"\*\*\*",

>   "uav_id":"\*\*\*",

>   "start_time":"\*\*\*",

>   "work_acreage":"\*\*\*",

>   "duration":"\*\*\*",

>   "status":"\*\*\*",

>   "order_id":"\*\*\*",

>   "block_id":"\*\*\*"

>   },{

>   "id":"\*\*\*",

>   "uav_id":"\*\*\*",

>   "start_time":"\*\*\*",

>   "work_acreage":"\*\*\*",

>   "duration":"\*\*\*",

>   "status":"\*\*\*",

>   "order_id":"\*\*\*",

>   "block_id":"\*\*\*"

>   }]

>   }

}


设备使用记录统计
----------------

### 程序描述

根据设备ID统计设备作业数据。

### 功能

根据设备ID统计设备作业数据。

### 性能

无

### 请求方式

>   POST

### 请求地址

> /api/orderTaskStatistics/uavWorkStatistics

### 输入

| 参数名       | 类型   | 中文意义                        | 说明 |
|--------------|--------|------------------------------|------|
| uav_id       | String | 无人机设备ID                          |      |


### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名           | 类型   | 中文意义   | 说明  |
|------------------|--------|------------|-------|
| uav_id        | String | 无人机ID   |       |
| work_acreage_sum | String | 总作业面积 | 亩    |
| dist_sum         | String | 总里程     | 千米  |
| duration_sum     | String | 总时长     | 时    |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

"device_id":"\*\*\*",

>   "uav_name":"\*\*\*",

>   "uav_logo_url":"\*\*\*",

>   "uav_code":"\*\*\*",

>   "own_user_id":"\*\*\*",

>   "own_user_name":"\*\*\*",

>   "uav_status":"\*\*\*",

>   "uav_version":"\*\*\*",

>   "product_date":"\*\*\*",

>   "activate_date":"\*\*\*",

>   "binding_date":"\*\*\*",

>   "FC_SN":"\*\*\*",

>   "FC_ID":"\*\*\*",

>   "address":"\*\*\*",

>   "is_lock":"\*\*\*",

>   "is_lock_parameter":"\*\*\*"

}

设备使用记录列表
----------------

### 程序描述

分页查询无人机设备使用记录列表。

### 功能

分页查询无人机设备使用记录列表。

### 性能

无

### 请求方式

>   POST

### 请求地址

> /api/uavWorkRecord/findUavUseRecord

### 输入

| 参数名       | 类型   | 中文意义                        | 说明 |
|--------------|--------|------------------------------|------|
| uav_id       | String | 无人机设备ID                          |      |
| page_count   | String | 每页数量                        |      |
| current_page | String | 当前页码                        |      |
| order_by     | String | 当前排序依据，默认为create_time |      |
| order_model  | String | 当前排序方式，默认为1(desc)     |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名           | 类型   | 中文意义   | 说明  |
|------------------|--------|------------|-------|
| device_id        | String | 无人机ID   |       |
| work_acreage_sum | String | 总作业面积 | 亩    |
| dist_sum         | String | 总里程     | 千米  |
| duration_sum     | String | 总时长     | 时    |
| efficiency       | String | 作业效率   | 亩/天 |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

"device_id":"\*\*\*",

>   "uav_name":"\*\*\*",

>   "uav_logo_url":"\*\*\*",

>   "uav_code":"\*\*\*",

>   "own_user_id":"\*\*\*",

>   "own_user_name":"\*\*\*",

>   "uav_status":"\*\*\*",

>   "uav_version":"\*\*\*",

>   "product_date":"\*\*\*",

>   "activate_date":"\*\*\*",

>   "binding_date":"\*\*\*",

>   "FC_SN":"\*\*\*",

>   "FC_ID":"\*\*\*",

>   "address":"\*\*\*",

>   "is_lock":"\*\*\*",

>   "is_lock_parameter":"\*\*\*"

}


设备维护记录列表
----------------

### 程序描述

分页查询设备维护记录列表。

### 功能

分页查询设备维护记录列表。

### 性能

无

### 请求方式

>   POST

### 请求地址

>  

### 输入

| 参数名       | 类型   | 中文意义                        | 说明 |
|--------------|--------|---------------------------------|------|
| device_id       | String | 设备ID                          |      |
| page_count   | String | 每页数量                        |      |
| current_page | String | 当前页码                        |      |
| order_by     | String | 当前排序依据，默认为create_time |      |
| order_model  | String | 当前排序方式，默认为1(desc)     |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名         | 类型   | 中文意义 | 说明 |
|----------------|--------|----------|------|
| id             | String | ID       |      |
| device_id         | String | 设备ID   |      |
| issue_type     | String | 问题类型 |      |
| issue_describe | String | 问题描述 |      |
| create_date    | String | 创建时间 |      |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

"total": 20,

>   "list":[{

>   "id":"\*\*\*",

>   "device_id":"\*\*\*",

>   "issue_type":"\*\*\*",

>   "issue_describe":"\*\*\*",

>   "create_date":"\*\*\*"

>   },{

>   "id":"\*\*\*",

>   "device_id":"\*\*\*",

>   "issue_type":"\*\*\*",

>   "issue_describe":"\*\*\*",

>   "create_date":"\*\*\*"

>   }]

>   }

}

设备流转记录列表
----------------

### 程序描述

根据设备ID设备类别分页查询设备流转记录列表。

### 功能

根据设备ID设备类别分页查询设备流转记录列表。

### 性能

无

### 请求方式

>   POST

### 请求地址

>   /api/deviceExchange/getListByDeviceId

### 输入

| 参数名       | 类型   | 中文意义                        | 说明 |
|--------------|--------|---------------------------------|------|
| device_id       | String | 设备ID                          |      |
|device_category|	String|	设备类别|	1:无人机,2:rtk基站,3:千寻账号(暂无)|
| page_count   | String | 每页数量                        |      |
| current_page | String | 当前页码                        |      |
| order_by     | String | 当前排序依据，默认为create_time |      |
| order_model  | String | 当前排序方式，默认为1(desc)     |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名     | 类型   | 中文意义     | 说明         |
|------------|--------|--------------|--------------|
| id         | String | ID           |              |
| device_id     | String | 设备ID       |              |
| user_id   | String | 拥有者用户ID |              |
| user_name | String | 拥有者名称   |              |
| start_time | String | 开始使用时间 |              |
| end_time   | String | 结束使用时间 | 为空时为至今 |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

"total": 20,

>   "list":[{

>   "id":"\*\*\*",

>   "device_id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "user_name":"\*\*\*",

>   "start_time":"\*\*\*",

>   "end_time":"\*\*\*"

>   },{

>   "id":"\*\*\*",

>   "device_id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "user_name":"\*\*\*",

>   "start_time":"\*\*\*",

>   "end_time":"\*\*\*"

>   }]

>   }

}

RTK列表
-------

### 程序描述

查询用户当前团队可用RTK列表。

### 功能

查询用户当前团队可用RTK列表。

### 性能

无

### 请求方式

>   POST

### 请求地址

/api/rtk/findRtkListByTeam

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| user_id | String | 用户ID   |      |
| team_id | String | 团队ID   |      |

示例:

{

"user_id":"487bc6e197704587874d9cc8a4b61a82",

"team_id":"49d0edb6a796460394393c1f349ba17d"

}

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名          | 类型   | 中文意义                                    | 说明 |
|-----------------|--------|---------------------------------------------|------|
| id              | String | 用户设备关系表ID                            |      |
| device_id       | String | RTK设备ID                                   |      |
| device_name     | String | RTK设备名称                                 |      |
| owner_id        | String | 设备拥有者ID                                |      |
| owner_name      | String | 设备拥有者名称                              |      |
| user_id         | String | 设备使用者ID                                |      |
| user_name       | String | 设备使用者名称                              |      |
| temp_owner_id   | String | 设备租赁者ID                                |      |
| temp_owner_name | String | 设备租赁者名称                              |      |
| team_id         | String | 团队ID                                      |      |
| team_name       | String | 团队名称                                    |      |
| status          | String | 状态 0：未绑定，1：已绑定                   |      |
| rent_state      | String | 租赁状态，1，可出租，2，出租中，3，不可出租 |      |
| type            | String | RTK类型                                     |      |
| mobile          | String | 客户手机号                                  |      |
| id_card         | String | 客户身份证号                                |      |
| is_sale         | String | 是否出售，1，已售，2未售，3租赁             |      |
| nickname        | String | 设备昵称                                    |      |

示例:

{

"status": {

"code": 0,

"reasonPhrase": "SUCCESS"

},

"data": {

"list": [

{

"id": "87e0365392194c559ba25f3f0994d111",

"isNewRecord": false,

"create_date": -1,

"update_date": -1,

"device_id": "210",

"device_name": "设备ID是哪个啊...",

"owner_id": "487bc6e197704587874d9cc8a4b61a82",

"owner_name": "88888888888",

"user_id": "487bc6e197704587874d9cc8a4b61a82",

"user_name": "88888888888",

"team_id": "49d0edb6a796460394393c1f349ba17d",

"team_name": "ceshi",

"office_id": "07650b9a0c47413395eed960de6d15c3",

"own_flag": 1,

"status": "0",

"is_sale": "2"

}

]

}

}

获取用户所有团队RTK列表
-----------------------

### 程序描述

查询用户所在团队可用RTK列表。

### 功能

查询用户所在团队可用RTK列表。

### 性能

无

### 请求方式

>   POST

### 请求地址

/api/rtk/findRtkListForApp

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| user_id | String | 用户ID   |      |

示例:

{

"user_id":"487bc6e197704587874d9cc8a4b61a82"

}

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名          | 类型   | 中文意义                                    | 说明 |
|-----------------|--------|---------------------------------------------|------|
| id              | String | 用户设备关系表ID                            |      |
| device_id       | String | RTK设备ID                                   |      |
| device_name     | String | RTK设备名称                                 |      |
| owner_id        | String | 设备拥有者ID                                |      |
| owner_name      | String | 设备拥有者名称                              |      |
| user_id         | String | 设备使用者ID                                |      |
| user_name       | String | 设备使用者名称                              |      |
| temp_owner_id   | String | 设备租赁者ID                                |      |
| temp_owner_name | String | 设备租赁者名称                              |      |
| team_id         | String | 团队ID                                      |      |
| team_name       | String | 团队名称                                    |      |
| status          | String | 状态 0：未绑定，1：已绑定                   |      |
| rent_state      | String | 租赁状态，1，可出租，2，出租中，3，不可出租 |      |
| type            | String | RTK类型                                     |      |
| mobile          | String | 客户手机号                                  |      |
| id_card         | String | 客户身份证号                                |      |
| is_sale         | String | 是否出售，1，已售，2未售，3租赁             |      |
| nickname        | String | 设备昵称                                    |      |

示例:

{

"status": {

"code": 0,

"reasonPhrase": "SUCCESS"

},

"data": {

>   "49d0edb6a796460394393c1f349ba17d": [//团队ID

{

"id": "87e0365392194c559ba25f3f0994d111",

"isNewRecord": false,

"create_date": -1,

"update_date": -1,

"device_id": "210",

"device_name": "设备ID是哪个啊...",

"owner_id": "487bc6e197704587874d9cc8a4b61a82",

"owner_name": "88888888888",

"user_id": "487bc6e197704587874d9cc8a4b61a82",

"user_name": "88888888888",

"team_id": "49d0edb6a796460394393c1f349ba17d",

"team_name": "ceshi",

"office_id": "07650b9a0c47413395eed960de6d15c3",

"own_flag": 1,

"status": "0",

"is_sale": "2"

}

]

},

>   "49d0edb6a796460394393c1f349ba17d": [//团队ID

{

"id": "87e0365392194c559ba25f3f0994d111",

"isNewRecord": false,

"create_date": -1,

"update_date": -1,

"device_id": "210",

"device_name": "设备ID是哪个啊...",

"owner_id": "487bc6e197704587874d9cc8a4b61a82",

"owner_name": "88888888888",

"user_id": "487bc6e197704587874d9cc8a4b61a82",

"user_name": "88888888888",

"team_id": "49d0edb6a796460394393c1f349ba17d",

"team_name": "ceshi",

"office_id": "07650b9a0c47413395eed960de6d15c3",

"own_flag": 1,

"status": "0",

"is_sale": "2"

}

]

}

}

RTK设备详情
-----------

### 程序描述

根据ID获取RTK设备详情。

### 功能

根据ID获取RTK设备详情。

### 性能

无

### 请求方式

>   POST

### 请求地址

> /api/rtk/getByDeviceId

### 输入

| 参数名 | 类型   | 中文意义  | 说明 |
|--------|--------|-----------|------|
| device_id | String | RTK设备ID |    |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名          | 类型   | 中文意义                                    | 说明 |
|-----------------|--------|---------------------------------------------|------|
| id              | String | 用户设备关系表ID                            |      |
| device_id       | String | RTK设备ID                                   |      |
| device_name     | String | RTK设备名称                                 |      |
| owner_id        | String | 设备拥有者ID                                |      |
| owner_name      | String | 设备拥有者名称                              |      |
| user_id         | String | 设备使用者ID                                |      |
| user_name       | String | 设备使用者名称                              |      |
| temp_owner_id   | String | 设备租赁者ID                                |      |
| temp_owner_name | String | 设备租赁者名称                              |      |
| team_id         | String | 团队ID                                      |      |
| team_name       | String | 团队名称                                    |      |
| status          | String | 状态 0：未绑定，1：已绑定                   |      |
| rent_state      | String | 租赁状态，1，可出租，2，出租中，3，不可出租 |      |
| type            | String | RTK类型                                     |      |
| mobile          | String | 客户手机号                                  |      |
| id_card         | String | 客户身份证号                                |      |
| is_sale         | String | 是否出售，1，已售，2未售，3租赁             |      |
| abolish_flag    | String | 是否报废标识:0:未报废;1:已报废         |      |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

>   "id":"\*\*\*",

>   "rtk_no":"\*\*\*",

>   "rtk_name":"\*\*\*",

>   "user_id":"\*\*\*",

>   "rtk_version":"\*\*\*",

>   "product_date":"\*\*\*",

>   "activate_date":"\*\*\*",

>   "binding_date":"\*\*\*",

>   "status":"\*\*\*",

>   "remarks":"\*\*\*"

}

RTK设备流转记录列表
-------------------

### 程序描述

分页查询RTK设备流转记录列表。

### 功能

分页查询RTK设备流转记录列表。

### 性能

无

### 请求地址

>   /api/deviceExchange/getListByDeviceId

### 输入

| 参数名       | 类型   | 中文意义                        | 说明 |
|--------------|--------|---------------------------------|------|
| device_id       | String | 设备ID                          |      |
|device_category|	String|	设备类别|	1:无人机,2:rtk基站,3:千寻账号(暂无)|
| page_count   | String | 每页数量                        |      |
| current_page | String | 当前页码                        |      |
| order_by     | String | 当前排序依据，默认为create_time |      |
| order_model  | String | 当前排序方式，默认为1(desc)     |      |

### 输出

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名     | 类型   | 中文意义     | 说明         |
|------------|--------|--------------|--------------|
| id         | String | ID           |              |
| device_id     | String | 设备ID       |              |
| user_id   | String | 拥有者用户ID |              |
| user_name | String | 拥有者名称   |              |
| start_time | String | 开始使用时间 |              |
| end_time   | String | 结束使用时间 | 为空时为至今 |
| sell_id   | String |售出人ID|     |
示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

"total": 20,

>   "list":[{

>   "id":"\*\*\*",

>   "device_id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "user_name":"\*\*\*",

>   "start_time":"\*\*\*",

>   "end_time":"\*\*\*"

>   },{

>   "id":"\*\*\*",

>   "device_id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "user_name":"\*\*\*",

>   "start_time":"\*\*\*",

>   "end_time":"\*\*\*"

>   }]

>   }

}

设备自用
----------------

### 程序描述

在设备使用表中删除该设备的团队使用权限(设备所有者关系不能删)。

### 功能

在设备使用表中删除该设备的团队使用权限(设备所有者关系不能删)。

### 性能

无

### 请求方式

>   POST

### 请求地址

>   /api/deviceUser/setSelf

### 输入

| 参数名             | 类型    | 中文意义  | 说明 |
|-------------------|--------|---------|------|
| device_id         | String | 设备ID   |      |
| device_category   | String | 设备ID   |1:无人机,2:rtk基站,3:千寻账号(暂无)      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}"}

设备设置共享团队
--------------------

### 程序描述

1.  在设备使用表中删除未被选择的团队使用权限(用户自有权限不删);

2.  之前选择且又被选择的团队使用权保持不变;

3.  增量添加新被选择的团队队长使用权.

### 功能

1.  在设备使用表中删除未被选择的团队使用权限(用户自有权限不删);

2.  之前选择且又被选择的团队使用权保持不变;

3.  增量添加新被选择的团队队长使用权。

### 性能

无

### 请求方式

>   POST

### 请求地址

>   /api/deviceUser/share

### 输入

| 参数名               | 类型    |中文意义          | 说明 |
|---------------------|--------|----------------|------|
| device_id           | String | 设备ID          |      |
| device_category     | String | 设备ID          |1:无人机,2:rtk基站,3:千寻账号(暂无)      |
| team_ids            | Array  | 备选团队ID列表    |      |

{

"device_id":"\*\*\*",

"team_ids":[111,222,333]

}

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}"}

查询设备共享团队列表
----------------------------

### 程序描述

查询设备可被分配团队列表,已被分配团队进行标记.

### 功能

查询设备可被分配团队列表,已被分配团队进行标记

### 性能

无

### 请求方式

>   GET

### 请求地址

> /api/teamFlyer/findDeviceShareTeams/{device_id}

### 输入

| 参数名    | 类型   | 中文意义 | 说明                              |
|-----------|--------|----------|-----------------------------------|
| device_id | String | 设备ID   | 必传                              |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名        | 类型   | 中文意义       | 说明                                                                                                    |
|---------------|--------|----------------|---------------------------------------------------------------------------------------------------------|
| user_id       | String | 用户ID         |                                                                                                         |
| team_id       | String | 团队ID         |                                                                                                         |
| team_name     | String | 团队名称       |                                                                                                         |
| team_logo_url | String | 团队logo URL   |                                                                                                         |
| leader_id     | String | 队长ID         |                                                                                                         |
| leader_name   | String | 队长名称       |                                                                                                         |
| member_count  | String | 队员数量       |                                                                                                         |
| current_flag  | String | 当前植保队标记 | 0:非当前植保队;1:当前植保队                                                                             |
| share_flag   | int    | 共享标识       | 0:未共享;1已共享(不在数据库中保存,程序通过设备使用权关系表中是否存在该团队队长与该设备关系记录进行判断) |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

>   "list":[{

>   "user_id":"\*\*\*",

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "team_logo_url":"\*\*\*",

>   "apply_count":"\*\*\*",

>   "leader_id":"\*\*\*",

>   "leader_name":"\*\*\*",

>   "member_count":"\*\*\*",

>   "shared_flag":"\*\*\*",

>   "current_flag":"\*\*\*"

>   },{

>   "user_id":"\*\*\*",

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "team_logo_url":"\*\*\*",

>   "apply_count":"\*\*\*",

>   "leader_id":"\*\*\*",

>   "leader_name":"\*\*\*",

>   "member_count":"\*\*\*",

>   "shared_flag":"\*\*\*",

>   "current_flag":"\*\*\*"

>   }]

>   }

}

查询团队设备列表
------------------------

### 程序描述

分页查询当前团队中分配给当前用户使用的设备列表(队长使用,用于分配设备)。

### 功能

分页查询当前团队中分配给当前用户使用的设备列表(队长使用,用于分配设备)。

### 性能

无

### 请求方式

>   POST

### 请求地址

> /api/deviceUser/findTeamDevices

### 输入

| 参数名       | 类型   | 中文意义                        | 说明     |
|--------------|--------|---------------------------------|----------|
| user_id      | String | 用户ID                          |          |
| team_id      | String | 团队ID                          |          |
| device_category| String | 设备类别                     |设备类别 用于识别设备:无人机:1;rtk:2;千寻账号:3   默认为1.无人机       |
| page_count   | String | 每页数量                        |          |
| current_page | String | 当前页码                        |          |
| order_by     | String | 当前排序依据，默认为create_time |          |
| order_model  | String | 当前排序方式，默认为1(desc)     |          |
| device_name  | String | 无人机名称                      | 模糊查询 |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名        | 类型   | 中文意义   | 说明 |
|---------------|--------|------------|------|
| device_id     | String | 设备ID     |      |
| device_name   | String | 设备名称   |      |
| owner_id      | String | 拥有者ID   |      |
| owner_name    | String | 拥有者姓名 |      |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

"total": 20,

>   "list":[{

>   "device_id":"\*\*\*",

>   "device_name":"\*\*\*",

>   "owner_id":"\*\*\*",

>   "owner_name":"\*\*\*"

>   },{

>   "device_id":"\*\*\*",

>   "device_name":"\*\*\*",

>   "owner_id":"\*\*\*",

>   "owner_name":"\*\*\*"

}]

>   }

}

分配设备
----------------

### 程序描述

团队队长将共享给当前团队的无人机分配给当前团队队员使用(队长和设备所有人默认被分配并且不能取消)

### 功能

团队队长将共享给当前团队的无人机分配给当前团队队员使用(队长和设备所有认默认被分配并且不能取消)。

### 性能

无

### 请求方式

>   POST

### 请求地址

> /api/deviceUser/distributeDevice

### 输入

| 参数名    | 类型   | 中文意义         | 说明 |
|-----------|--------|------------------|------|
| device_id | String | 设备ID           |      |
| team_id   | String | 团队ID           |      |
| user_ids  | Array  | 被分配队员ID列表 |      |


### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}"}

千寻账号绑定
--------------------

### 程序描述

>   将选择的千寻账号与当前设备进行绑定,如果被绑的千寻账号之前绑定的设备上线则不允许该千寻账号被绑定.

### 功能

>   将选择的千寻账号与当前设备进行绑定,如果被绑的千寻账号之前绑定的设备上线则不允许该千寻账号被绑定

### 性能

无

### 请求方式

>   POST

### 请求地址

>   /api/qxAccount/bind

### 输入

| 参数名     | 类型   | 中文意义  | 说明 |
|------------|--------|-----------|------|
| binding_id | String | RTK设备ID |      |
| account_id | String | 千寻账号  |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}"}

千寻账号解绑
--------------------

### 程序描述

>   将RTK设备与千寻账号解绑.如果该设备处于在线状态(last_point_rtk设备最后更新时间小于当前时间2分钟)则不允许解绑

### 功能

>   将RTK设备与千寻账号解绑.如果该设备处于在线状态(last_point_rtk设备最后更新时间小于当前时间2分钟)则不允许解绑

### 性能

无

### 请求方式

>   POST

### 请求地址

>   /api/qxAccount/unbind

### 输入

| 参数名    | 类型   | 中文意义  | 说明 |
|-----------|--------|-----------|------|
| account_id | String | 需要解绑的千寻账号 |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}"}

微信端查询可绑定千寻账号列表
------------------------------------

### 程序描述

查询当前团队可获取的RTK列表(当前不在线的rtk绑定的千寻账号和未被绑定的千寻账号列表)。

### 功能

查询当前团队可获取的RTK列表(当前不在线的rtk绑定的千寻账号和未被绑定的千寻账号列表)s。

### 性能

无

### 请求方式

>   POST

### 请求地址

>   /api/qxAccount/availableQxAccounts

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| user_id | String | 用户ID   |      |
| team_id | String | 团队ID   |      |

示例:

{

"user_id":"487bc6e197704587874d9cc8a4b61a82",

"team_id":"49d0edb6a796460394393c1f349ba17d"

}

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名          | 类型   | 中文意义           | 说明                                       |
|-----------------|--------|--------------------|--------------------------------------------|
| id              | String | 用户设备关系ID     |                                            |
| account_id      | String | 千寻账号ID         |                                            |
| account_secret  | String | 千寻账号密码       |                                            |
| status          | String | 账号状态           | 1: 未激活，2：服务中，3：暂停，5：即将到期 |
| valid_date      | String | 有效期至           |                                            |
| device_id       | String | 千寻账号ID         |                                            |
| device_name     | String | 千寻账号           |                                            |
| owner_id        | String | 设备拥有者ID       |                                            |
| owner_name      | String | 设备拥有者名称     |                                            |
| user_id         | String | 设备使用者ID       |                                            |
| user_name       | String | 设备使用者名称     |                                            |
| temp_owner_id   | String | 设备租赁者ID       |                                            |
| temp_owner_name | String | 设备租赁者名称     |                                            |
| team_id         | String | 团队ID             |                                            |
| team_name       | String | 团队名称           |                                            |
| binding_id      | String | 绑定RTK ID         |                                            |
| binding_name    | String | 绑定RTK名称        |                                            |
| office_id       | String | 经销商ID           |                                            |
| office_name     | String | 经销商名称         |                                            |
| last_time       | String | 绑定设备离线时间戳 |                                            |
|                 |        |                    |                                            |

示例:

{

"status": {

"code": 0,

"reasonPhrase": "SUCCESS"

},

"data": {

"list": [

{

"id": "487bc6e197704587874d9cc8a4b61aww",

"isNewRecord": false,

"create_date": -1,

"update_date": -1,

"device_id": "a9a834c6cc2043f58da0001281df68cc",

"device_name": "D000003ON9A",

"owner_id": "",

"user_id": "487bc6e197704587874d9cc8a4b61a82",

"user_name": "88888888888",

"team_id": "22",

"team_name": "as",

"temp_owner_id": "487bc6e197704587874d9cc8a4b61a82",

"temp_owner_name": "88888888888",

"office_id": "b84cbed292f144f2819db846c40a46f7",

"office_name": "V3测试环境(勿删)",

"own_flag": 2,

"account_id": "D000003ON9A",

"account_secret":
"61ddde95e7a3be7a1f51658dc3730849cfb996569641fbf8cf56b5275ac72ba7",

"valid_date": "2018-11-30 14:15:41.0",

"status": "2",

"binding_id": "fb649aa78a1546eb9041da239153aaee",

"binding_name": "测试RTK",

"lon": 0,

"lat": 0,

"last_time": 1543214881000

},

{

"id": "487bc6e197704587874d9cc8a4b61aqq",

"isNewRecord": false,

"create_date": -1,

"update_date": -1,

"device_id": "a9a828572bf64306b3bd34ecb8a26cfc",

"device_name": "D000003ONCM",

"owner_id": "487bc6e197704587874d9cc8a4b61a82",

"owner_name": "88888888888",

"user_id": "487bc6e197704587874d9cc8a4b61a82",

"user_name": "88888888888",

"office_id": "b84cbed292f144f2819db846c40a46f7",

"office_name": "V3测试环境(勿删)",

"own_flag": 1,

"account_id": "D000003ONCM",

"account_secret":
"61ddde95e7a3be7a1f51658dc3730849cfb996569641fbf8cf56b5275ac72ba7",

"valid_date": "2018-11-30 14:15:36.0",

"status": "5",

"lon": 0,

"lat": 0,

"last_time": 0

}

]

}

}

APP端查询可绑定千寻账号列表
-----------------------------------

### 程序描述

查询可绑定千寻账号列表(当前不在线的rtk绑定的千寻账号和未被绑定的千寻账号列表)。

### 功能

查询可绑定千寻账号列表(当前不在线的rtk绑定的千寻账号和未被绑定的千寻账号列表)s。

### 性能

无

### 请求方式

>   POST

### 请求地址

>/api/qxAccount/availableQxAccountsForApp

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| user_id | String | 用户ID   |      |

示例:{

"user_id":"487bc6e197704587874d9cc8a4b61a82"

}

### 输出

JSON格式数据如下：

{"status":"{code=0,
reasonPhrase=SUCCESS}","data":"{团队ID1:[{千寻账号1},{千寻账号2}],

团队ID2:[{千寻账号1},{千寻账号2}]}"}

| 参数名          | 类型   | 中文意义           | 说明                                       |
|-----------------|--------|--------------------|--------------------------------------------|
| id              | String | ID                 |                                            |
| account_id      | String | 千寻账号ID         |                                            |
| account_secret  | String | 千寻账号密码       |                                            |
| status          | String | 账号状态           | 1: 未激活，2：服务中，3：暂停，4：即将到期 |
| valid_date      | String | 有效期至           |                                            |
| device_id       | String | 千寻账号ID         |                                            |
| device_name     | String | 千寻账号           |                                            |
| owner_id        | String | 设备拥有者ID       |                                            |
| owner_name      | String | 设备拥有者名称     |                                            |
| user_id         | String | 设备使用者ID       |                                            |
| user_name       | String | 设备使用者名称     |                                            |
| temp_owner_id   | String | 设备租赁者ID       |                                            |
| temp_owner_name | String | 设备租赁者名称     |                                            |
| team_id         | String | 团队ID             |                                            |
| team_name       | String | 团队名称           |                                            |
| binding_id      | String | 绑定RTK ID         |                                            |
| binding_name    | String | 绑定RTK名称        |                                            |
| office_id       | String | 经销商ID           |                                            |
| office_name     | String | 经销商名称         |                                            |
| last_time       | String | 绑定设备离线时间戳 |                                            |
|                 |        |                    |                                            |

示例:

{

"status": {

"code": 0,

"reasonPhrase": "SUCCESS"

},

"data": {

"49d0edb6a796460394393c1f349ba17d": [

{

"id": "487bc6e197704587874d9cc8a4b61aww",

"isNewRecord": false,

"create_date": -1,

"update_date": -1,

"device_id": "a9a834c6cc2043f58da0001281df68cc",

"device_name": "D000003ON9A",

"owner_id": "",

"user_id": "487bc6e197704587874d9cc8a4b61a82",

"user_name": "88888888888",

"team_id": "49d0edb6a796460394393c1f349ba17d",

"team_name": "ceshi",

"temp_owner_id": "487bc6e197704587874d9cc8a4b61a82",

"temp_owner_name": "88888888888",

"office_id": "b84cbed292f144f2819db846c40a46f7",

"office_name": "V3测试环境(勿删)",

"own_flag": 2,

"account_id": "D000003ON9A",

"account_secret":
"61ddde95e7a3be7a1f51658dc3730849cfb996569641fbf8cf56b5275ac72ba7",

"valid_date": "2018-11-30 14:15:41.0",

"status": "2",

"binding_id": "fb649aa78a1546eb9041da239153aaee",

"binding_name": "测试RTK",

"lon": 0,

"lat": 0,

"last_time": 1543214881000

},

{

"id": "487bc6e197704587874d9cc8a4b61aqq",

"isNewRecord": false,

"create_date": -1,

"update_date": -1,

"device_id": "a9a828572bf64306b3bd34ecb8a26cfc",

"device_name": "D000003ONCM",

"owner_id": "487bc6e197704587874d9cc8a4b61a82",

"owner_name": "88888888888",

"user_id": "487bc6e197704587874d9cc8a4b61a82",

"user_name": "88888888888",

"office_id": "b84cbed292f144f2819db846c40a46f7",

"office_name": "V3测试环境(勿删)",

"own_flag": 1,

"account_id": "D000003ONCM",

"account_secret":
"61ddde95e7a3be7a1f51658dc3730849cfb996569641fbf8cf56b5275ac72ba7",

"valid_date": "2018-11-30 14:15:36.0",

"status": "5",

"lon": 0,

"lat": 0,

"last_time": 0

}

]

}

}

查询已租赁设备列表
--------------------------

### 程序描述

查询设备使用表中临时所有人是我的设备列表.

### 功能

查询设备使用表中临时所有人是我的设备列表。

### 性能

无

### 请求方式

>   POST

### 请求地址

> /api/deviceUser/findRentDevices

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| owner_id | String | 用户ID   |      |
| device_category| String | 设备类别                     |设备类别 用于识别设备:无人机:1;rtk:2;千寻账号:3   默认为1.无人机       |
| page_count   | String | 每页数量                        |          |
| current_page | String | 当前页码                        |          |
| order_by     | String | 当前排序依据，默认为create_time |          |
| order_model  | String | 当前排序方式，默认为1(desc)     |          |
| device_name  | String | 无人机名称                      | 模糊查询 |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名        | 类型   | 中文意义 | 说明 |
|---------------|--------|----------|------|
| device_id     | String | 设备ID   |      |
| device_name | String | 设备名称 |      |

示例:

>{

>"status":{"code":0,"reasonPhrase":"SUCCESS"},

>"data":{

>   "list":[{

>   " device_id ":"\*\*\*",

>   " device \_name ":"\*\*\*"

>   },{

>   " device_id ":"\*\*\*",

>   " device \_name ":"\*\*\*"

>   }]

>   }

>}

根据设备ID,团队ID查询已分配队员列表
--------------------------

### 程序描述

根据设备ID,团队ID查询已分配队员列表,已被分配队员,distribute_flag = 1;未被分配队员distribute_flag=0

### 功能

根据设备ID,团队ID查询已分配队员列表,已被分配队员,distribute_flag = 1;未被分配队员distribute_flag=0

### 性能

无

### 请求方式

>   POST

### 请求地址

> /api/deviceUser/findMemberList

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|----------|--------|------|------|
| device_id| String | 设备ID|      |
| team_id  | String | 团队ID|      |


### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名        | 类型   | 中文意义 | 说明 |
|---------------|--------|----------|------|
| device_id     | String | 设备ID   |      |
| user_id | String | 团队成员ID |      |
| team_id | String | 团队ID |      |
| distribute_flag | String | 分配标识 |1:已分配;0:未分配      |

示例:

>{

>"status":{"code":0,"reasonPhrase":"SUCCESS"},

>"data":{

>   "list":[{

>   " device_id ":"\*\*\*",

>   " user_id ":"\*\*\*",
>   " team_id ":"\*\*\*",

>   " distribute_flag ":"\*\*\*"


>   },{

>   "list":[{

>   " device_id ":"\*\*\*",

>   " user_id ":"\*\*\*",
>   " team_id ":"\*\*\*",

>   " distribute_flag ":"\*\*\*"

>   }]

>   }

>}

设备问题类型字典表
--------------------------
### 程序描述

查询设备问题类型字典表

### 功能

查询设备问题类型字典表

### 性能

无

### 请求方式

>   GET

### 请求地址

> /api/dict/findByType?type=device_issue_type

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|----------|--------|------|------|
| type| String | 字典类型|      |



### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名        | 类型   | 中文意义 | 说明 |
|---------------|--------|----------|------|
| id     | String | 字典ID   |      |
| value | String | 数据值 |      |
| label | String | 标签名 |      |
| type | String | 类型 |     |
| description | String | 描述 |      |
| sort | String | 排序 |      |
| parentId | String | 父Id |     |

示例:

>{

>"status":{"code":0,"reasonPhrase":"SUCCESS"},

>"data":{

>   "list":[{

>   " id ":"\*\*\*",

>   " value ":"\*\*\*",
>   " label ":"\*\*\*",

>   " type ":"\*\*\*"
>   " description ":"\*\*\*",
>   " sort ":"\*\*\*",

>   " parentId ":"\*\*\*"

>   },{

>   "list":[{

>   " id ":"\*\*\*",

>   " value ":"\*\*\*",
>   " label ":"\*\*\*",

>   " type ":"\*\*\*"
>   " description ":"\*\*\*",
>   " sort ":"\*\*\*",

>   " parentId ":"\*\*\*"

>   }]

>   }

>}




无人机类型字典表
--------------------------

### 程序描述

查询无人机类型字典表

### 功能

查询无人机类型字典表

### 性能

无

### 请求方式

>   GET

### 请求地址

> /api/dict/findByType?type=uav_type_web

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|----------|--------|------|------|
| type| String | 字典类型|      |



### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名        | 类型   | 中文意义 | 说明 |
|---------------|--------|----------|------|
| id    | String | 字典ID   |      |
| value | String | 数据值 |      |
| label | String | 标签名 |      |
| type | String | 类型 |     |
| description | String | 描述 |      |
| sort | String | 排序 |      |
| parentId | String | 父Id |     |

示例:

>{

>"status":{"code":0,"reasonPhrase":"SUCCESS"},

>"data":{

>   "list":[{

>   " id ":"\*\*\*",

>   " value ":"\*\*\*",
>   " label ":"\*\*\*",

>   " type ":"\*\*\*"
>   " description ":"\*\*\*",
>   " sort ":"\*\*\*",

>   " parentId ":"\*\*\*"

>   },{

>   "list":[{
>   " id ":"\*\*\*",
>   " value ":"\*\*\*",
>   " label ":"\*\*\*",
>   " type ":"\*\*\*"
>   " description ":"\*\*\*",
>   " sort ":"\*\*\*",
>   " parentId ":"\*\*\*"

>   }]

>   }

>}


获取RTK流量详情
------------------
### 程序描述
    根据RTK_ID获取RTK设备流量详情。
### 功能
    根据RTK_ID获取RTK设备流量详情。
### 性能
无
### 请求方式
POST
### 请求地址
>  /api/flowCardRtkInfo/getFlowCardRtk
### 输入

|参数名	    |类型	|中文意义	   |说明   |
|-----------|-------|----------|------|
|device_id	|String	|RTK设备ID  |	  |

### 输出
JSON格式数据如下：
{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

|参数名	            |类型	    |中文意义	                   |说明          |
|-------------------|-------|------------------------------|------------|
|id					|String	|id	                           |         	|
|appid				|String	|应用编码	                       |            |
|ebid				|String	|能力编码	                       |            |
|password			|String	|流量卡密码	                   |            |
|flow_card_id		|String	|流量卡id	                       |            |
|flow_total			|String	|总流量	                       |	        |
|flow_left			|String	|剩余流量	                       |            |
|flow_used			|String	|已用流量	                       |            |
|device_id			|String	|设备id	                       |	        |
|version			|String	|版本号	                       |	        |
|qx_account			|String	|千寻账号	                       |            |
|work_mode			|String	|工作模式1-数传，2-大数据，3-千寻网络|             |
|device_type		|String	|设备类型1-基站，2-采点器，3-机载Rtk|            |
|base_station_id	|String	|基站id	                       |    	    |
|bind_state			|String	|绑定状态	                       |	        |
|accuracy_degree	|String	|精度等级                        | 	        |

示例:
>{
>	"status":{"code":0,"reasonPhrase":"SUCCESS"},
>	"data":{
>	"id":"***",
>"appid":"***",
>"ebid":"***",
>"password":"***",
>"flow_card_id":"***",
>"flow_total":"***",
>"flow_left":"***",
>"flow_used":"***",
>"device_id":"***",
>"version":"***",
>"qx_account":"***",
>"work_mode":"***",
>"device_type":"***",
>"base_station_id":"***",
>"bind_state":"***",
>"accuracy_degree":"***"
>}
>}

千寻账号详情
-----------

### 程序描述

根据ID获取千寻账号详情。

### 功能

根据ID获取千寻账号详情。

### 性能

无

### 请求方式

>   POST

### 请求地址

> /api/qxAccount/getByDeviceId

### 输入

| 参数名 | 类型   | 中文意义  | 说明 |
|--------|--------|-----------|------|
| device_id | String | 千寻账号ID |    |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名          | 类型   | 中文意义           | 说明                                       |
|-----------------|--------|--------------------|--------------------------------------------|
| id              | String | ID               |                                            |
| account_id      | String | 千寻账号ID         |                                            |
| account_secret  | String | 千寻账号密码       |                                            |
| status          | String | 账号状态           | 1: 未激活，2：服务中，3：暂停，5：即将到期 |
| valid_date      | String | 有效期至           |                                            |
| device_id       | String | 千寻账号ID         |                                            |
| device_name     | String | 千寻账号           |                                            |
| owner_id        | String | 设备拥有者ID       |                                            |
| owner_name      | String | 设备拥有者名称     |                                            |
| user_id         | String | 设备使用者ID       |                                            |
| user_name       | String | 设备使用者名称     |                                            |
| temp_owner_id   | String | 设备租赁者ID       |                                            |
| temp_owner_name | String | 设备租赁者名称     |                                            |
| team_id         | String | 团队ID             |                                            |
| team_name       | String | 团队名称           |                                            |
| binding_id      | String | 绑定RTK ID         |                                            |
| binding_name    | String | 绑定RTK名称        |                                            |
| office_id       | String | 经销商ID           |                                            |
| office_name     | String | 经销商名称         |                                            |
| last_time       | String | 绑定设备离线时间戳 |                                            |
|                 |        |                    |                                            |

RTK设备报废
----------------

### 程序描述

RTK设备报废。

### 功能

RTK设备报废。

### 性能

无

### 请求方式

>   POST

### 请求地址

>   /api/rtk/abolish
### 输入

| 参数名      | 类型    | 中文意义  | 说明 |
|------------|--------|---------|------|
| device_id  | String | 设备ID   |      |
| remarks    | String | 备注信息  |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}"}



联盟管理部分接口
================

创建联盟
--------

### 程序描述

创建联盟。

### 功能

创建联盟。

### 性能

无

### 请求方式

>   POST

### url地址

>   /api/union/addUnion

### 输入

| 参数名       | 类型   | 中文意义         | 说明            |
|--------------|--------|------------------|-----------------|
| user_id      | String | 用户id           |                 |
| union_name   | String | 联盟名称         |                 |
| ident_flag   | String | 团队需要认证标识 | 0:不需要;1:需要 |
| publish_flag | String | 允许团队发布需求 | 0:允许;1:不允许 |
| remarks      | String | 备注             |                 |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}"}

编辑联盟
--------

### 程序描述

编辑联盟。

### 功能

编辑联盟。

### 性能

无

### 请求方式

>   POST

### url地址

>   /api/union/updateUnion

### 输入

| 参数名       | 类型   | 中文意义         | 说明            |
|--------------|--------|------------------|-----------------|
| user_id      | String | 用户id           |                 |
| union_id     | String | 联盟ID           |                 |
| union_name   | String | 联盟名称         |                 |
| ident_flag   | String | 团队需要认证标识 | 0:不需要;1:需要 |
| publish_flag | String | 允许团队发布需求 | 0:允许;1:不允许 |
| remarks      | String | 备注             |                 |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}"}

联盟列表
--------

### 程序描述

查询用户所在联盟列表。

### 功能

查询用户所在联盟列表。

### 性能

无

### 请求方式

>   GET

### url地址

>   /api/union/findUnionList

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| user_id | String | 用户ID   |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名         | 类型   | 中文意义     | 说明 |
|----------------|--------|--------------|------|
| user_id        | String | 用户ID       |      |
| union_id       | String | 联盟ID       |      |
| union_name     | String | 联盟名称     |      |
| union_logo_url | String | 联盟logo URL |      |
| apply_count    | String | 待审核数量   |      |
| team_count     | String | 团队数量     |      |
| order_count    | String | 联盟订单数量 |      |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

>   "list":[{

>   "user_id":"\*\*\*",

>   "union_id":"\*\*\*",

>   "union_name":"\*\*\*",

>   "union_logo_url":"\*\*\*",

>   "apply_count":"\*\*\*",

>   "team_count":"\*\*\*",

>   "order_count":"\*\*\*"

>   },{

>   "user_id":"\*\*\*",

>   "union_id":"\*\*\*",

>   "union_name":"\*\*\*",

>   "union_logo_url":"\*\*\*",

>   "apply_count":"\*\*\*",

>   "team_count":"\*\*\*",

>   "order_count":"\*\*\*"

>   }]

>   }

}

联盟详情
--------

### 程序描述

根据联盟ID查看联盟详情。

### 功能

根据联盟ID查看联盟详情.

### 性能

无

### 请求方式

>   GET

### url地址

>   /api/union/findUnionInfo

### 输入

| 参数名   | 类型   | 中文意义 | 说明 |
|----------|--------|----------|------|
| union_id | String | 联盟ID   |      |

### 输出

JSON格式数据如下：

{“status":”{code=0, reasonPhrase=SUCCESS}","data":"{}"}

data:List\<TeamInfo \>，其中FORM BEAN类名：TeamInfo

| 参数名       | 类型   | 中文意义         | 说明            |
|--------------|--------|------------------|-----------------|
| union_id     | String | 联盟ID           |                 |
| union_name   | String | 联盟名称         |                 |
| ident_flag   | String | 团队需要认证标识 | 0:不需要;1:需要 |
| publish_flag | String | 允许团队发布需求 | 0:允许;1:不允许 |
| remarks      | String | 备注             |                 |
| code_url     | String | 联盟二维码URL    |                 |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

>   "union_id":"\*\*\*",

>   "union_name":"\*\*\*",

>   "ident_flag":"\*\*\*",

>   "publish_flag":"\*\*\*",

>   "remarks":"\*\*\*"

}

}

联盟团队列表
------------

### 程序描述

查询用户所在联盟列表。

### 功能

查询用户所在联盟列表。

### 性能

无

### 请求方式

>   GET

### url地址

>   /api/union/findUnionTeamList

### 输入

| 参数名   | 类型   | 中文意义 | 说明 |
|----------|--------|----------|------|
| union_id | String | 联盟ID   |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名    | 类型   | 中文意义           | 说明                   |
|-----------|--------|--------------------|------------------------|
| union_id  | String | 联盟ID             |                        |
| team_id   | String | 团队ID             |                        |
| team_name | String | 团队名称           |                        |
| role_flag | String | 在团队中的角色标识 | 0:成员;1:盟主所在团队; |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

>   "list":[{

>   "union_id":"\*\*\*",

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "role_flag":"\*\*\*"

>   },{

>   "union_id":"\*\*\*",

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "role_flag":"\*\*\*"

>   }]

>   }

}

邀请加入联盟
------------

### 程序描述

返回加入联盟二维码信息。

### 功能

返回加入联盟二维码信息。

### 性能

无

### 请求方式

>   GET

### url地址

>   /api/union/inviteUnion

### 输入

| 参数名   | 类型   | 中文意义 | 说明 |
|----------|--------|----------|------|
| union_id | String | 联盟ID   |      |
| user_id  | String | 用户ID   |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名       | 类型   | 中文意义      | 说明 |
|--------------|--------|---------------|------|
| union_id     | String | 联盟ID        |      |
| user_id      | String | 用户ID        |      |
| union \_name | String | 联盟名称      |      |
| user_name    | String | 用户名称      |      |
| leader_id    | String | 盟主ID        |      |
| leader_name  | String | 盟主名称      |      |
| code_url     | String | 联盟二维码URL |      |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

>   "list":[{

>   "union_id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "union_name":"\*\*\*",

>   "user_name":"\*\*\*",

>   "leader_id":"\*\*\*",

>   "leader_name":"\*\*\*",

>   "code_url":"\*\*\*"

>   },{

>   "union_id":"\*\*\*",

>   "user_id":"\*\*\*",

>   "union_name":"\*\*\*",

>   "user_name":"\*\*\*",

>   "leader_id":"\*\*\*",

>   "leader_name":"\*\*\*",

>   "code_url":"\*\*\*"

>   }]

>   }

}

联盟申请加入
------------

### 程序描述

**申请加入联盟**。

### 功能

**申请加入联盟**。

### 性能

无

### 请求方式

>   POST

### url地址

>   /api/union/applyJoinUnion

### 输入

| 参数名   | 类型   | 中文意义 | 说明       |
|----------|--------|----------|------------|
| team_id  | String | 团队id   | 申请团队ID |
| user_id  | String | 申请人ID |            |
| union_id | String | 联盟ID   |            |
| remarks  | String | 申请理由 |            |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}"}

联盟申请列表
------------

### 程序描述

分页查询联盟申请列表。

### 功能

分页查询联盟申请列表。

### 性能

无

### 请求方式

>   POST

### url地址

/api/union/queryUnionTeamJoinList

### 输入

| 参数名       | 类型   | 中文意义                        | 说明 |
|--------------|--------|---------------------------------|------|
| union_id     | String | 联盟ID                          |      |
| page_count   | String | 每页数量                        |      |
| current_page | String | 当前页码                        |      |
| order_by     | String | 当前排序依据，默认为create_date |      |
| order_model  | String | 当前排序方式，默认为1(desc)     |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名       | 类型   | 中文意义           | 说明                   |
|--------------|--------|--------------------|------------------------|
| id           | String | 联盟团队关系表ID   |                        |
| union_id     | String | 联盟ID             |                        |
| union_name   | String | 联盟名称           |                        |
| apply_id     | String | 申请人ID           |                        |
| apply_name   | String | 申请人名称         |                        |
| team_id      | String | 团队ID             |                        |
| team_name    | String | 团队名称           |                        |
| apply_flag   | String | 在团队中的角色标识 | 0:待审核;1:通过;2:拒绝 |
| remarks      | String | 申请原因           |                        |
| work_acreage | String | 作业经验           | 亩                     |
| member_count | String | 成员数量           |                        |
| uav_count    | String | 无人机数量         |                        |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

"total":20,

>   "list":[{

>   "apply_id":"\*\*\*",

>   "apply_name":"\*\*\*",

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "apply_flag":"\*\*\*",

>   "remarks":"\*\*\*",

>   "work_acreage":"\*\*\*",

>   "member_count":"\*\*\*",

>   "uav_count":"\*\*\*"

>   },{

>   "apply_id":"\*\*\*",

>   "apply_name":"\*\*\*",

>   "team_id":"\*\*\*",

>   "team_name":"\*\*\*",

>   "apply_flag":"\*\*\*",

>   "remarks":"\*\*\*",

>   "work_acreage":"\*\*\*",

>   "member_count":"\*\*\*",

>   "uav_count":"\*\*\*"

>   }]

>   }

}

审批联盟申请
--------------------

### 程序描述

>   审批加入联盟申请。

### 功能

>   审批加入联盟申请。

### 性能

无

### 请求方式

>   POST

### url地址

>   /api/union/handleUnionApplication

### 输入

| 参数名   | 类型   | 中文意义 | 说明                      |
|----------|--------|----------|---------------------------|
| apply_id | String | 申请id   | 申请团队ID                |
| status   | String | 状态     | 状态:0:待审批;1通过;2拒绝 |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}"}



解散联盟(未登记)
------------------------
### 程序描述
 解散联盟。
###	功能
删除联盟和联盟植保队关系表。
###	性能
无
###	请求方式
>POST
###	url地址
	/api/union/dismissUnion

###	输入

|参数名   |	    类型|   	中文意义|   	说明|
|---------|--------|-------|-------|
|union_id|	String|	联盟id|	联盟id|
|user_id|	String|	用户ID|	用户ID|

###	输出
JSON格式数据如下：
{"status":"{code=0, reasonPhrase=SUCCESS}"}

盟主权限转让(未登记)
-----------------------
###	程序描述
    盟主权限转让。
###	功能
    盟主权限转让。
###	性能
   无
###	请求方式
>POST
###	url地址
	/api/union/transferUnionTeamAuthority
###	输入

|参数名   |   	类型|	中文意义|	  说明|
|--------|--------|-------|-------|
|union_id|	String|	联盟id|	联盟id|
|user_id|	String|	用户ID|	用户ID|
|team_id|String|植保队ID|	植保队ID|

###	输出
JSON格式数据如下：
{"status":"{code=0, reasonPhrase=SUCCESS}"}

退出联盟(未登记)
---------------
###	程序描述
    退出联盟。
###	功能
退出。
###	性能
无
###	请求方式
>POST
###	url地址
	/api/union/exitUnionTeam


###	输入

|参数名   |	    类型|	中文意义|	  说明|
|--------|--------|-------|---------|
|union_id|	String|	联盟id|	联盟id|
|user_id|	String|	用户ID|	用户ID|
|team_id|   String|	植保队ID|植保队ID|

###	输出
JSON格式数据如下：
{"status":"{code=0, reasonPhrase=SUCCESS}"}

移除联盟团队(未登记)
------------
###	程序描述
    移除联盟团队。
###	功能
移除联盟团队。
###	性能
无
###	请求方式
>POST
###	url地址
	/api/union/removeUnionTeam



###	输入

|参数名   |	    类型| 	中文意义|	  说明|
|--------|--------|--------|----------|
|union_id|	String|	联盟id|	联盟id|
|user_id|	String|	用户ID|	用户ID|
|team_id|  String|	植保队ID|植保队ID|

###	输出
JSON格式数据如下：
{"status":"{code=0, reasonPhrase=SUCCESS}"}






个人中心部分接口
================

沙盘统计（未登记）
------------------

### 程序描述

沙盘统计。

### 功能

沙盘统计

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| user_id | String | 联盟ID   |      |

JSON格式数据如下：

{

" user_id":"\*\*\*"

}

### 输出

>   列表:

| 参数名       | 类型   | 中文意义       | 说明 |
|--------------|--------|----------------|------|
| user_id      | String | 用户id         |      |
| acreage      | String | 总作业面积     |      |
| work_acreage | String | 已完成作业面积 |      |
| uav_count    | String | 无人机数量     |      |
| member_count | String | 参与人数       |      |

JSON格式数据如下：

{

>   "status":"{code=0, reasonPhrase=SUCCESS}",

>   "data":{

"user_id":"\*\*\*",

>   "acreage":"\*\*\*",

>   "work_acreage":"\*\*\*",

>   "uav_count":"\*\*\*",

>   "member_count":"\*\*\*"

>   }

}

我的订单列表（未登记）
----------------------

### 程序描述

分页查询联盟订单列表信息。

### 功能

分页查询联盟订单列表信息

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名       | 类型   | 中文意义                        | 说明                                                      |
|--------------|--------|---------------------------------|-----------------------------------------------------------|
| user_id      | String | 用户ID                          |                                                           |
| current_page | String | 当前分页，默认为1               |                                                           |
| order_by     | String | 当前排序依据，默认为create_time |                                                           |
| order_model  | String | 当前排序方式，默认为1(desc)     |                                                           |
| page_count   | String | 每页数量，默认为10              |                                                           |
| search       | String | 根据订单名称搜索相应订单        |                                                           |
| status       | String | 订单状态                        | 0:我发布的;1:我申请的(默认为空表示查询全部)               |
| sub_status   | String | 分类状态                        | 0:招募中;1:停止招募;2:已完成; 0:待审核;1:进行中;2:已完成; |

>   示例:

>   {

>   “user_id”:”\*\*\*\*”,

>   “current_page” : 1,

>   “order_by”:” create_time”,

>   “order_model” : 1,

>   “page_count”: 10,

>   “search”:”\*\*\*\*”,

>   }

### 输出

>   格式: JSON

>   列表:

| 参数名               | 类型   | 中文意义             | 说明                                              |
|----------------------|--------|----------------------|---------------------------------------------------|
| id                   | String | 订单id               |                                                   |
| order_name           | String | 订单名称             |                                                   |
| order_acreage        | String | 订单面积             |                                                   |
| order_unit_price     | String | 每亩价格             |                                                   |
| order_pesticide_type | String | 用药类型             |                                                   |
| order_create_time    | Date   | 创建时间             | 返回数据是毫秒                                    |
| order_time_start     | Date   | 开始时间             | 返回数据是毫秒                                    |
| order_time_end       | Date   | 结束时间             | 返回数据是毫秒                                    |
| order_position       | String | 作业地址             |                                                   |
| location             | String | 地址坐标             | 返回地块经纬度,以’,’分割                          |
| publish_type         | int    | 发布类型             | 0:大厅;1联盟;2:团队;3:个人                        |
| union_id             | String | 联盟ID               | publish_type为1时不为空                           |
| team_id              | String | 团队ID               | publish_type为1或2时不为空                        |
| ident_flag           | Int    | 团队认证标识         | 0:团队不需要认证 1:团队需要认证                   |
| offer_lunch          | Int    | 提供工作餐标识       | 0:不提供;1:提供                                   |
| offer_hotel          | Int    | 提供住宿标识         | 0:不提供;1:提供                                   |
| offer_charge         | Int    | 提供电池充电标识     | 0:不提供;1:提供                                   |
| offer_logistics      | Int    | 提供后勤服务         | 0:不提供;1:提供                                   |
| offer_pesticide      | Int    | 需求方包药           | 0:不包;1:包                                       |
| show_phone           | Int    | 对外显示手机号标识   | 0:不显示;1:显示                                   |
| show_data            | Int    | 对外公开作业数据标识 | 0:不公开;1:公开                                   |
| order_require        | Int    | 作业要求标识         | 0:不需要;1:需要                                   |
| order_fly_height     | String | 飞行高度             | 单位:米                                           |
| order_fly_velocity   | String | 飞行速度             | 米/秒                                             |
| order_remark         | String | 备注                 |                                                   |
| user_number          | String | 联系方式             | 农户手机                                          |
| publish_status       | Int    | 订单发布状态         | 0:招募中;1:停止招募;2:已完成                      |
| city_id              | String | 地块行政区ID         | 市级行政区ID                                      |
| order_pesticide      | String | 农药名称             |                                                   |
| contact_name         | String | 联系人姓名           |                                                   |
| contact_phone        | String | 联系人手机号         |                                                   |
| order_crop           | String | 订单作物             |                                                   |
| order_crop_type      | String | 作物类型             |                                                   |
| apply_acreage        | String | 申请面积             |                                                   |
| apply_time           | Date   | 申请时间             | 返回数据是毫秒                                    |
| apply_status         | String | 申请状态             | 0:待审核;1:进行中(同意);2:已完成;3:拒绝;(默认为0) |
| mapping_acreage      | String | 测绘面积             |                                                   |
| work_acreage         | String | 作业面积             |                                                   |
| update_by            | String | 更新人               |                                                   |
| update_date          | String | 更新时间             |                                                   |

>   示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{"total":13,

"list":[{

"id":"\*\*\*",

>   "order_name":"\*\*\*",

>   "order_acreage":"\*\*\*",

>   "order_unit_price":"\*\*\*",

>   "order_pesticide_type":"\*\*\*",

>   "order_create_time":"\*\*\*",

>   "order_time_start":"\*\*\*",

>   "order_time_end":"\*\*\*",

>   "order_position":"\*\*\*",

>   "location":"\*\*\*",

>   "publish_type":"\*\*\*",

>   "union_id":"\*\*\*",

>   "team_id":"\*\*\*",

>   "ident_flag":"\*\*\*",

>   "offer_lunch":"\*\*\*",

>   "offer_hotel":"\*\*\*",

>   "offer_charge":"\*\*\*",

>   "offer_logistics":"\*\*\*",

>   "offer_pesticide":"\*\*\*",

>   "show_phone":"\*\*\*",

>   "show_data":"\*\*\*",

>   "order_require":"\*\*\*",

>   "order_fly_height":"\*\*\*",

>   "order_fly_velocity":"\*\*\*",

>   "order_remark":"\*\*\*",

>   "user_number":"\*\*\*",

>   "publish_status":"\*\*\*",

>   "city_id":"\*\*\*",

>   "order_pesticide":"\*\*\*",

>   "contact_name":"\*\*\*",

>   "contact_phone":"\*\*\*",

>   "order_crop":"\*\*\*",

>   "order_crop_type":"\*\*\*",

>   "mapping_acreage":"\*\*\*",

>   "work_acreage":"\*\*\*",

>   "update_by":"\*\*\*",

>   "update_date":"\*\*\*"

},

{

"id":"\*\*\*",

>   "order_name":"\*\*\*",

>   "order_acreage":"\*\*\*",

>   "order_unit_price":"\*\*\*",

>   "order_pesticide_type":"\*\*\*",

>   "order_create_time":"\*\*\*",

>   "order_time_start":"\*\*\*",

>   "order_time_end":"\*\*\*",

>   "order_position":"\*\*\*",

>   "location":"\*\*\*",

>   "publish_type":"\*\*\*",

>   "union_id":"\*\*\*",

>   "team_id":"\*\*\*",

>   "ident_flag":"\*\*\*",

>   "offer_lunch":"\*\*\*",

>   "offer_hotel":"\*\*\*",

>   "offer_charge":"\*\*\*",

>   "offer_logistics":"\*\*\*",

>   "offer_pesticide":"\*\*\*",

>   "show_phone":"\*\*\*",

>   "show_data":"\*\*\*",

>   "order_require":"\*\*\*",

>   "order_fly_height":"\*\*\*",

>   "order_fly_velocity":"\*\*\*",

>   "order_remark":"\*\*\*",

>   "user_number":"\*\*\*",

>   "publish_status":"\*\*\*",

>   "city_id":"\*\*\*",

>   "order_pesticide":"\*\*\*",

>   "contact_name":"\*\*\*",

>   "contact_phone":"\*\*\*",

>   "order_crop":"\*\*\*",

>   "order_crop_type":"\*\*\*",

>   "mapping_acreage":"\*\*\*",

>   "work_acreage":"\*\*\*",

>   "update_by":"\*\*\*",

>   "update_date":"\*\*\*"

}

]}

}

市级行政区列表
--------------

### 程序描述

查询市级行政区列表。

### 功能

查询市级行政区列表。

### 性能

无

### 请求方式

>   POST

### 输入

无

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名        | 类型   | 中文意义       | 说明            |
|---------------|--------|----------------|-----------------|
| city_id       | String | 市级行政区ID   |                 |
| city_name     | String | 市级行政区名称 |                 |
| province_id   | String | 省行政区ID     |                 |
| province_name | String | 省行政区名称   |                 |
| location      | String | 地理坐标       | 经纬度以”,”分隔 |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

>   "list":[{

>   "city_id":"\*\*\*",

>   "city_name":"\*\*\*",

>   "province_id":"\*\*\*",

>   "province_name":"\*\*\*",

>   "location":"\*\*\*"

>   },{

>   "city_id":"\*\*\*",

>   "city_name":"\*\*\*",

>   "province_id":"\*\*\*",

>   "province_name":"\*\*\*",

>   "location":"\*\*\*"

>   }]

>   }

}

根据地区ID获取用户地块列表（接口作废）
------------------------------------

### 程序描述

分页查询根据地区ID获取用户地块列表。

### 功能

分页查询根据地区ID获取用户地块列表。

### 性能

无

### 请求方式

>   POST

### 输入

| 参数名       | 类型   | 中文意义                        | 说明 |
|--------------|--------|---------------------------------|------|
| user_id      | String | 用户ID                          |      |
| area_id      | String | 行政区ID                        |      |
| page_count   | String | 每页数量                        |      |
| current_page | String | 当前页码                        |      |
| order_by     | String | 当前排序依据，默认为create_time |      |
| order_model  | String | 当前排序方式，默认为1(desc)     |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名           | 类型   | 中文意义     | 说明                             |
|------------------|--------|--------------|----------------------------------|
| block_id         | String | 地块ID       |                                  |
| name             | String | 地块名称     |                                  |
| location         | String | 地块位置坐标 | 经纬度以”,”分隔                  |
| location_details | String | 地块坐标详情 | 经纬度以”,”分隔;点与点以”\|”分隔 |
| uav_count        | String | 无人机数量   |                                  |
| uav_list         | Array  | 无人机ID列表 |                                  |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

"total":20,

>   "list":[{

>   "block_id":"\*\*\*",

>   "name":"\*\*\*",

>   "location":"\*\*\*",

>   "location_details":"\*\*\*",

>   "uav_count":"\*\*\*",

>   "uav_list":[{

>   "device_id":"\*\*\*"

>   },{

>   "device_id":"\*\*\*"

>   }]

>   },{

>   "block_id":"\*\*\*",

>   "name":"\*\*\*",

>   "location":"\*\*\*",

>   "location_details":"\*\*\*",

>   "uav_count":"\*\*\*",

>   "uav_list":[{

>   "device_id":"\*\*\*"

>   },{

>   "device_id":"\*\*\*"

>   }]

>   }]

>   }

}

地块设备作业详情（未登记）
--------------------------

### 程序描述

根据地块ID查询设备详情。

### 功能

根据地块ID查询设备详情。

### 性能

无

### 请求方式

>   GET

### 输入

| 参数名   | 类型   | 中文意义 | 说明 |
|----------|--------|----------|------|
| device_id   | String | 无人机ID |      |
| block_id | String | 地块ID   |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名        | 类型   | 中文意义       | 说明 |
|---------------|--------|----------------|------|
| device_id        | String | 无人机ID       |      |
| uav_name      | String | 无人机名称     |      |
| uav_logo_url  | String | 无人机logo URL |      |
| uav_code      | String | 无人机编码     |      |
| own_user_id   | String | 拥有者ID       |      |
| own_user_name | String | 拥有者姓名     |      |
| uav_version   | String | 设备型号       |      |
| location      | String | 定位地址       |      |
| location_time | String | 定位时间       |      |
| work_acreage  | String | 作业面积       |      |
| duration      | String | 飞行时长       |      |
| dist          | String | 飞行里程       |      |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

"device_id":"\*\*\*",

>   "uav_name":"\*\*\*",

>   "uav_logo_url":"\*\*\*",

>   "uav_code":"\*\*\*",

>   "own_user_id":"\*\*\*",

>   "own_user_name":"\*\*\*",

>   "uav_version":"\*\*\*",

>   "location":"\*\*\*",

>   "location_time":"\*\*\*",

>   "work_acreage":"\*\*\*",

>   "duration":"\*\*\*",

>   "dist":"\*\*\*"

}

新建反馈
--------

### 程序描述

创建联盟。

### 功能

创建联盟。

### 性能

无

### 请求方式

>   POST

### url地址

/api/personal/addFeedback

### 输入

| 参数名     | 类型    | 中文意义 | 说明                     |
|------------|---------|----------|--------------------------|
| user_id    | String  | 用户ID   |                          |
| type       | String  | 反馈类型 | 0:投诉;1:建议;2:功能缺陷 |
| contact_no | varchar | 联系号码 |                          |
| img1       | varchar | 图片1    |                          |
| img2       | varchar | 图片2    |                          |
| img3       | varchar | 图片3    |                          |
| img4       | varchar | 图片4    |                          |
| img5       | varchar | 图片5    |                          |
| img6       | varchar | 图片6    |                          |
| remarks    | varchar | 反馈内容 |                          |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}"}

反馈详情列表
------------

### 程序描述

分页查询反馈列表,同时查询反馈处理内容。

### 功能

分页查询反馈列表,同时查询反馈处理内容。

### 性能

无

### 请求方式

>   POST

### url地址

/api/personal/queryFeedbackList

### 输入

| 参数名       | 类型   | 中文意义                        | 说明 |
|--------------|--------|---------------------------------|------|
| user_id      | String | 用户ID                          |      |
| page_count   | String | 每页数量                        |      |
| current_page | String | 当前页码                        |      |
| order_by     | String | 当前排序依据，默认为create_time |      |
| order_model  | String | 当前排序方式，默认为1(desc)     |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名      | 类型    | 中文意义                               | 说明                     |
|-------------|---------|----------------------------------------|--------------------------|
| user_id     | String  | 用户ID                                 |                          |
| type        | String  | 反馈类型                               | 0:投诉;1:建议;2:功能缺陷 |
| contact_no  | varchar | 联系号码                               |                          |
| img1        | varchar | 图片1                                  |                          |
| img2        | varchar | 图片2                                  |                          |
| img3        | varchar | 图片3                                  |                          |
| img4        | varchar | 图片4                                  |                          |
| img5        | varchar | 图片5                                  |                          |
| img6        | varchar | 图片6                                  |                          |
| remarks     | varchar | 反馈内容                               |                          |
| company_id  | varchar | 来源ID                                 |                          |
|             |         |                                        |                          |
| feedback_id | varchar | 反馈ID                                 |                          |
| status      | int     | '处理状态:0:未处理;1处理中;2:处理完成' | 0                        |
| content     | varchar | 处理内容                               | 0                        |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

"total":20,

>   "list":[{

>   " user_id ":"\*\*\*",

>   " type ":"\*\*\*",

>   " contact_no ":"\*\*\*",

>   " img1":"\*\*\*",

>   " img2":"\*\*\*",

>   " img3":"\*\*\*",

>   “processes”:[

>   {

>   feedback_id:”\*\*\*”,

>   status:”\*\*\*”,

>   content:”\*\*\*”,

>   },{

>   feedback_id:”\*\*\*”,

>   status:”\*\*\*”,

>   content:”\*\*\*”,

>   }

>   ]

>   },{

>   " user_id ":"\*\*\*",

>   " type ":"\*\*\*",

>   " contact_no ":"\*\*\*",

>   " img1":"\*\*\*",

>   " img2":"\*\*\*",

>   " img3":"\*\*\*",

>   “processes”:[

>   {

>   feedback_id:”\*\*\*”,

>   status:”\*\*\*”,

>   content:”\*\*\*”,

>   },{

>   feedback_id:”\*\*\*”,

>   status:”\*\*\*”,

>   content:”\*\*\*”,

>   }

>   ]

>   }]

>   }

}

反馈详情
--------

### 程序描述

根据反馈ID获取反馈详细信息,同时查询反馈处理内容。

### 功能

根据反馈ID获取反馈详细信息,同时查询反馈处理内容。

### 性能

无

### 请求方式

>   POST

### url地址

/api/personal/queryFeedBack

### 输入

| 参数名 | 类型   | 中文意义 | 说明 |
|--------|--------|----------|------|
| id     | String | 反馈ID   |      |

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名      | 类型    | 中文意义                               | 说明                     |
|-------------|---------|----------------------------------------|--------------------------|
| user_id     | String  | 用户ID                                 |                          |
| type        | String  | 反馈类型                               | 0:投诉;1:建议;2:功能缺陷 |
| contact_no  | varchar | 联系号码                               |                          |
| img1        | varchar | 图片1                                  |                          |
| img2        | varchar | 图片2                                  |                          |
| img3        | varchar | 图片3                                  |                          |
| img4        | varchar | 图片4                                  |                          |
| img5        | varchar | 图片5                                  |                          |
| img6        | varchar | 图片6                                  |                          |
| remarks     | varchar | 反馈内容                               |                          |
| company_id  | varchar | 来源ID                                 |                          |
|             |         |                                        |                          |
| feedback_id | varchar | 反馈ID                                 |                          |
| status      | int     | '处理状态:0:未处理;1处理中;2:处理完成' | 0                        |
| content     | varchar | 处理内容                               | 0                        |

示例:

{

"status":{"code":0,"reasonPhrase":"SUCCESS"},

"data":{

"total":20,

>   "list":[{

>   " user_id ":"\*\*\*",

>   " type ":"\*\*\*",

>   " contact_no ":"\*\*\*",

>   " img1":"\*\*\*",

>   " img2":"\*\*\*",

>   " img3":"\*\*\*",

>   “processes”:[

>   {

>   feedback_id:”\*\*\*”,

>   status:”\*\*\*”,

>   content:”\*\*\*”,

>   },{

>   feedback_id:”\*\*\*”,

>   status:”\*\*\*”,

>   content:”\*\*\*”,

>   }

>   ]

>   },{

>   " user_id ":"\*\*\*",

>   " type ":"\*\*\*",

>   " contact_no ":"\*\*\*",

>   " img1":"\*\*\*",

>   " img2":"\*\*\*",

>   " img3":"\*\*\*",

>   “processes”:[

>   {

>   feedback_id:”\*\*\*”,

>   status:”\*\*\*”,

>   content:”\*\*\*”,

>   },{

>   feedback_id:”\*\*\*”,

>   status:”\*\*\*”,

>   content:”\*\*\*”,

>   }

>   ]

>   }]

>   }

}
订单管理部分接口
================

主页（作业统计）
----------------

### 程序描述

两个统计数据接口

1.  作业面积统计，包括总面积、作业面积、测绘面积、作业时长。

### 功能

按照当前用户，统计当前用户的作业面积，与订单情况。

### 请求方式

Get

**http://localhost:8182/plant-protection-platform/a/order/jobacc?user\_id=23**

### 输入

user\_id

### 输出

**1统计作业**

**{**

**\"status\": {**

**\"code\": 0,**

**\"reasonPhrase\": \"SUCCESS\"**

**},**

**\"data\": {**

**\"id\": \"123\",**

**\"total\_acreage\": \"222\", //**总面积

**\"task\_acreage\": \"222\", //**作业面积

**\"position\": \"2322\", //**测绘面积

**\"alliance\": \"2222\", //**作业时长

**\"user\_id\": \"2222\" //用户id**

**}**

**}**

主页（订单统计）
----------------

### 程序描述

两个统计数据接口

1订单统计，包括总的订单数量、招募中的订单数量、停止招募的订单数量、已完成的订单数量。

### 功能

按照当前用户，统计当前用户订单情况。

### 请求方式

Get

http://localhost:8182/plant-protection-platform/a/order/orderacc?user\_id=2

### 输入

user\_id

### 输出

**JSON格式数据如下：**

**{**

**\"status\": {**

**\"code\": 0,**

**\"reasonPhrase\": \"SUCCESS\"**

**},**

**\"data\": {**

**\"release\_order\": \"2\", //**发布订单

**\"recruiting\_order\": \"0\", //**招募中

**\"recruited\_order\": \"0\", //停止招募**

**\"completed\_order\": \"1\" //已完成**

**}**

**}**

订单管理(列表)
--------------

### 关于订单的返回值查询以下

private String id;\
private String order\_name; //订单名称\
private int order\_status;//订单发布状态 0:招募中;1:停止招募;2:已完成\
private String order\_position; //订单地址 order-crop\
private String crops\_id;//作物类型 code\
private String order\_crop;//作物名\
private String location; //地址坐标返回地块经纬度,以','分割publish-type\
private int publish\_type; //发布类型 0:大厅;1联盟;2:团队;3:个人\
private Double order\_acreage; //订单面积\
private Double mapping\_acreage;//测绘面积\
private Double work\_acreage;//作业面积\
private Double order\_unit\_price; //每亩单价\
private String order\_pesticide; //用药类型\
private String pesticide\_id; //用药类型id\
// \@JsonFormat(pattern = \"yyyy-MM-dd hh:mm:ss\")\
private Date order\_time\_start; //开始时间\
// \@JsonFormat(pattern = \"yyyy-MM-dd hh:mm:ss\")\
private Date order\_time\_end; //结束时间\
private String header\_image; //订单创建者头像\
private String order\_creater\_id; //创建者id\
private String order\_creater; //创建者\
// \@JsonFormat(pattern = \"yyyy-MM-dd hh:mm:ss\")\
private Date order\_create\_time;//创建时间\
private int work\_team;//作业团队数量\
private int work\_uav;//作业飞机数量\
private int work\_user;//作业人员数量\
private int provide\_meal;//提供工作餐标识 0:不提供;1:提供\
private int provide\_accommodation;//提供住宿标识 0:不提供;1:提供\
private int provide\_battery\_charging;//提供电池充电标识
0:不提供;1:提供\
private int provide\_post\_service;//提供后勤服务 0:不提供;1:提供\
private int provide\_drug;//需求方包药 0:不包;1:包\
private String order\_creater\_tel;//联系方式创建者\
private int work\_demand;//是否有作业要求 1：有 0：无\
private double max\_flying\_height;//飞行高度 单位:米\
private double max\_flying\_speed;//飞行速度 米/秒\
private String remark;//备注\
private String update\_by;\
private String update\_id;\
private String order\_by;\
private Integer order\_model;\
private String city\_id;//地块行政区ID 市级行政区ID\
\
private String union\_id; //联盟ID publishType为1时不为空\
private String union\_name;//联盟名称 publishType为1时不为空\
private String team\_id; //团队名称 publishType为1或2时不为空\
private String team\_name;//团队名称 publishType为1或2时不为空\
private int ident\_flag;//团队认证标识 0:团队不需要认证;1:团队需要认证\
private int shownumber\_flag;//对外显示手机号标识 0:不显示;1:显示\
private int showinfo\_flag;//对外公开作业数据标识 0:不公开;1:公开\
private int require\_flag;//作业要求标识 0:不需要;1:需要\
private List\<String\> teamlogolist;\
private Integer order\_team;\
private Integer total\_team;\
private List\<String\>
unionIds;//当前用户登录的当前团队的所属的所有的联盟的id
大厅列表时候使用\
private Integer is\_myself;//是不是当前用户创建的订单
在我的订单时候使用，0是我创建的 1是我申请的\
private String contactor;//联系人\
private String contactor\_phonenum;//联系人电话\
private Integer user\_type; //user类型 1飞手 2农户\
private Integer allandnotall;//接收参数是不是查询自己申请的和创建的
在我的订单中使用 其他地方不用 1我申请的 2我创建的\
private String team\_id\_ap; //申请的team\
private String team\_master\_id\_ap;//申请的team的队长\
private String team\_master\_or;//创建的team的队长\
private String team\_id\_or;//创建的team\
\
//订单详情中需要判断的6个属性\
private int
update\_flag;//订单是否可编辑标识0:可编辑;1不可编辑(默认为0)没有加入团队的申请，并且没有参与团队的订单可以编辑（植保队内部队员除外）。
其他情况不可编辑\
private int ismyap;//是我申请的吗 1是 0不是\
private Integer apply\_status;//订单发布状态\
private Integer work\_status;//申请表中的工作状态\
private int team\_master\_id\_ap\_isself;//本人是不是申请的团队的队长
1是 0不是\
private int isallocationme;//是不是分配给我的 1是 0不是\
private int ismyor;//是我创建的吗 1是 0不是\
private int team\_master\_or\_isself;//本人是不是创建团队的队长 1是0不是

### 程序描述

分页查询获取当前用户所有订单列表。

### 功能

按照此时登陆的用户，统计当前用户的所有订单列表

### 请求方式

Get

http://localhost:8182/plant-protection-platform/a/order/orderlistfarmer?page\_no=1&&page\_size=30&&user\_id=2

### 输入

  **参数名**    **类型**   **中文意义**   **说明**
  ------------- ---------- -------------- --------------------
  Order\_name   String     订单名称       按订单名称模糊查询
  Page\_size    String     每页数量
  Page\_no      String     当前页码

### 输出

{

\"status\": {

\"code\": 0,

\"reasonPhrase\": \"SUCCESS\"

},

\"data\": {

\"pageNo\": 1,

\"pageSize\": 30,

\"current\_page\": 1,

\"page\_count\": 30,

\"count\": 2,

\"list\": \[

{

\"id\": \"22\",

\"isNewRecord\": false,

\"order\_name\": \"22\",

\"order\_status\": 2,

\"order\_position\": \"2\",

\"crops\_id\": 2,

\"order\_crop\": \"韭菜\",

\"location\": \"2\",

\"publish\_type\": 2,

\"order\_acreage\": 2,

\"order\_unit\_price\": 2,

\"order\_pesticide\": \"除草剂\",

\"pesticide\_id\": \"2\",

\"order\_time\_start\": 1542080812000,

\"order\_time\_end\": 1542080814000,

\"order\_creater\_id\": \"2\",

\"order\_create\_time\": 1542080809000,

\"work\_team\": 0,

\"work\_uav\": 0,

\"provide\_meal\": 2,

\"provide\_accommodation\": 2,

\"provide\_battery\_charging\": 0,

\"provide\_post\_service\": 2,

\"provide\_drug\": 2,

\"order\_creater\_tel\": \"2\",

\"work\_demand\": 2,

\"max\_flying\_height\": 2,

\"max\_flying\_speed\": 2,

\"remark\": \"2\",

\"update\_by\": \"2\",

\"update\_id\": \"2\",

\"city\_id\": \"2\",

\"update\_flag\": 2,

\"union\_id\": \"2\",

\"union\_name\": \"2\",

\"team\_id\": \"2\",

\"team\_name\": \"2\",

\"ident\_flag\": 2,

\"shownumber\_flag\": 2,

\"showinfo\_flag\": 2,

\"require\_flag\": 0,

\"teamlogolist\": \[

\"asdas\",

\"asd\"

\],

\"order\_team\": 2,

\"total\_team\": 0

},

{

\"id\": \"4\",

\"isNewRecord\": false,

\"order\_name\": \"4\",

\"order\_status\": 0,

\"order\_position\": \"4\",

\"crops\_id\": 2,

\"order\_crop\": \"韭菜\",

\"location\": \"4\",

\"publish\_type\": 4,

\"order\_acreage\": 4,

\"order\_unit\_price\": 4,

\"pesticide\_id\": \"4\",

\"order\_time\_start\": 1542089933000,

\"order\_time\_end\": 1542089935000,

\"order\_creater\_id\": \"2\",

\"order\_create\_time\": 1542089930000,

\"work\_team\": 0,

\"work\_uav\": 0,

\"provide\_meal\": 0,

\"provide\_accommodation\": 0,

\"provide\_battery\_charging\": 0,

\"provide\_post\_service\": 0,

\"provide\_drug\": 0,

\"work\_demand\": 0,

\"max\_flying\_height\": 0,

\"max\_flying\_speed\": 0,

\"update\_id\": \"2\",

\"update\_flag\": 0,

\"ident\_flag\": 0,

\"shownumber\_flag\": 0,

\"showinfo\_flag\": 0,

\"require\_flag\": 0,

\"order\_team\": 0,

\"total\_team\": 0

}

\],

\"html\": \"\<ul\>\\n\<li class=\\\"disabled\\\"\>\<a
href=\\\"javascript:\\\"\>« 上一页\</a\>\</li\>\\n\<li
class=\\\"active\\\"\>\<a
href=\\\"javascript:\\\"\>1\</a\>\</li\>\\n\<li
class=\\\"disabled\\\"\>\<a href=\\\"javascript:\\\"\>下一页
»\</a\>\</li\>\\n\<li class=\\\"disabled controls\\\"\>\<a
href=\\\"javascript:\\\"\>当前 \<input type=\\\"text\\\" value=\\\"1\\\"
onkeypress=\\\"var e=window.event\|\|event;var
c=e.keyCode\|\|e.which;if(c==13)page(this.value,30,\'\');\\\"
onclick=\\\"this.select();\\\"/\> / \<input type=\\\"text\\\"
value=\\\"30\\\" onkeypress=\\\"var e=window.event\|\|event;var
c=e.keyCode\|\|e.which;if(c==13)page(1,this.value,\'\');\\\"
onclick=\\\"this.select();\\\"/\> 条，共 2
条\</a\>\</li\>\\n\</ul\>\\n\<div style=\\\"clear:both;\\\"\>\</div\>\",

\"firstResult\": 0,

\"maxResults\": 30

}

}

创建订单
--------

### 程序描述

农户创建订单

### 功能

农户创建订单

### 请求方式

Post

[[http://localhost:8182/plant-protection-platform/a/order/addorder]{.underline}](http://localhost:8182/plant-protection-platform/a/order/addorder)[]{#_Toc529536923
.anchor}
输入
+----------------------------+----------+----------------------+------------------+
| **参数名**                 | **类型** | **中文意义**         | **说明**         |
+============================+==========+======================+==================+
| order\_name                | String   | 订单名称             |                  |
+----------------------------+----------+----------------------+------------------+
| crops\_id                  | String   | 农作物id             |                  |
+----------------------------+----------+----------------------+------------------+
| work\_acreage              | D        | 订单面积             |                  |
+----------------------------+----------+----------------------+------------------+
| order\_unit\_price         | Double   | 每亩价格             |                  |
+----------------------------+----------+----------------------+------------------+
| pesticide\_id              | String   | 用药类型id           |                  |
+----------------------------+----------+----------------------+------------------+
| order\_time\_start         | Date     | 开始时间             |                  |
+----------------------------+----------+----------------------+------------------+
| order\_time\_end           | Date     | 结束时间             |                  |
+----------------------------+----------+----------------------+------------------+
| order\_position            | String   | 作业地址             |                  |
+----------------------------+----------+----------------------+------------------+
| location                   | String   | 地址坐标             | 没有             |
+----------------------------+----------+----------------------+------------------+
| ident\_flag                | Int      | 团队认证标识         | 0:团队不需要认证 |
|                            |          |                      |                  |
|                            |          |                      | 1:团队需要认证   |
+----------------------------+----------+----------------------+------------------+
| provide\_meal              | Int      | 提供工作餐标识       | 0:不提供;1:提供  |
+----------------------------+----------+----------------------+------------------+
| provide\_accommodation     | Int      | 提供住宿标识         | 0:不提供;1:提供  |
+----------------------------+----------+----------------------+------------------+
| provide\_battery\_charging | Int      | 提供电池充电标识     | 0:不提供;1:提供  |
+----------------------------+----------+----------------------+------------------+
| provide\_post\_service     | Int      | 提供后勤服务         | 0:不提供;1:提供  |
+----------------------------+----------+----------------------+------------------+
| provide\_drug              | Int      | 需求方包药           | 0:不包;1:包      |
+----------------------------+----------+----------------------+------------------+
| shownumber\_flag           | Int      | 对外显示手机号标识   | 0:不显示;1:显示  |
+----------------------------+----------+----------------------+------------------+
| showinfo\_flag             | Int      | 对外公开作业数据标识 | 0:不公开;1:公开  |
+----------------------------+----------+----------------------+------------------+
| work\_demand               | Int      | 作业要求标识         | 0:不需要;1:需要  |
+----------------------------+----------+----------------------+------------------+
| max\_flying\_height        | String   | 飞行高度             | 单位:米          |
+----------------------------+----------+----------------------+------------------+
| max\_flying\_speed         | String   | 飞行速度             | 米/秒            |
+----------------------------+----------+----------------------+------------------+
| remark                     | String   | 备注                 |                  |
+----------------------------+----------+----------------------+------------------+
| contactor\_phonenum        | String   | 联系方式             | 农户手机         |
+----------------------------+----------+----------------------+------------------+

### 输出

{

\"status\": {

\"code\": 0,

\"reasonPhrase\": \"SUCCESS\"

},

}

农药列表
--------

### 程序描述

农药字典表信息。

### 功能

### 性能

无

### 请求方式

GET

http://localhost:8182/plant-protection-platform/a/order/worktype

### 输入

无

### 输出

**JSON格式数据如下：**

{

\"status\": {

\"code\": 0,

\"reasonPhrase\": \"SUCCESS\"

},

\"data\": {

\"list\": \[

{

\"id\": \"1\",

\"wname\": \"杀虫剂\",

\"code\": \"1\"

},

{

\"id\": \"2\",

\"wname\": \"除草剂\",

\"code\": \"2\"

}

\]

}

}

农作物类型列表
--------------

### 程序描述

农作物类型字典表

### 功能

农药字典表信息

### 请求方式

Get

http://localhost:8182/plant-protection-platform/a/order/cropstype

### 输入

无

### 输出

{

\"status\": {

\"code\": 0,

\"reasonPhrase\": \"SUCCESS\"

},

\"data\": {

\"list\": \[

{

\"id\": \"1\",

\"cname\": \"白菜\",

\"code\": \"1\"

},

{

\"id\": \"2\",

\"cname\": \"韭菜\",

\"code\": \"2\"

}

\]

}

}

订单详情
--------

### 关于订单的返回值查询以下

private String id;\
private String order\_name; //订单名称\
private int order\_status;//订单发布状态 0:招募中;1:停止招募;2:已完成\
private String order\_position; //订单地址 order-crop\
private String crops\_id;//作物类型 code\
private String order\_crop;//作物名\
private String location; //地址坐标返回地块经纬度,以','分割publish-type\
private int publish\_type; //发布类型 0:大厅;1联盟;2:团队;3:个人\
private Double order\_acreage; //订单面积\
private Double mapping\_acreage;//测绘面积\
private Double work\_acreage;//作业面积\
private Double order\_unit\_price; //每亩单价\
private String order\_pesticide; //用药类型\
private String pesticide\_id; //用药类型id\
// \@JsonFormat(pattern = \"yyyy-MM-dd hh:mm:ss\")\
private Date order\_time\_start; //开始时间\
// \@JsonFormat(pattern = \"yyyy-MM-dd hh:mm:ss\")\
private Date order\_time\_end; //结束时间\
private String header\_image; //订单创建者头像\
private String order\_creater\_id; //创建者id\
private String order\_creater; //创建者\
// \@JsonFormat(pattern = \"yyyy-MM-dd hh:mm:ss\")\
private Date order\_create\_time;//创建时间\
private int work\_team;//作业团队数量\
private int work\_uav;//作业飞机数量\
private int work\_user;//作业人员数量\
private int provide\_meal;//提供工作餐标识 0:不提供;1:提供\
private int provide\_accommodation;//提供住宿标识 0:不提供;1:提供\
private int provide\_battery\_charging;//提供电池充电标识
0:不提供;1:提供\
private int provide\_post\_service;//提供后勤服务 0:不提供;1:提供\
private int provide\_drug;//需求方包药 0:不包;1:包\
private String order\_creater\_tel;//联系方式创建者\
private int work\_demand;//是否有作业要求 1：有 0：无\
private double max\_flying\_height;//飞行高度 单位:米\
private double max\_flying\_speed;//飞行速度 米/秒\
private String remark;//备注\
private String update\_by;\
private String update\_id;\
private String order\_by;\
private Integer order\_model;\
private String city\_id;//地块行政区ID 市级行政区ID\
\
private String union\_id; //联盟ID publishType为1时不为空\
private String union\_name;//联盟名称 publishType为1时不为空\
private String team\_id; //团队名称 publishType为1或2时不为空\
private String team\_name;//团队名称 publishType为1或2时不为空\
private int ident\_flag;//团队认证标识 0:团队不需要认证;1:团队需要认证\
private int shownumber\_flag;//对外显示手机号标识 0:不显示;1:显示\
private int showinfo\_flag;//对外公开作业数据标识 0:不公开;1:公开\
private int require\_flag;//作业要求标识 0:不需要;1:需要\
private List\<String\> teamlogolist;\
private Integer order\_team;\
private Integer total\_team;\
private List\<String\>
unionIds;//当前用户登录的当前团队的所属的所有的联盟的id
大厅列表时候使用\
private Integer is\_myself;//是不是当前用户创建的订单
在我的订单时候使用，0是我创建的 1是我申请的\
private String contactor;//联系人\
private String contactor\_phonenum;//联系人电话\
private Integer user\_type; //user类型 1飞手 2农户\
private Integer allandnotall;//接收参数是不是查询自己申请的和创建的
在我的订单中使用 其他地方不用 1我申请的 2我创建的\
private String team\_id\_ap; //申请的team\
private String team\_master\_id\_ap;//申请的team的队长\
private String team\_master\_or;//创建的team的队长\
private String team\_id\_or;//创建的team\
\
//订单详情中需要判断的6个属性\
private int
update\_flag;//订单是否可编辑标识0:可编辑;1不可编辑(默认为0)没有加入团队的申请，并且没有参与团队的订单可以编辑（植保队内部队员除外）。
其他情况不可编辑\
private int ismyap;//是我申请的吗 1是 0不是\
private Integer apply\_status;//订单发布状态\
private Integer work\_status;//申请表中的工作状态\
private int team\_master\_id\_ap\_isself;//本人是不是申请的团队的队长
1是 0不是\
private int isallocationme;//是不是分配给我的 1是 0不是\
private int ismyor;//是我创建的吗 1是 0不是\
private int team\_master\_or\_isself;//本人是不是创建团队的队长 1是0不是

### 程序描述

根据订单ID获取订单详情信息。

### 功能

### 性能

无

### 请求方式

GET

http://localhost:8182/plant-protection-platform/a/order/getorder?id=22

### 输入

  **参数名**     **类型**     **中文意义**   **说明**
  -------------- ------------ -------------- ----------
  **User\_id**                **用户**
  **orderId**    **String**   **订单id**

### 输出

**JSON格式数据如下：**

{

\"status\": {

\"code\": 0,

\"reasonPhrase\": \"SUCCESS\"

},

\"data\": {

\"id\": \"22\",

\"isNewRecord\": false,

\"update\_by\": \"2\",

\"order\_name\": \"22\",

\"order\_status\": 2,

\"order\_position\": \"2\",

\"crops\_id\": \"2\",

\"order\_crop\": \"韭菜\",

\"location\": \"2\",

\"publish\_type\": 2,

\"order\_acreage\": 2,

\"work\_acreage\": 22,

\"order\_unit\_price\": 2,

\"order\_pesticide\": \"除草剂\",

\"pesticide\_id\": \"2\",

\"order\_time\_start\": 1542080812000,

\"order\_time\_end\": 1542080814000,

\"order\_creater\_id\": \"23\",

\"order\_create\_time\": 1542080809000,

\"work\_team\": 2,

\"work\_uav\": 22,

\"work\_user\": 22,

\"provide\_meal\": 2,

\"provide\_accommodation\": 2,

\"provide\_battery\_charging\": 0,

\"provide\_post\_service\": 2,

\"provide\_drug\": 2,

\"order\_creater\_tel\": \"2\",

\"work\_demand\": 2,

\"max\_flying\_height\": 2,

\"max\_flying\_speed\": 2,

\"remark\": \"2\",

\"update\_id\": \"2\",

\"city\_id\": \"2\",

\"union\_id\": \"22\",

\"union\_name\": \"2\",

\"team\_id\": \"2\",

\"team\_name\": \"2\",

\"ident\_flag\": 2,

\"shownumber\_flag\": 2,

\"showinfo\_flag\": 2,

\"require\_flag\": 0,

\"contactor\": \"ewr\",

\"contactor\_phonenum\": \"123241241223\",

\"user\_type\": 1,

\"update\_flag\": 1,

\"ismyap\": 0,

\"team\_master\_id\_ap\_isself\": 0,

\"isallocationme\": 0,

\"ismyor\": 1,

\"team\_master\_or\_isself\": 0

}

}

申请作业数量
------------

### 程序描述

查询点击详情的订单的申请作业的单位数量

### 功能

查询点击详情的订单的申请作业的单位数量

### 请求方式

Get

http://localhost:8182/plant-protection-platform/a/order/orderappronum?order\_id=22

### 输入

order\_id

### 输出

{

\"status\": {

\"code\": 0,

\"reasonPhrase\": \"SUCCESS\"

},

\"data\": {

\"orderappronum\": 0

}

}

参与团队列表
------------

### 程序描述

根据订单ID获取订单参与团队列表。

### 功能

### 性能

无

### 请求方式

GET

http://localhost:8182/plant-protection-platform/a/order/orderapprolist?order\_id=22

### 输入

  **参数名**   **类型**   **中文意义**   **说明**
  ------------ ---------- -------------- ----------
  order\_id    String     订单ID         订单id

### 输出

**JSON格式数据如下：**

{

\"status\": {

\"code\": 0,

\"reasonPhrase\": \"SUCCESS\"

},

\"data\": {

\"list\": \[

{

\"apply\_work\_acreage\": 22, //申请面积

\"team\_id\": \"22\",

\"order\_id\": \"22\",

\"applicant\_team\": \"as\", //团队名称

\"logo\_url\": \"asd\"

},

{

\"team\_id\": \"2\",

\"order\_id\": \"22\",

\"logo\_url\": \"asdas\"

}

\]

}

}

订单申请列表
------------

### 程序描述

分页查询订单申请列表。

### 功能

根据订单ID分页查询订单申请列表

### 性能

无

### 请求方式

get

### 输入

  **参数名**   **类型**   **中文意义**   **说明**
  ------------ ---------- -------------- ----------
  orderId      String     订单ID

### 输出

**JSON格式数据如下：**

{

\"status\": {

\"code\": 0,

\"reasonPhrase\": \"SUCCESS\"

},

\"data\": {

\"name\": \"22\",

\"list\": \[

{

\"id\": \"3\",

\"isNewRecord\": false,

\"order\_id\": \"22\", //订单id

\"order\_name\": \"22\", //订单名称

\"user\_id\": \"12\",//用户id

"user\_name":"",//用户名

\"team\_id\": \"123\",//团队id

"team\_name":"",//团队名

"uav\_count":"",//飞机数量

\"apply\_status\": 0,//申请状态0待审核 1进行中（同意）2已完成 3拒绝

\"work\_status\": 0, //工作状态 0正常 1被停止

"person\_count":"",//作业人数

"apply\_work\_acceage:"",//申请面积

"apply\_time":"",//申请时间

"create\_by":"",//创建者

"create\_time":"",//创建时间

"update\_by":"",//修改者

"update\_time":"",//修改时间

"remarks":"",//备注

"worked\_area":""//作业经验

},

{

\"id\": \"4\",

\"isNewRecord\": false,

\"order\_id\": \"22\",

\"order\_name\": \"22\",

\"user\_id\": \"q22\",

\"team\_id\": \"wwqqw\",

\"apply\_status\": 0,

\"work\_status\": 0

}

\]

}

}

审核加入作业申请接口
--------------------

### 程序描述

修改订单申请审核状态

### 功能

根据订单申请ID修改审核状态

### 性能

无

### 请求方式

Get

http://localhost:8182/plant-protection-platform/a/order/orderappring?order\_id=22&&team\_id=2&&status=2

### 输入

  **参数名**    **类型**   **中文意义**   **说明**
  ------------- ---------- -------------- ---------------
  id            String     订单申请ID
  auditStatus   String     审核状态       3:拒绝;1:同意

### 输出

**JSON格式数据如下：**

**{ \"status\": \"{code=0, reasonPhrase=SUCCESS}\"}**

参与团队详情接口
----------------

### 程序描述

通过订单ID,植保队ID查询植保队详情。

### 功能

### 性能

无

### 请求方式

POST

### 输入

  **参数名**   **类型**   **中文意义**   **说明**
  ------------ ---------- -------------- ----------
  orderId      String     订单ID
  teamId       String     团队ID

### 输出

**JSON格式数据如下：**

{

\"status\": {

\"code\": 0,

\"reasonPhrase\": \"SUCCESS\"

},

\"data\": {

\"apply\_work\_acreage\": 22, //申请面积

\"team\_id\": \"22\",//团队id

\"order\_id\": \"22\",//订单id

\"order\_name\": \"22\",//订单名

\"applicant\_team\": \"as\",//团队名

"work\_status":"",//作业状态 0正常 1被停止

"mapping\_acreage":"",//测绘面积

\"task\_acreage\": 22,//作业面积

\"task\_person\_count\": 22,//人数

\"task\_uav\_count\": 22,//飞机数

\"teamMemberEntity\": \[

{

\"id\": \"1\",

\"name\": \"系统管理员\",//姓名

\"area\": 22//面积

}

\]

}

}

停止作业接口
------------

### 程序描述

停止作业的接口

### 功能

停止当前团队的作业任务

### 请求方式

Get

### 输入

  **参数名**   **类型**   **中文意义**   **说明**
  ------------ ---------- -------------- ----------
  id           String     订单申请ID
  workStatus   String     工作转态       1:拒绝

### 输出

**{ \"status\": \"{code=0, reasonPhrase=SUCCESS}\"}**

订单作业设备列表接口
--------------------

### 程序描述

根据订单ID查询订单作业设备列表。

### 功能

### 性能

无

### 请求方式

GET

http://localhost:8182/plant-protection-platform/a/order/uavlist?order\_id=22

### 输入

  **参数名**   **类型**   **中文意义**   **说明**
  ------------ ---------- -------------- ----------
  order\_id    String     订单ID

### 输出

**JSON格式数据如下：**

{

\"status\": {

\"code\": 0,

\"reasonPhrase\": \"SUCCESS\"

},

\"data\": {

\"list\": \[

{

\"apply\_work\_acreage\": 22,

\"team\_id\": \"22\",

\"order\_id\": \"22\",

\"applicant\_team\": \"as\", //团队名称

\"logo\_url\": \"asd\",

\"uavTaskMessageEntities\": \[

{

\"uav\_id\": \"022556b20b8f4688af38a170e1501111\",

\"uav\_name\": \"CE2020170303093\", //飞机名称

\"work\_acreage\": 22 //飞机作业面积

}

\]

}

\]

}

}

订单卫星地图列表
----------------

### 程序描述

分页查询订单地块坐标信息列表。

### 功能

根据订单ID分页查询地块坐标信息列表

### 性能

无

### 请求方式

Get

列表统计

[[http://localhost:8182/plant-protection-platform/a/order/landsliststatistics?order\_id=22]{.underline}](http://localhost:8182/plant-protection-platform/a/order/landsliststatistics?order_id=22)

列表：

http://localhost:8182/plant-protection-platform/a/order/landslist?order\_id=22&&page\_size=10&&page\_no=1

### 输入

  **参数名**   **类型**   **中文意义**   **说明**
  ------------ ---------- -------------- ----------
  orderId      String     订单ID
  pageSize     String     每页数量
  pageNo       String     当前页码

### 输出

**JSON格式数据如下：**

**地块列表页的统计接口：**

{

\"status\": {

\"code\": 0,

\"reasonPhrase\": \"SUCCESS\"

},

\"data\": {

\"order\_name\": \"22\",

\"crop\_id\": \"2\",

\"crop\_name\": \"韭菜\",

\"finished\_acreage\": 22,

\"land\_count\": 1,

\"land\_acreage\": 22

}

}

List

{

\"status\": {

\"code\": 0,

\"reasonPhrase\": \"SUCCESS\"

},

\"data\": {

\"pageNo\": 1,

\"pageSize\": -1,

\"count\": 1,

\"list\": \[

{

\"isNewRecord\": true,

\"order\_id\": \"22\",

\"land\_id\": \"222\"

}

\],

\"current\_page\": 1,

\"page\_count\": 10,

\"firstResult\": 0,

\"maxResults\": -1,

}

}

订单地块详情
------------

### 程序描述

根据订单地块ID查询地块详情。

### 功能

根据订单地块ID查询地块详情

### 性能

无

### 请求方式

GET

http://localhost:8182/plant-protection-platform/a/order/landdetail?land\_id=222

### 输入

  **参数名**   **类型**   **中文意义**   **说明**
  ------------ ---------- -------------- ----------
  land\_id     String     订单地块ID

### 输出

**JSON格式数据如下：**

{

\"status\": {

\"code\": 0,

\"reasonPhrase\": \"SUCCESS\"

},

\"data\": {

\"isNewRecord\": true,

\"land\_id\": \"222\",

"land\_name":"",//地块名称

\"user\_id\": \"487bc6e197704587874d9cc8a4b61a82\",

"work\_status":"",//状态

"worked\_area":"",//工作

"mapping\_area":""//测绘

}

}

招募状态改变接口
----------------

### 程序描述

修改订单招募状态。

### 功能

### 性能

无

### 请求方式

Get

停止订单

[[http://localhost:8182/plant-protection-platform/a/order/stoporder?order\_id=22]{.underline}](http://localhost:8182/plant-protection-platform/a/order/stoporder?order_id=22)

继续订单

http://localhost:8182/plant-protection-platform/a/order/goonorder?order\_id=22

### 输入

  **参数名**                **类型**   **中文意义**   **说明**
  ------------------------- ---------- -------------- ----------------------
  orderId                   String     订单ID
  publishStatus（不要了）   Int        订单发布状态   0:招募中;1:停止招募;

### 输出

**JSON格式数据如下：**

**{ \"status\": \"{code=0, reasonPhrase=SUCCESS}\" }**

订单完成接口
------------

### 程序描述

修改订单招募状态为已完成，生成报表。

### 功能

### 性能

无

### 请求方式

Get

http://localhost:8182/plant-protection-platform/a/order/orderover?order\_id=22

### 输入

  **参数名**      **类型**   **中文意义**   **说明**
  --------------- ---------- -------------- -----------
  orderId         String     订单ID
  publishStatus   Int        订单发布状态   2，已完成

### 输出

**JSON格式数据如下：**

**{ \"status\": \"{code=0, reasonPhrase=SUCCESS}\" }**

订单执行部分接口
================

订单列表(大厅)
--------------

### 程序描述

分页查询获取订单大厅内所有订单列表。

### 功能

按照地区(默认全部),订单发布类型(默认大厅+联盟)分页查询订单发布列表,按照面积单价排序

### 性能

网络环境稳定的情况下10秒内响应

### 请求方式

Get

http://localhost:8182/plant-protection-platform/a/order/orderlistlobby?page\_no=1&&page\_size=30&&user\_id=2&&order\_by=unit\_price&&order\_model=0

### 输入

格式: JSON

列表:

  **参数名**     **类型**   **中文意义**                       **说明**
  -------------- ---------- ---------------------------------- ----------
  user\_id       String     用户ID
  page\_no       String     当前分页，默认为1
  order\_by      String     当前排序依据，默认为create\_time
  order\_model   String     当前排序方式，默认为1(desc)
  page\_size     String     每页数量，默认为10
  order\_name    String     根据订单名称搜索相应订单

### 输出

格式: JSON

列表:

+-----------------+-----------------+-----------------+-----------------+
| **参数名**      | **类型**        | **中文意义**    | **说明**        |
+=================+=================+=================+=================+
| id              | String          | 订单id          |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_name     | String          | 订单名称        |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_acreage  | String          | 订单面积        |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_unit\_pr | String          | 每亩价格        |                 |
| ice             |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_pesticid | String          | 用药类型        |                 |
| e               |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| pesticide\_id   |                 | 用药类型id      |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_create\_ | Date            | 创建时间        | 返回数据是毫秒  |
| time            |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_time\_st | Date            | 开始时间        | 返回数据是毫秒  |
| art             |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_time\_en | Date            | 结束时间        | 返回数据是毫秒  |
| d               |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_position | String          | 作业地址        |                 |
+-----------------+-----------------+-----------------+-----------------+
| location        | String          | 地址坐标        | 返回地块经纬度,以','分割 |
+-----------------+-----------------+-----------------+-----------------+
| publish\_type   | int             | 发布类型        | 0:大厅;1联盟;2:团队;3 |
|                 |                 |                 | :个人           |
+-----------------+-----------------+-----------------+-----------------+
| union\_id       | String          | 联盟ID          | publish\_type为1 |
|                 |                 |                 | 时不为空        |
+-----------------+-----------------+-----------------+-----------------+
| union\_name     |                 | 联盟名          |                 |
+-----------------+-----------------+-----------------+-----------------+
| team\_id        | String          | 团队ID          | publish\_type为1 |
|                 |                 |                 | 或2时不为空     |
+-----------------+-----------------+-----------------+-----------------+
| team\_name      |                 | 团队名          |                 |
+-----------------+-----------------+-----------------+-----------------+
| ident\_flag     | Int             | 团队认证标识    | 0:团队不需要认证 |
|                 |                 |                 |                 |
|                 |                 |                 |                 |
|                 |                 |                 | 1:团队需要认证  |
+-----------------+-----------------+-----------------+-----------------+
| provide\_meal   | Int             | 提供工作餐标识  | 0:不提供;1:提供 |
+-----------------+-----------------+-----------------+-----------------+
| provide\_accomm | Int             | 提供住宿标识    | 0:不提供;1:提供 |
| odation         |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| provide\_batter | Int             | 提供电池充电标识 | 0:不提供;1:提供 |
| y\_charging     |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| provide\_post\_ | Int             | 提供后勤服务    | 0:不提供;1:提供 |
| service         |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| provide\_drug   | Int             | 需求方包药      | 0:不包;1:包     |
+-----------------+-----------------+-----------------+-----------------+
| shownumber\_fla | Int             | 对外显示手机号标识 | 0:不显示;1:显示 |
| g               |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| showinfo\_flag  | Int             | 对外公开作业数据标识 | 0:不公开;1:公开 |
+-----------------+-----------------+-----------------+-----------------+
| work\_demand    | Int             | 作业要求标识    | 0:不需要;1:需要 |
+-----------------+-----------------+-----------------+-----------------+
| max\_flying\_he | String          | 飞行高度        | 单位:米         |
| ight            |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| max\_flying\_sp | String          | 飞行速度        | 米/秒           |
| eed             |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| remark          | String          | 备注            |                 |
+-----------------+-----------------+-----------------+-----------------+
| user\_number    | String          | 联系方式        | 农户手机        |
+-----------------+-----------------+-----------------+-----------------+
| order\_status   | Int             | 订单发布状态    | 0:招募中;1:停止招募;2: |
|                 |                 |                 | 已完成          |
+-----------------+-----------------+-----------------+-----------------+
| city\_id        | String          | 地块行政区ID    | 市级行政区ID    |
+-----------------+-----------------+-----------------+-----------------+
| Province\_id    |                 | 省id            |                 |
+-----------------+-----------------+-----------------+-----------------+
| Country         |                 | 县id            |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_pesticid | String          | 农药名称        |                 |
| e               |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| pesticide\_id   |                 | 农药id          |                 |
+-----------------+-----------------+-----------------+-----------------+
| contactor       | String          | 联系人姓名      |                 |
+-----------------+-----------------+-----------------+-----------------+
| contactor\_phon | String          | 联系人手机号    |                 |
| enum            |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_crop     | String          | 订单作物        |                 |
+-----------------+-----------------+-----------------+-----------------+
| crops\_id       | String          | 作物类型        |                 |
+-----------------+-----------------+-----------------+-----------------+

示例:

{

\"status\": {

\"code\": 0,

\"reasonPhrase\": \"SUCCESS\"

},

\"data\": {

\"pageNo\": 1,

\"pageSize\": -1,

\"count\": 2,

\"list\": \[

{

\"id\": \"wqe11111111\",

\"isNewRecord\": false,

\"update\_by\": \"1\",

\"create\_date\": -1,

\"update\_date\": -1,

\"order\_name\": \"a的订单1\",

\"order\_status\": 0,

\"order\_position\": \"沈阳\",

\"location\": \"asas\",

\"publish\_type\": 0,

\"order\_acreage\": 222,

\"order\_unit\_price\": 22,

\"order\_pesticide\": \"杀虫剂\",

\"pesticide\_id\": \"1\",

\"order\_time\_start\": 1542937212000,

\"order\_time\_end\": 1542937214000,

\"order\_creater\_id\": \"2\",

\"order\_create\_time\": 1542937209000,

\"work\_team\": 0,

\"work\_uav\": 0,

\"work\_user\": 0,

\"provide\_meal\": 1,

\"provide\_accommodation\": 1,

\"provide\_battery\_charging\": 1,

\"provide\_post\_service\": 1,

\"provide\_drug\": 1,

\"order\_creater\_tel\": \"1\",

\"work\_demand\": 1,

\"max\_flying\_height\": 1,

\"max\_flying\_speed\": 1,

\"remark\": \"1\",

\"city\_id\": \"1\",

\"ident\_flag\": 1,

\"shownumber\_flag\": 1,

\"showinfo\_flag\": 1,

\"require\_flag\": 0,

\"update\_flag\": 1,

\"ismyap\": 0,

\"team\_master\_id\_ap\_isself\": 0,

\"isallocationme\": 0,

\"ismyor\": 0,

\"team\_master\_or\_isself\": 0,

\"current\_status\": 0

},

{

\"id\": \"4\",

\"isNewRecord\": false,

\"create\_date\": -1,

\"update\_date\": -1,

\"order\_name\": \"4\",

\"order\_status\": 0,

\"order\_position\": \"4\",

\"crops\_id\": \"2\",

\"order\_crop\": \"韭菜\",

\"location\": \"4\",

\"publish\_type\": 4,

\"order\_acreage\": 4,

\"order\_unit\_price\": 4,

\"pesticide\_id\": \"4\",

\"order\_time\_start\": 1542089933000,

\"order\_time\_end\": 1542089935000,

\"order\_creater\_id\": \"2\",

\"order\_create\_time\": 1542089930000,

\"work\_team\": 0,

\"work\_uav\": 0,

\"work\_user\": 0,

\"provide\_meal\": 0,

\"provide\_accommodation\": 0,

\"provide\_battery\_charging\": 0,

\"provide\_post\_service\": 0,

\"provide\_drug\": 0,

\"work\_demand\": 0,

\"max\_flying\_height\": 0,

\"max\_flying\_speed\": 0,

\"update\_id\": \"2\",

\"ident\_flag\": 0,

\"shownumber\_flag\": 0,

\"showinfo\_flag\": 0,

\"require\_flag\": 0,

\"update\_flag\": 0,

\"ismyap\": 0,

\"team\_master\_id\_ap\_isself\": 0,

\"isallocationme\": 0,

\"ismyor\": 0,

\"team\_master\_or\_isself\": 0,

\"current\_status\": 0

}

\],

\"current\_page\": 1,

\"page\_count\": 30,

}

}

订单详情
--------

### 程序描述

根据订单ID获取订单详情信息。

### 功能

根据订单ID获取订单详情信息。

### 性能

网络环境稳定的情况下10秒内响应

### 请求方式

GET

http://localhost:8182/plant-protection-platform/a/order/getorder?id=22

### 输入

  **参数名**      **类型**     **中文意义**   **说明**
  --------------- ------------ -------------- ----------
  **order\_id**   **String**   **订单id**

### 输出

格式: JSON

列表:

+-----------------+-----------------+-----------------+-----------------+
| **参数名**      | **类型**        | **中文意义**    | **说明**        |
+=================+=================+=================+=================+
| id              | String          | 订单id          |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_name     | String          | 订单名称        |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_acreage  | String          | 订单面积        |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_unit\_pr | String          | 每亩价格        |                 |
| ice             |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_pesticid | String          | 用药类型        |                 |
| e               |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| pesticide\_id   |                 | 用药id          |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_create\_ | Date            | 创建时间        | 返回数据是毫秒  |
| time            |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_time\_st | Date            | 开始时间        | 返回数据是毫秒  |
| art             |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_time\_en | Date            | 结束时间        | 返回数据是毫秒  |
| d               |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_position | String          | 作业地址        |                 |
+-----------------+-----------------+-----------------+-----------------+
| location        | String          | 地址坐标        | 返回地块经纬度,以','分割 |
+-----------------+-----------------+-----------------+-----------------+
| publish\_type   | int             | 发布类型        | 0:大厅;1联盟;2:团队;3 |
|                 |                 |                 | :个人           |
+-----------------+-----------------+-----------------+-----------------+
| union\_id       | String          | 联盟ID          | publish\_type为1 |
|                 |                 |                 | 时不为空        |
+-----------------+-----------------+-----------------+-----------------+
| union\_name     |                 | 联盟名          |                 |
+-----------------+-----------------+-----------------+-----------------+
| team\_id        | String          | 团队ID          | publish\_type为1 |
|                 |                 |                 | 或2时不为空     |
+-----------------+-----------------+-----------------+-----------------+
| team\_name      |                 | 团队名          |                 |
+-----------------+-----------------+-----------------+-----------------+
| ident\_flag     | Int             | 团队认证标识    | 0:团队不需要认证 |
|                 |                 |                 |                 |
|                 |                 |                 |                 |
|                 |                 |                 | 1:团队需要认证  |
+-----------------+-----------------+-----------------+-----------------+
| provide\_meal   | Int             | 提供工作餐标识  | 0:不提供;1:提供 |
+-----------------+-----------------+-----------------+-----------------+
| provide\_accomm | Int             | 提供住宿标识    | 0:不提供;1:提供 |
| odation         |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| provide\_batter | Int             | 提供电池充电标识 | 0:不提供;1:提供 |
| y\_charging     |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| provide\_post\_ | Int             | 提供后勤服务    | 0:不提供;1:提供 |
| service         |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| provide\_drug   | Int             | 需求方包药      | 0:不包;1:包     |
+-----------------+-----------------+-----------------+-----------------+
| shownumber\_fla | Int             | 对外显示手机号标识 | 0:不显示;1:显示 |
| g               |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| showinfo\_flag  | Int             | 对外公开作业数据标识 | 0:不公开;1:公开 |
+-----------------+-----------------+-----------------+-----------------+
| work\_demand    | Int             | 作业要求标识    | 0:不需要;1:需要 |
+-----------------+-----------------+-----------------+-----------------+
| max\_flying\_he | String          | 飞行高度        | 单位:米         |
| ight            |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| max\_flying\_sp | String          | 飞行速度        | 米/秒           |
| eed             |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| remark          | String          | 备注            |                 |
+-----------------+-----------------+-----------------+-----------------+
| user\_number    | String          | 联系方式        | 农户手机        |
+-----------------+-----------------+-----------------+-----------------+
| order\_status   | Int             | 订单发布状态    | 0:招募中;1:停止招募;2: |
|                 |                 |                 | 已完成          |
+-----------------+-----------------+-----------------+-----------------+
| city\_id        | String          | 地块行政区ID    | 市级行政区ID    |
+-----------------+-----------------+-----------------+-----------------+
| order\_pesticid | String          | 农药名称        |                 |
| e               |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| pesticide\_id   |                 | 农药id          |                 |
+-----------------+-----------------+-----------------+-----------------+
| contactor       | String          | 联系人姓名      |                 |
+-----------------+-----------------+-----------------+-----------------+
| contactor\_phon | String          | 联系人手机号    |                 |
| enum            |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_crop     | String          | 订单作物        |                 |
+-----------------+-----------------+-----------------+-----------------+
| crops\_id       |                 | 作物id          |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_crop\_ty | String          | 作物类型        |                 |
| pe              |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| update\_flag    | Int             | 订单是否可编辑标识 | 0:可编辑;1不可编辑(默认为 |
|                 |                 |                 | 0)              |
|                 |                 |                 |                 |
|                 |                 |                 | 没有加入团队的申请，并且没有参 |
|                 |                 |                 | 与团队的订单可以编辑（植保队内 |
|                 |                 |                 | 部队员除外）。  |
|                 |                 |                 | 其他情况不可编辑 |
+-----------------+-----------------+-----------------+-----------------+
| ismyap          |                 | 是我申请的吗    |                 |
|                 |                 | 1是 0不是       |                 |
+-----------------+-----------------+-----------------+-----------------+
| apply\_status   |                 | 订单申请状态    |                 |
+-----------------+-----------------+-----------------+-----------------+
| work\_status    |                 | 申请表中的工作状态 |              |
+-----------------+-----------------+-----------------+-----------------+
| team\_master\_o |                 | 本人是不是创建团队的队长 |        |
| r\_isself       |                 |                 |                 |
|                 |                 | 1是0不是        |                 |
+-----------------+-----------------+-----------------+-----------------+
| team\_master\_i |                 | 本人是不是申请的团队的队长 |      |
| d\_ap\_isself   |                 |                 |                 |
|                 |                 | 1是 0不是       |                 |
+-----------------+-----------------+-----------------+-----------------+
| isallocationme  |                 | 是不是分配给我的 |                |
|                 |                 |                 |                 |
|                 |                 | 1是 0不是       |                 |
+-----------------+-----------------+-----------------+-----------------+
| ismyor          |                 | 是我创建的吗    |                 |
|                 |                 | 1是 0不是       |                 |
+-----------------+-----------------+-----------------+-----------------+

示例:

{

\"status\":{\"code\":0,\"reasonPhrase\":\"SUCCESS\"},

\"data\":{

\"id\":\"\*\*\*\",

\"order\_name\":\"\*\*\*\",

\"order\_acreage\":\"\*\*\*\",

\"order\_unit\_price\":\"\*\*\*\",

\"order\_pesticide\_type\":\"\*\*\*\",

\"order\_create\_time\":\"\*\*\*\",

\"order\_time\_start\":\"\*\*\*\",

\"order\_time\_end\":\"\*\*\*\",

\"order\_position\":\"\*\*\*\",

\"location\":\"\*\*\*\",

\"publish\_type\":\"\*\*\*\",

\"union\_id\":\"\*\*\*\",

\"team\_id\":\"\*\*\*\",

\"ident\_flag\":\"\*\*\*\",

\"offer\_lunch\":\"\*\*\*\",

\"offer\_hotel\":\"\*\*\*\",

\"offer\_charge\":\"\*\*\*\",

\"offer\_logistics\":\"\*\*\*\",

\"offer\_pesticide\":\"\*\*\*\",

\"show\_phone\":\"\*\*\*\",

\"show\_data\":\"\*\*\*\",

\"order\_require\":\"\*\*\*\",

\"order\_fly\_height\":\"\*\*\*\",

\"order\_fly\_velocity\":\"\*\*\*\",

\"order\_remark\":\"\*\*\*\",

\"user\_number\":\"\*\*\*\",

\"publish\_status\":\"\*\*\*\",

\"city\_id\":\"\*\*\*\",

\"order\_pesticide\":\"\*\*\*\",

\"contact\_name\":\"\*\*\*\",

\"contact\_phone\":\"\*\*\*\",

\"order\_crop\":\"\*\*\*\",

\"order\_crop\_type\":\"\*\*\*\",

\"updateFlag\":\"\*\*\*\*\"

}

}

查询用户所属团队列表
--------------------

### 程序描述

根据用户ID获取所属团队列表。

### 功能

### 性能

无

### 请求方式

GET

http://localhost:8182/plant-protection-platform/a/order/getallteam?user\_id=22

### 输入

  **参数名**   **类型**   **中文意义**   **说明**
  ------------ ---------- -------------- ----------
  user\_id     String     用户ID

### 输出

格式: JSON

列表:

  **参数名**   **类型**     **中文意义**   **说明**
  ------------ ------------ -------------- ----------
  **id**       **String**   **团队ID**
  **name**     **String**   **团队名称**

查询用户所属联盟列表
--------------------

### 程序描述

根据用户ID获取用户所属团队的联盟列表。

### 功能

### 性能

无

### 请求方式

GET

http://localhost:8182/plant-protection-platform/a/order/getallunion?user\_id=22

### 输入

  **参数名**   **类型**   **中文意义**   **说明**
  ------------ ---------- -------------- ----------
  user\_id     String     用户ID

### 输出

**JSON格式数据如下：**

**{"status\":"{code=0, reasonPhrase=SUCCESS}\",\"data\":\"{}\"}**

  **参数名**   **类型**     **中文意义**   **说明**
  ------------ ------------ -------------- ----------
  **id**       **String**   **联盟ID**
  **name**     **String**   **联盟名称**

创建订单（见9.4）
-----------------

### 程序描述

创建订单。

### 功能

创建订单。

### 性能

无

### 请求方式

POST

### 输入

格式: JSON

列表:

+-----------------+-----------------+-----------------+-----------------+
| **参数名**      | **类型**        | **中文意义**    | **说明**        |
+=================+=================+=================+=================+
| order\_name     | String          | 订单名称        |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_acreage  | String          | 订单面积        |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_unit\_pr | String          | 每亩价格        |                 |
| ice             |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_pesticid | String          | 用药类型        |                 |
| e\_type         |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_time\_st | Date            | 开始时间        | 返回数据是毫秒  |
| art             |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_time\_en | Date            | 结束时间        | 返回数据是毫秒  |
| d               |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_position | String          | 作业地址        |                 |
+-----------------+-----------------+-----------------+-----------------+
| location        | String          | 地址坐标        | 返回地块经纬度,以','分割 |
+-----------------+-----------------+-----------------+-----------------+
| publish\_type   | int             | 发布类型        | 0:大厅;1联盟;2:团队;3 |
|                 |                 |                 | :个人           |
+-----------------+-----------------+-----------------+-----------------+
| union\_id       | String          | 联盟ID          | publish\_type为1 |
|                 |                 |                 | 时不为空        |
+-----------------+-----------------+-----------------+-----------------+
| team\_id        | String          | 团队ID          | publish\_type为1 |
|                 |                 |                 | 或2时不为空     |
+-----------------+-----------------+-----------------+-----------------+
| ident\_flag     | Int             | 团队认证标识    | 0:团队不需要认证 |
|                 |                 |                 |                 |
|                 |                 |                 |                 |
|                 |                 |                 | 1:团队需要认证  |
+-----------------+-----------------+-----------------+-----------------+
| offer\_lunch    | Int             | 提供工作餐标识  | 0:不提供;1:提供 |
+-----------------+-----------------+-----------------+-----------------+
| offer\_hotel    | Int             | 提供住宿标识    | 0:不提供;1:提供 |
+-----------------+-----------------+-----------------+-----------------+
| offer\_charge   | Int             | 提供电池充电标识 | 0:不提供;1:提供 |
+-----------------+-----------------+-----------------+-----------------+
| offer\_logistic | Int             | 提供后勤服务    | 0:不提供;1:提供 |
| s               |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| offer\_pesticid | Int             | 需求方包药      | 0:不包;1:包     |
| e               |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| show\_phone     | Int             | 对外显示手机号标识 | 0:不显示;1:显示 |
+-----------------+-----------------+-----------------+-----------------+
| show\_data      | Int             | 对外公开作业数据标识 | 0:不公开;1:公开 |
+-----------------+-----------------+-----------------+-----------------+
| order\_require  | Int             | 作业要求标识    | 0:不需要;1:需要 |
+-----------------+-----------------+-----------------+-----------------+
| order\_fly\_hei | String          | 飞行高度        | 单位:米         |
| ght             |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_fly\_vel | String          | 飞行速度        | 米/秒           |
| ocity           |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_remark   | String          | 备注            |                 |
+-----------------+-----------------+-----------------+-----------------+
| user\_number    | String          | 联系方式        | 农户手机        |
+-----------------+-----------------+-----------------+-----------------+
| publish\_status | Int             | 订单发布状态    | 0:招募中;1:停止招募;2: |
|                 |                 |                 | 已完成          |
+-----------------+-----------------+-----------------+-----------------+
| city\_id        | String          | 地块行政区ID    | 市级行政区ID    |
+-----------------+-----------------+-----------------+-----------------+
| contact\_name   | String          | 联系人姓名      |                 |
+-----------------+-----------------+-----------------+-----------------+
| contact\_phone  | String          | 联系人手机号    |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_crop\_ty | String          | 作物类型        |                 |
| pe              |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+

示例:

{

\"id\":\"\*\*\*\*\",

\"order\_name\":\"\*\*\*\*\",

\"area\":\"\*\*\*\*\",

\"unitPrice\":\"\*\*\*\*\",

\"pesticideType\":\"\*\*\*\*\",

\"createDate\":\"\*\*\*\*\",

\"startTime\":\"\*\*\*\*\",

\"endTime\":\"\*\*\*\*\",

\"address\":\"\*\*\*\*\",

\"location\":\"\*\*\*\*\",

\"publishType\":\"\*\*\*\*\",

\"unionId\":\"\*\*\*\*\",

\"team\_id\":\"\*\*\*\*\",

\"identFlag\":\"\*\*\*\*\",

\"lunchFlag\":\"\*\*\*\*\",

\"stayFlag\":\"\*\*\*\*\",

\"chargeFlag\":\"\*\*\*\*\",

\"serverFlag\":\"\*\*\*\*\",

\"provideFlag\":\"\*\*\*\*\",

\"showNumberFlag\":\"\*\*\*\*\",

\"showInfoFlag\":\"\*\*\*\*\",

\"requireFlag\":\"\*\*\*\*\",

\"height\":\"\*\*\*\*\",

\"speed\":\"\*\*\*\*\",

\"remark\":\"\*\*\*\*\",

\"contactNumber\":\"\*\*\*\*\",

\"publishStatus\":\"\*\*\*\*\",

\"cityId\":\"\*\*\*\*\",

\"pesticideName\":\"\*\*\*\*\"

}

### 输出

**JSON格式数据如下：**

**{"status\":"{code=0, reasonPhrase=SUCCESS}\",\"data\":\"{}\"}**

编辑订单（订单详情 创建）
-------------------------

### 程序描述

编辑订单。

### 功能

### 性能

无

### 请求方式

POST

### 输入

格式: JSON

列表:

+-----------------+-----------------+-----------------+-----------------+
| **参数名**      | **类型**        | **中文意义**    | **说明**        |
+=================+=================+=================+=================+
| id              | String          | 订单id          |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_name     | String          | 订单名称        |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_acreage  | String          | 订单面积        |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_unit\_pr | String          | 每亩价格        |                 |
| ice             |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_pesticid | String          | 用药类型        |                 |
| e\_type         |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_time\_st | Date            | 开始时间        | 返回数据是毫秒  |
| art             |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_time\_en | Date            | 结束时间        | 返回数据是毫秒  |
| d               |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_position | String          | 作业地址        |                 |
+-----------------+-----------------+-----------------+-----------------+
| location        | String          | 地址坐标        | 返回地块经纬度,以','分割 |
+-----------------+-----------------+-----------------+-----------------+
| publish\_type   | int             | 发布类型        | 0:大厅;1联盟;2:团队;3 |
|                 |                 |                 | :个人           |
+-----------------+-----------------+-----------------+-----------------+
| union\_id       | String          | 联盟ID          | publish\_type为1 |
|                 |                 |                 | 时不为空        |
+-----------------+-----------------+-----------------+-----------------+
| team\_id        | String          | 团队ID          | publish\_type为1 |
|                 |                 |                 | 或2时不为空     |
+-----------------+-----------------+-----------------+-----------------+
| ident\_flag     | Int             | 团队认证标识    | 0:团队不需要认证 |
|                 |                 |                 |                 |
|                 |                 |                 |                 |
|                 |                 |                 | 1:团队需要认证  |
+-----------------+-----------------+-----------------+-----------------+
| offer\_lunch    | Int             | 提供工作餐标识  | 0:不提供;1:提供 |
+-----------------+-----------------+-----------------+-----------------+
| offer\_hotel    | Int             | 提供住宿标识    | 0:不提供;1:提供 |
+-----------------+-----------------+-----------------+-----------------+
| offer\_charge   | Int             | 提供电池充电标识 | 0:不提供;1:提供 |
+-----------------+-----------------+-----------------+-----------------+
| offer\_logistic | Int             | 提供后勤服务    | 0:不提供;1:提供 |
| s               |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| offer\_pesticid | Int             | 需求方包药      | 0:不包;1:包     |
| e               |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| show\_phone     | Int             | 对外显示手机号标识 | 0:不显示;1:显示 |
+-----------------+-----------------+-----------------+-----------------+
| show\_data      | Int             | 对外公开作业数据标识 | 0:不公开;1:公开 |
+-----------------+-----------------+-----------------+-----------------+
| order\_require  | Int             | 作业要求标识    | 0:不需要;1:需要 |
+-----------------+-----------------+-----------------+-----------------+
| order\_fly\_hei | String          | 飞行高度        | 单位:米         |
| ght             |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_fly\_vel | String          | 飞行速度        | 米/秒           |
| ocity           |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_remark   | String          | 备注            |                 |
+-----------------+-----------------+-----------------+-----------------+
| user\_number    | String          | 联系方式        | 农户手机        |
+-----------------+-----------------+-----------------+-----------------+
| publish\_status | Int             | 订单发布状态    | 0:招募中;1:停止招募;2: |
|                 |                 |                 | 已完成          |
+-----------------+-----------------+-----------------+-----------------+
| city\_id        | String          | 地块行政区ID    | 市级行政区ID    |
+-----------------+-----------------+-----------------+-----------------+
| contact\_name   | String          | 联系人姓名      |                 |
+-----------------+-----------------+-----------------+-----------------+
| contact\_phone  | String          | 联系人手机号    |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_crop\_ty | String          | 作物类型        |                 |
| pe              |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+

示例:

{

\"id\":\"\*\*\*\",

\"order\_name\":\"\*\*\*\",

\"order\_acreage\":\"\*\*\*\",

\"order\_unit\_price\":\"\*\*\*\",

\"order\_pesticide\_type\":\"\*\*\*\",

\"order\_create\_time\":\"\*\*\*\",

\"order\_time\_start\":\"\*\*\*\",

\"order\_time\_end\":\"\*\*\*\",

\"order\_position\":\"\*\*\*\",

\"location\":\"\*\*\*\",

\"publish\_type\":\"\*\*\*\",

\"union\_id\":\"\*\*\*\",

\"team\_id\":\"\*\*\*\",

\"ident\_flag\":\"\*\*\*\",

\"offer\_lunch\":\"\*\*\*\",

\"offer\_hotel\":\"\*\*\*\",

\"offer\_charge\":\"\*\*\*\",

\"offer\_logistics\":\"\*\*\*\",

\"offer\_pesticide\":\"\*\*\*\",

\"show\_phone\":\"\*\*\*\",

\"show\_data\":\"\*\*\*\",

\"order\_require\":\"\*\*\*\",

\"order\_fly\_height\":\"\*\*\*\",

\"order\_fly\_velocity\":\"\*\*\*\",

\"order\_remark\":\"\*\*\*\",

\"user\_number\":\"\*\*\*\",

\"publish\_status\":\"\*\*\*\",

\"city\_id\":\"\*\*\*\",

\"order\_pesticide\":\"\*\*\*\",

\"contact\_name\":\"\*\*\*\",

\"contact\_phone\":\"\*\*\*\",

\"order\_crop\":\"\*\*\*\",

\"order\_crop\_type\":\"\*\*\*\",

}

### 输出

**JSON格式数据如下：**

**{"status\":"{code=0, reasonPhrase=SUCCESS}\"}**

飞手所属团队列表
----------------

### 程序描述

查询植保用户所属植保队列表。

### 功能

查询植保用户所属植保队列表。

### 性能

无

### 请求方式

GET

### 输入

  **参数名**   **类型**   **中文意义**   **说明**
  ------------ ---------- -------------- ----------
  user\_id     String     用户id

### 输出

**JSON格式数据如下：**

**{"status\":"{code=0, reasonPhrase=SUCCESS}\",\"data\":\"{}\"}**

d**ata: List\<TeamInfo\>，其中FORM BEAN类名：TeamInfo**

  **参数名**   **类型**   **中文意义**   **说明**
  ------------ ---------- -------------- -----------------
  id           String     团队id
  name         String     团队名称
  status       int        当前团队标记   0:非默认;1:默认


示例:

{

\"status\":{\"code\":0,\"reasonPhrase\":\"SUCCESS\"},

\"data\":\[{

\"id\":\"\*\*\*\*\",\"name\":\"\*\*\*\*\"

},{

\"id\":\"\*\*\*\*\",\"name\":\"\*\*\*\*\"

}

\...

\]

}

订单申请
--------

### 程序描述

申请加入订单。

### 功能

### 性能

无

### 请求方式

POST

http://localhost:8182/plant-protection-platform/a/order/applyorder

### 输入

  **参数名**             **类型**   **中文意义**   **说明**
  ---------------------- ---------- -------------- ----------
  user\_id               String     用户ID         申请人
  order\_id              String     订单ID
  team\_id               String     团队ID
  uav\_count             String     参与飞机数量
  person\_count          String     参与人员数量
  apply\_work\_acreage   String     申请作业面积
  remark                 String     备注说明
  **applicant\_tel**     String     申请人电话

### 输出

**JSON格式数据如下：**

**{"status\":"{code=0, reasonPhrase=SUCCESS}\"}**

我的订单列表
------------

### 程序描述

分页查询我的订单列表。

### 功能

按照我发布的/我申请的状态分页查询我的订单列表

### 性能

无

### 请求方式

POST

http://localhost:8182/plant-protection-platform/api/order/myorder?page\_no=1&&page\_size=30&&user\_id=2

### 输入

+-----------------+-----------------+-----------------+-----------------+
| **参数名**      | **类型**        | **中文意义**    | **说明**        |
+=================+=================+=================+=================+
| allandnotall    | String          | 订单状态        | 接收参数allandnotal |
|                 |                 |                 | l               |
|                 |                 |                 | 代表 查询全部   |
|                 |                 |                 | 包括我参与的和我发布的所有的 |
|                 |                 |                 |                 |
|                 |                 |                 | 1我参与 2我发布 |
|                 |                 |                 | 如果为空        |
|                 |                 |                 | 默认给10        |
|                 |                 |                 | 查询全部        |
+-----------------+-----------------+-----------------+-----------------+
| order\_status   | String          | 分类状态        | 0:招募中;1:停止招募;2: |
|                 |                 |                 | 已完成;         |
|                 |                 |                 |                 |
|                 |                 |                 | 0:待审核;1:进行中;2:已 |
|                 |                 |                 | 完成;           |
+-----------------+-----------------+-----------------+-----------------+
| user\_id        | String          | 用户ID          |                 |
+-----------------+-----------------+-----------------+-----------------+
| page\_size      | String          | 每页数量        |                 |
+-----------------+-----------------+-----------------+-----------------+
| page\_no        | String          | 当前页码        |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_by       | String          | 当前排序依据，默认为creat |       |
|                 |                 | e\_time         |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_name     |                 | 订单名          |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_model    | String          | 当前排序方式，默认为1(des |       |
|                 |                 | c)              |                 |
+-----------------+-----------------+-----------------+-----------------+

### 输出

**JSON格式数据如下：**

**{"status\":"{code=0, reasonPhrase=SUCCESS}\",\"data\":\"{}\"}**

**data:List\<OrderDetailInfo \>，其中FORM BEAN类名：OrderDetailInfo**

+-----------------+-----------------+-----------------+-----------------+
| **参数名**      | **类型**        | **中文意义**    | **说明**        |
+=================+=================+=================+=================+
| id              | String          | 订单id          |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_name     | String          | 订单名称        |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_acreage  | String          | 订单面积        |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_unit\_pr | String          | 每亩价格        |                 |
| ice             |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_pesticid | String          | 用药类型        |                 |
| e               |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| pesticide\_id   |                 | 用药id          |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_create\_ | Date            | 创建时间        | 返回数据是毫秒  |
| time            |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_time\_st | Date            | 开始时间        | 返回数据是毫秒  |
| art             |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_time\_en | Date            | 结束时间        | 返回数据是毫秒  |
| d               |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_position | String          | 作业地址        |                 |
+-----------------+-----------------+-----------------+-----------------+
| location        | String          | 地址坐标        | 返回地块经纬度,以','分割 |
+-----------------+-----------------+-----------------+-----------------+
| publish\_type   | int             | 发布类型        | 0:大厅;1联盟;2:团队;3 |
|                 |                 |                 | :个人           |
+-----------------+-----------------+-----------------+-----------------+
| union\_id       | String          | 联盟ID          | publish\_type为1 |
|                 |                 |                 | 时不为空        |
+-----------------+-----------------+-----------------+-----------------+
| union\_name     |                 | 联盟名          |                 |
+-----------------+-----------------+-----------------+-----------------+
| team\_id        | String          | 团队ID          | publish\_type为1 |
|                 |                 |                 | 或2时不为空     |
+-----------------+-----------------+-----------------+-----------------+
| team\_name      |                 | 团队名          |                 |
+-----------------+-----------------+-----------------+-----------------+
| ident\_flag     | Int             | 团队认证标识    | 0:团队不需要认证 |
|                 |                 |                 |                 |
|                 |                 |                 |                 |
|                 |                 |                 | 1:团队需要认证  |
+-----------------+-----------------+-----------------+-----------------+
| provide\_meal   | Int             | 提供工作餐标识  | 0:不提供;1:提供 |
+-----------------+-----------------+-----------------+-----------------+
| provide\_accomm | Int             | 提供住宿标识    | 0:不提供;1:提供 |
| odation         |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| provide\_batter | Int             | 提供电池充电标识 | 0:不提供;1:提供 |
| y\_charging     |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| provide\_post\_ | Int             | 提供后勤服务    | 0:不提供;1:提供 |
| service         |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| provide\_drug   | Int             | 需求方包药      | 0:不包;1:包     |
+-----------------+-----------------+-----------------+-----------------+
| shownumber\_fla | Int             | 对外显示手机号标识 | 0:不显示;1:显示 |
| g               |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| showinfo\_flag  | Int             | 对外公开作业数据标识 | 0:不公开;1:公开 |
+-----------------+-----------------+-----------------+-----------------+
| work\_demand    | Int             | 作业要求标识    | 0:不需要;1:需要 |
+-----------------+-----------------+-----------------+-----------------+
| max\_flying\_he | String          | 飞行高度        | 单位:米         |
| ight            |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| max\_flying\_sp | String          | 飞行速度        | 米/秒           |
| eed             |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| remark          | String          | 备注            |                 |
+-----------------+-----------------+-----------------+-----------------+
| user\_number    | String          | 联系方式        | 农户手机        |
+-----------------+-----------------+-----------------+-----------------+
| order\_status   | Int             | 订单发布状态    | 0:招募中;1:停止招募;2: |
|                 |                 |                 | 已完成          |
+-----------------+-----------------+-----------------+-----------------+
| city\_id        | String          | 地块行政区ID    | 市级行政区ID    |
+-----------------+-----------------+-----------------+-----------------+
| order\_pesticid | String          | 农药名称        |                 |
| e               |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| pesticide\_id   |                 | 农药id          |                 |
+-----------------+-----------------+-----------------+-----------------+
| contactor       | String          | 联系人姓名      |                 |
+-----------------+-----------------+-----------------+-----------------+
| contactor\_phon | String          | 联系人手机号    |                 |
| enum            |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_crop     | String          | 订单作物        |                 |
+-----------------+-----------------+-----------------+-----------------+
| crops\_id       |                 | 作物id          |                 |
+-----------------+-----------------+-----------------+-----------------+
| order\_crop\_ty | String          | 作物类型        |                 |
| pe              |                 |                 |                 |
+-----------------+-----------------+-----------------+-----------------+
| is\_myself      | String          | 发布源          | 0是我创建的     |
|                 |                 |                 | 1是我申请的     |
+-----------------+-----------------+-----------------+-----------------+

订单申请列表
------------

### 程序描述

分页查询订单申请列表。

### 功能

根据订单ID分页查询订单申请列表

### 性能

无

### 请求方式

Get

http://localhost:8182/plant-protection-platform/api/order/orderapprolist?id=22

### 输入

  **参数名**   **类型**   **中文意义**   **说明**
  ------------ ---------- -------------- ----------
  order\_id    String     订单ID

### 输出

**JSON格式数据如下：**

**{"status\":"{code=0, reasonPhrase=SUCCESS}\",\"data\":\"{}\"}**

**data:List\<ApplyForOrderInfo \>，其中FORM
BEAN类名：ApplyForOrderInfo**

  **参数名**             **类型**   **中文意义**   **说明**
  ---------------------- ---------- -------------- ---------------------------------------------------
  id                     String     订单申请id
  order\_id              String     订单ID
  order\_name            String     订单名称
  user\_id               String     申请人ID
  applicant              String     申请人名称
  team\_id               String     申请团队ID
  team\_name             String     申请团队名称
  worked\_area           String     作业经验
  uav\_count             String     参与飞机数量
  person\_count          String     参与人员数量
  apply\_work\_acreage   String     申请面积
  apply\_time            Date       申请时间       返回数据是毫秒
  remark                 String     备注
  apply\_status          String     申请状态       0:待审核;1:进行中(同意);2:已完成;3:拒绝;(默认为0)

示例:

{

\"status\":{\"code\":0,\"reasonPhrase\":\"SUCCESS\"},

\"data\":\[{

\"id\":\"\*\*\*\*\",

\"order\_id\":\"\*\*\*\*\",

\"order\_name\":\"\*\*\*\*\",

\"user\_id\":\"\*\*\*\*\",

\"user\_name\":\"\*\*\*\*\",

\"team\_id\":\"\*\*\*\*\",

\"team\_name\":\"\*\*\*\*\",

\"workedArea\":\"\*\*\*\*\",

\"uavCount\":\"\*\*\*\*\",

\"userCount\":\"\*\*\*\*\",

\"applyForArea\":\"\*\*\*\*\",

\"applyTime\":\"\*\*\*\*\",

\"remark\":\"\*\*\*\*\",

\"applyStatus\":\"\*\*\*\*\"

},{

\"id\":\"\*\*\*\*\",

\"order\_id\":\"\*\*\*\*\",

\"order\_name\":\"\*\*\*\*\",

\"user\_id\":\"\*\*\*\*\",

\"user\_name\":\"\*\*\*\*\",

\"team\_id\":\"\*\*\*\*\",

\"team\_name\":\"\*\*\*\*\",

\"workedArea\":\"\*\*\*\*\",

\"uavCount\":\"\*\*\*\*\",

\"userCount\":\"\*\*\*\*\",

\"applyForArea\":\"\*\*\*\*\",

\"applyTime\":\"\*\*\*\*\",

\"remark\":\"\*\*\*\*\",

\"applyStatus\":\"\*\*\*\*\"

}

\...

\]

}

订单地块列表统计
----------------

### 程序描述

分页查询订单地块坐标信息列表。

### 功能

根据订单ID分页查询地块坐标信息列表

### 性能

无

### 请求方式

Get

http://localhost:8182/plant-protection-platform/a/order/landsliststatistics?order\_id=22输入

  **参数名**   **类型**   **中文意义**   **说明**
  ------------ ---------- -------------- ----------
  order\_id    String     订单ID

### 输出

**JSON格式数据如下：**

**{"status\":"{code=0, reasonPhrase=SUCCESS}\",\"data\":\"{}\"}**

**data:List\<BlockOfOrderInfo \>，其中FORM BEAN类名：BlockOfOrderInfo**

  **参数名**          **类型**   **中文意义**   **说明**
  ------------------- ---------- -------------- ----------
  land\_count         String     地块数量
  land\_acreage       String     地块总面积     单位(亩)
  finished\_acreage   String     已作业面积     单位(亩)
  crop\_id            String     农作物ID
  crop\_name          String     农作物名称
  order\_id           String     订单ID
  order\_name         String     订单名称

订单地块列表
------------

### 程序描述

分页查询订单地块坐标信息列表。

### 功能

根据订单ID分页查询地块坐标信息列表

### 性能

无

### 请求方式

Get

http://localhost:8182/plant-protection-platform/a/order/landslist?order\_id=22&&page\_size=2&&page\_no=1

### 输入

  **参数名**   **类型**   **中文意义**   **说明**
  ------------ ---------- -------------- ----------
  order\_id    String     订单ID
  page\_size   String     每页数量
  Page\_no     String     当前页码


### 输出

**JSON格式数据如下：**

**{"status\":"{code=0, reasonPhrase=SUCCESS}\",\"data\":\"{}\"}**

**data:List\<BlockOfOrderInfo \>，其中FORM BEAN类名：BlockOfOrderInfo**

其中FORM BEAN类名：BlockInfo

  **参数名**                **类型**   **中文意义**   **说明**
  ------------------------- ---------- -------------- ---------------------------------------------------------
  id                        String     地块ID
  land\_info                String     地块坐标信息   经纬度按","连接，点与点使用"\|"连接，经度在前，纬度在后
  work\_status              String     作业状态       0:未作业;1:未完成:2:已完成
  land\_code                String     地块编码
  land\_name                String     地块名称
  land\_acreage             String     地块面积
  finished\_acreage         String     作业面积
  land\_finished\_percent   String     完成百分比

示例:

{

\"status\":{\"code\":0,\"reasonPhrase\":\"SUCCESS\"},

\"data\":{

\"count\":\"\*\*\*\",

\"land\_acreage\":\"\*\*\*\",

\"finished\_acreage\":\"\*\*\*\",

\"crop\_id\":\"\*\*\*\",

\"crop\_name\":\"\*\*\*\",

\"order\_id\":\"\*\*\*\",

\"order\_name\":\"\*\*\*\",

\"list\":\[{

\"id\":\"\*\*\*\",

\"location\":\"\*\*\*\",

\"status\":\"\*\*\*\",

\"code\":\"\*\*\*\",

\"name\":\"\*\*\*\",

\"land\_acreage\":\"\*\*\*\",

\"finished\_acreage\":\"\*\*\*\",

\"land\_finished\_percent\":\"\*\*\*\"

},{

\"id\":\"\*\*\*\",

\"location\":\"\*\*\*\",

\"status\":\"\*\*\*\",

\"code\":\"\*\*\*\",

\"name\":\"\*\*\*\",

\"land\_acreage\":\"\*\*\*\",

\"finished\_acreage\":\"\*\*\*\",

\"land\_finished\_percent\":\"\*\*\*\"

}\]

}

}

订单地块详情
------------

### 程序描述

根据订单地块ID查询地块详情。

### 功能

根据订单地块ID查询地块详情

### 性能

无

### 请求方式

GET

http://localhost:8182/plant-protection-platform/a/order/landdetail?land\_id=222

### 输入

  **参数名**   **类型**   **中文意义**   **说明**
  ------------ ---------- -------------- ----------
  block\_id    String     订单地块ID

### 输出

**JSON格式数据如下：**

**{"status\":"{code=0, reasonPhrase=SUCCESS}\",\"data\":\"{}\"}**

**data:** BlockInfo**，其中FORM BEAN类名：**BlockInfo

  **参数名**                **类型**     **中文意义**       **说明**
  ------------------------- ------------ ------------------ -------------------------------------------------------------
  land\_id                  **String**   **地块ID**
  land\_info                **String**   **地块坐标信息**   **经纬度按","连接，点与点使用"\|"连接，经度在前，纬度在后**
  work\_status              **String**   **作业状态**       **0:未作业;1:未完成:2:已完成**
  land\_code                **String**   **地块编码**
  land\_name                **String**   **地块名称**
  work\_status              **String**   **作业面积**
  mapping\_area             **String**   **测绘面积**
  user\_id                  **String**   **测绘人员ID**
  **User\_name**            **String**   **测绘人员名称**
  dosage                    **String**   **用药量**
  start\_time               **Date**     **开始时间**       **毫秒数**
  end\_time                 **Date**     **结束时间**       **毫秒数**
  land\_finished\_percent   **String**   **完成半分比**

示例:

**{"status\": {code=0, reasonPhrase=SUCCESS},\"data\":{**

**\"id\":\"\*\*\*\",**

**\"location\":\"\*\*\*\",**

**\"status\":\"\*\*\*\",**

**\"code\":\"\*\*\*\",**

**\"name\":\"\*\*\*\",**

**\"**work\_acreage**\":\"\*\*\*\",**

**mapping**\_acreage**\":\"\*\*\*\",**

**\"mapping\_person\_id\":\"\*\*\*\",**

**\"mapping\_person\_name\":\"\*\*\*\",**

**\"dosage\":\"\*\*\*\",**

**\"**land\_start\_time**\":\"\*\*\*\",**

**\"**land\_end\_time**\":\"\*\*\*\",**

**\"**land\_finished\_percent**\":\"\*\*\*\"**

**}}**

修改订单申请审核状态(见9.11)
----------------------------

### 程序描述

修改订单申请审核状态

### 功能

根据订单申请ID修改审核状态

### 性能

无

### 请求方式

POST

### 输入

  **参数名**      **类型**   **中文意义**   **说明**
  --------------- ---------- -------------- ---------------
  id              String     订单申请ID
  audit\_status   String     审核状态       3:拒绝;1:同意
  team\_id        String     团队id

示例:

{

\"id\":\"\*\*\*\*\*\",

\"auditStatus": 1

}

### 输出

**JSON格式数据如下：**

**{"status\":"{code=0, reasonPhrase=SUCCESS}\"}**

农药列表
--------

### 程序描述

农药字典表信息。

### 功能

查询农药字典列表。

### 性能

无

### 请求方式

GET

http://localhost:8182/plant-protection-platform/a/order/worktype

### 输入

无

### 输出

**JSON格式数据如下：**

**{"status\":"{code=0, reasonPhrase=SUCCESS}\",\"data\":\"{}\"}**

**其中FORM BEAN类名：Type**

  **参数名**   **类型 **   **中文意义**   **说明**
  ------------ ----------- -------------- ----------
  id           String      农药id
  name         String      农药名称

**示例:**

**{"status\": {code=0, reasonPhrase=SUCCESS},\"data\":\[{**

**\"id\":\"\*\*\*\",**

**\"name\":\"\*\*\*\"**

**},{**

**\"id\":\"\*\*\*\",**

**\"name\":\"\*\*\*\"**

**}\]}**

农作物列表
----------

### 程序描述

农作物字典表信息。

### 功能

查询农作物典列表。

### 性能

无

### 请求方式

GET

http://localhost:8182/plant-protection-platform/a/order/cropstype

### 输入

无

### 输出

**JSON格式数据如下：**

**{"status\":"{code=0, reasonPhrase=SUCCESS}\",\"data\":\"{}\"}**

**其中FORM BEAN类名：Type**

  **参数名**   **类型 **   **中文意义**   **说明**
  ------------ ----------- -------------- ----------
  id           String      农作物id
  name         String      农作物名称

**示例:**

**{"status\": {code=0, reasonPhrase=SUCCESS},\"data\":\[{**

**\"id\":\"\*\*\*\",**

**\"name\":\"\*\*\*\"**

**},{**

**\"id\":\"\*\*\*\",**

**\"name\":\"\*\*\*\"**

**}\]}**


作物列表（app）
------------
### 请求方式

GET

http://localhost:8182/api/order/cropstypeapp

### 输入

无

### 输出
{
    "status": {
        "code": 0,
        "reasonPhrase": "SUCCESS"
    },
    "data": {
        "list": [
            {
                "id": "1",
                "cname": "白菜",
                "code": "1",
                "url": ""
            },
            {
                "id": "2",
                "cname": "韭菜",
                "code": "2",
                "url": ""
            }
        ]
    }
}

参与团队列表
------------

### 程序描述

根据订单ID获取订单参与团队列表。

### 功能

### 性能

无

### 请求方式

GET

http://localhost:8182/plant-protection-platform/a/order/plantteamlist?order\_id=22

### 输入

  **参数名**   **类型**   **中文意义**   **说明**
  ------------ ---------- -------------- ----------
  order\_id    String     订单ID

### 输出

**JSON格式数据如下：**

**{"status\":"{code=0, reasonPhrase=SUCCESS}\",\"data\":\"{}\"}**

d**ata: List\<ApplyInfo\>，其中FORM BEAN类名：ApplyInfo**

  **参数名**             **类型**     **中文意义**       **说明**
  ---------------------- ------------ ------------------ ----------------------------------
  **team\_id**           **String**   **团队ID**
  **applicant\_team**    **String**   **团队名称**
  **work\_status**       **String**   **团队作业状态**   **0:进行中(默认);1:完成;2:停止**
  apply\_work\_acreage   **String**   **团队作业面积**   **单位:亩**
  **logo\_url**          **String**   **团队logo**       **团队logo URL**

**{**

**\"status\": {**

**\"code\": 0,**

**\"reasonPhrase\": \"SUCCESS\"**

**},**

**\"data\": {**

**\"list\": \[**

**{**

**\"id\": \"\",**

**\"apply\_work\_acreage\": 22,**

**\"team\_id\": \"22\",**

**\"order\_id\": \"22\",**

**\"order\_name\": \"\",**

**\"applicant\_team\": \"TESTNAME\",**

**\"task\_flag\": \"\",**

**\"task\_acreage\": \"\",**

**\"authen\_flag\": \"\",**

**\"task\_person\_count\": \"\",**

**\"task\_uav\_count\": \"\",**

**\"teamMemberEntity\": \"\",**

**\"mapping\_acreage\": \"\",**

**\"work\_status\": \"\",**

**\"logo\_url\": \"asd\",**

**\"uavTaskMessageEntities\": \"\"**

**}**

**\]**

**}**

**}**

参与团队详情
------------

### 程序描述

通过订单ID,植保队ID查询植保队详情。

### 功能

### 性能

无

### 请求方式

Get

http://localhost:8182/plant-protection-platform/a/order/partteamdetail?order\_id=22&&team\_id=22

### 输入

  **参数名**   **类型**   **中文意义**   **说明**
  ------------ ---------- -------------- ----------
  order\_id    String     订单ID
  team\_id     String     团队ID

### 输出

**JSON格式数据如下：**

**{"status\":"{code=0, reasonPhrase=SUCCESS}\",\"data\":\"{}\"}**

d**ata: List\<ApplyTeamInfo\>，其中FORM BEAN类名：ApplyTeamInfo**

  **参数名**                **类型**     **中文意义**       **说明**
  ------------------------- ------------ ------------------ ----------
  order\_id                 String       订单ID
  team\_id                  String       团队ID
  **order\_name**           **String**   **订单名称**
  **applicant\_team**       **String**   **团队名称**
  **mapping\_acreage**      **String**   **测绘面积**
  **task\_acreage**         **String**   **作业面积**
  **task\_person\_count**   **String**   **作业人员数量**
  **task\_uav\_count**      **String**   **作业飞机数量**
  **teamMemberEntity**      **List**     **团队成员列表**

其中FORM BEAN类名：Member

  **参数名**   **类型**     **中文意义**       **说明**
  ------------ ------------ ------------------ ----------
  **name**     **String**   **团队成员姓名**
  **area**     **String**   **作业面积**
  **id**       **String**   **成员ID**

**示例:**

**{**

**\"status\": {**

**\"code\": 0,**

**\"reasonPhrase\": \"SUCCESS\"**

**},**

**\"data\": {**

**\"id\": \"\",**

**\"apply\_work\_acreage\": 22,**

**\"team\_id\": \"22\",**

**\"order\_id\": \"22\",**

**\"order\_name\": \"22\",**

**\"applicant\_team\": \"TESTNAME\",**

**\"task\_flag\": \"\",**

**\"task\_acreage\": 87,**

**\"authen\_flag\": \"\",**

**\"task\_person\_count\": 22,**

**\"task\_uav\_count\": 22,**

**\"teamMemberEntity\": \[**

**{**

**\"id\": \"1\",**

**\"name\": \"系统管理员\",**

**\"area\": 22**

**}**

**\],**

**\"mapping\_acreage\": 67,**

**\"work\_status\": \"\",**

**\"logo\_url\": \"\",**

**\"uavTaskMessageEntities\": \"\"**

**}**

**}**

订单作业设备列表接口（见9.14）
------------------------------

### 程序描述

根据订单ID查询订单作业设备列表。

### 功能

根据订单ID查询订单作业设备列表。

### 性能

无

### 请求方式

GET

### 输入

  **参数名**   **类型**   **中文意义**   **说明**
  ------------ ---------- -------------- ----------
  order\_id    String     订单ID

### 输出

**JSON格式数据如下：**

**{"status\":"{code=0, reasonPhrase=SUCCESS}\",\"data\":\"{}\"}**

d**ata: List\<** **EquipmentInfo\>，其中FORM BEAN类名：EquipmentInfo**

  **参数名**          **类型**     **中文意义**   **说明**
  ------------------- ------------ -------------- ----------
  **team\_id**        **String**   **团队ID**
  **team\_name**      **String**   **团队名称**
  **number**          **String**   **飞手电话**
  **uav\_id**         **String**   **飞机ID**
  **uav\_name**       **String**   **飞机名称**
  **work\_acreage**   **String**   **作业面积**



示例:

**{"status\": {code=0, reasonPhrase=SUCCESS},\"data\":\[{**

**\"team\_id\":\"\*\*\*\",**

**\"team\_name\":\"\*\*\*\",**

**\"number \":\"\*\*\*\",**

**\"uav\_id\":\"\*\*\*\",**

**\"uav\_name\":\"\*\*\*\",**

**\"user\_id\":\"\*\*\*\",**

**\"user\_name\":\"\*\*\*\",**

**\"work\_acreage\":\"\*\*\*\"**

**},{**

**\"team\_id\":\"\*\*\*\",**

**\"team\_name\":\"\*\*\*\",**

**\"number \":\"\*\*\*\",**

**\"uav\_id\":\"\*\*\*\",**

**\"uav\_name\":\"\*\*\*\",**

**\"user\_id\":\"\*\*\*\",**

**\"user\_name\":\"\*\*\*\",**

**\"work\_acreage\":\"\*\*\*\"**

**}\]}**

查询团队成员列表接口
--------------------

### 程序描述

根据团队ID查询团队成员列表。

### 功能

根据团队ID查询团队成员列表。

### 性能

无

### 请求方式

GET

[[http://localhost:8182/plant-protection-platform/a/order/assign?order\_id=22&&team\_id=66666666666]{.underline}](http://localhost:8182/plant-protection-platform/a/order/assign?order_id=22&&team_id=66666666666)

get

### 输入

  **参数名**   **类型**   **中文意义**   **说明**
  ------------ ---------- -------------- ----------
  team\_id     String     团队ID
  order\_id    String     订单ID

### 输出

**JSON格式数据如下：**

**{\"status\":\"{code=0, reasonPhrase=SUCCESS}\"}**

d**ata: List\<** Member **\>，其中FORM BEAN类名：**Member

  **参数名**       **类型**     **中文意义**       **说明**
  ---------------- ------------ ------------------ -----------------------
  **name**         **String**   **团队成员姓名**
  **id**           **String**   **成员ID**
  **permission**   **int**      **参与状态**       **0:未加入;1:已加入**

**示例:**

**{**

**\"status\": {**

**\"code\": 0,**

**\"reasonPhrase\": \"SUCCESS\"**

**},**

**\"data\": {**

**\"list\": \[**

**{**

**\"id\": \"dba0af0c8f73419497e7465464d5491c\",**

**\"name\": \"辽宁三级经销商部门人员\",**

**\"permission\": 1,**

**\"reid\": \"5\"**

**}**

**\]**

**}**

**}**

分派队员接口
------------

### 程序描述

为订单分派队员

### 功能

### 性能

无

### 请求方式

Get

http://localhost:8182/plant-protection-platform/a/order/assigned?order\_id=22&&team\_id=66666666666&&user\_ids=dba0af0c8f73419497e7465464d5491c,dba0af0c8f73419497e7465464d5491c1

### 输入

  **参数名**   **类型**     **中文意义**       **说明**
  ------------ ------------ ------------------ ----------
  order\_id    String       订单ID
  team\_id     String       团队ID
  user\_ids    String\[\]   被分派成员ID列表
  User\_id                  队长id

### 输出

**JSON格式数据如下：**

**{"status\":"{code=0, reasonPhrase=SUCCESS}\"}**

订单招募状态修改接口（见9.17）
------------------------------

### 程序描述

修改订单招募状态。

### 功能

### 性能

无

### 请求方式

POST

### 输入

  **参数名**        **类型**   **中文意义**   **说明**
  ----------------- ---------- -------------- ------------------------------
  order\_id         String     订单ID
  publish\_status   Int        订单发布状态   0:招募中;1:停止招募;2:已完成

示例:

**{\"order\_id\":"\*\*\*\",**

**\"**publishStatus**\": 0**

**}**

### 输出

**JSON格式数据如下：**

**{"status\":"{code=0, reasonPhrase=SUCCESS}\" }**

分享订单
--------

### 程序描述

根据订单ID生成订单分享信息。

### 功能

根据订单ID生成订单分享信息。

### 性能

网络环境稳定的情况下10秒内响应

### 请求方式

GET

分享订单详情

[[http://localhost:8182/plant-protection-platform/a/order/shareorder?order\_id=22&&user\_id=23]{.underline}](http://localhost:8182/plant-protection-platform/a/order/shareorder?order_id=22&&user_id=23)

分享订单二维码

http://localhost:8182/plant-protection-platform/a/order/qrcode

### 输入

  **参数名**      **类型**     **中文意义**   **说明**
  --------------- ------------ -------------- ----------
  **order\_id**   **String**   **订单id**

### 输出

格式: JSON

列表:

  **参数名**           **类型**     **中文意义**   **说明**
  -------------------- ------------ -------------- ----------
  order\_id            String       订单id
  inviter              **String**   邀请人
  order\_name          **String**   订单名称
  position             **String**   地址
  order\_crop          **String**   作物
  order\_acreage       **String**   面积
  order\_unit\_price   **String**   亩单价
  order\_pesticide     **String**   农药
  order\_time\_start   **String**   作业开始时间
  order\_time\_end     **String**   作业结束时间
  code\_image          **String**   二维码图片

示例:

{

\"status\":{\"code\":0,\"reasonPhrase\":\"SUCCESS\"},

\"data\":{

\"order\_id\":\"\*\*\*\",

\"inviter\":\"\*\*\*\",

\"order\_name\":\"\*\*\*\",

\"position\":\"\*\*\*\",

\"order\_crop\":\"\*\*\*\",

\"order\_acreage\":\"\*\*\*\",

\"order\_unit\_price\":\"\*\*\*\",

\"order\_pesticide\":\"\*\*\*\",

\"order\_time\_start\":\"\*\*\*\",

\"order\_time\_end\":\"\*\*\*\",

\"code\_image\":\"\*\*\*\"

}

}

申请加入订单数量（见9.8）
-------------------------

### 程序描述

查询点击详情的订单的申请作业的单位数量

### 功能

查询点击详情的订单的申请作业的单位数量

### 请求方式

Get

### 输入

  **参数名**      **类型**     **中文意义**   **说明**
  --------------- ------------ -------------- ----------
  **order\_id**   **String**   **订单id**

### 输出

**{ **

**\"status\": \"{code=0, reasonPhrase=SUCCESS}\",**

**\"data\":\"{**

**"**[apply](javascript:;)\_count**":""**

**}\"**

**}**

基站管理APP部分接口
===================

消息列表
--------

### 程序描述

返回所有最新消息和历史消息列表

### 功能

### 性能

无

### 输入

### 输出

JSON格式数据如下：

{

"status": "{code=0, reasonPhrase=SUCCESS}",

"data": {

"messages": [{ // 最新消息

"mid": "...",

"msg": "...",

"read": false

}],

"his_messages": [{ // 历史消息

"mid": "...",

"msg": "..."

}]

}

}

各字段说明如下：

| 参数名 | 类型    | 中文意义 | 说明 |
|--------|---------|----------|------|
| mid    | String  | 消息id   |      |
| msg    | String  | 消息内容 |      |
| read   | boolean | 是否已读 |      |

置消息已读
----------

### 程序描述

将该消息置为已读状态。

### 功能

### 性能

无

### 输入

| 参数名 | 类型   | 中文意义 | 说明 |
|--------|--------|----------|------|
| mid    | String | 消息id   |      |

### 输出

JSON格式数据如下：

{ "status": "{code=0, reasonPhrase=SUCCESS}","data":"{}"}

千寻账号列表
------------

### 程序描述

返回当前用户可用的千寻账号列表。

### 功能

### 输入

| 参数名 | 类型   | 中文意义 | 说明 |
|--------|--------|----------|------|
| teamId | String | 植保队id |      |

### 输出

JSON格式数据如下：

{

"status": "{code=0, reasonPhrase=SUCCESS}",

"data": [

{

"qxId":"...",

"qxaccount":"..."

}

]

}

各字段说明如下：

| 参数名    | 类型   | 中文意义   | 说明 |
|-----------|--------|------------|------|
| qxId      | String | 千寻账号id |      |
| qxaccount | String | 千寻账号   |      |

千寻账号删除
------------

### 程序描述

删除千寻账号。

### 功能

### 输入

| 参数名 | 类型   | 中文意义   | 说明 |
|--------|--------|------------|------|
| qxId   | String | 千寻账号id |      |

### 输出

JSON格式数据如下：

{ "status": "{code=0, reasonPhrase=SUCCESS}","data":"{}"}

基准点列表
----------

### 程序描述

返回所有基准点，以手机与基准点距离由近到远排序。

### 功能

### 输入

| 参数名 | 类型   | 中文意义   | 说明 |
|--------|--------|------------|------|
| teamid   | String | 团队id | 选填，不填则只能查到自己新建的点   |
| lat   | Double | 纬度 | 手机当前位置   |
| lon   | Double | 经度 | 手机当前位置   |

### 输出

JSON格式数据如下：

{

"status": "{code=0, reasonPhrase=SUCCESS}",

"data": [

{

"pid":"...",

"name":"...",

"lat":41.123123,

"lon":123.345234,

"distance":3452

}

]

}

各字段说明如下：

| 参数名 | 类型   | 中文意义   | 说明 |
|--------|--------|------------|------|
| pid    | String | 基准点id   |      |
| name   | String | 基准点名称 |      |
| lat    | double | 维度       |      |
| lon    | double | 经度       |      |
| distance  | double | 手机到基准点的距离  |      |

新增基准点
----------

### 程序描述

增加基准点

### 功能

### 输入

| 参数名 | 类型   | 中文意义   | 说明 |
|--------|--------|------------|------|
| name   | String | 基准点名称 |      |
| lat    | double | 维度       |      |
| lon    | double | 经度       |      |
| team_id| double | 团队id     | 选填 |

### 输出

JSON格式数据如下：

{ "status": "{code=0, reasonPhrase=SUCCESS}","data":"{}"}

删除基准点
----------

### 程序描述

删除基准点。

### 功能

### 性能

无

### 输入

| 参数名 | 类型   | 中文意义 | 说明 |
|--------|--------|----------|------|
| pid    | String | 基准点id |      |

### 输出

JSON格式数据如下：

{ "status": "{code=0, reasonPhrase=SUCCESS}","data":"{}"}

检测RTK更新
-----------

### 程序描述

检测当前RTK是否为最新版本。

### 功能

### 性能

无

### 输入

| 参数名  | 类型   | 中文意义        | 说明 |
|---------|--------|-----------------|------|
| version | String | 当前RTK的版本号 |      |

### 输出

JSON格式数据如下：

{

"status": "{code=0, reasonPhrase=SUCCESS}",

"data": {

"result": true,

"lastest_version": "..."

}

}

各字段说明如下：

| 参数名          | 类型    | 中文意义           | 说明 |
|-----------------|---------|--------------------|------|
| result          | boolean | 当前是否为最新版本 |      |
| lastest_version | String  | 当前最新版本号     |      |

检测APP更新
-----------

### 程序描述

检测当前APP是否为最新版本。

### 功能

### 性能

无

### 输入

| 参数名  | 类型   | 中文意义        | 说明 |
|---------|--------|-----------------|------|
| version | String | 当前APP的版本号 |      |

### 输出

JSON格式数据如下：

{

"status": "{code=0, reasonPhrase=SUCCESS}",

"data": {

"result": true,

"lastest_version": "..."

}

}

各字段说明如下：

| 参数名          | 类型    | 中文意义           | 说明 |
|-----------------|---------|--------------------|------|
| result          | boolean | 当前是否为最新版本 |      |
| lastest_version | String  | 当前最新版本号     |      |

RTK固件下载
-----------

### 程序描述

下载最新的RTK固件文件。

### 功能

### 性能

无

### 输入

### 输出

JSON格式数据如下：

{ "status": "{code=0, reasonPhrase=SUCCESS}"}

RTK列表
---------------

### 程序描述

查询当前用户所在的所有植保队的RTK设备。

### 功能

### 性能

无

### 请求方式

>   api/mapping/rtk/list 调用方式：GET

### 输入

无

### 输出

JSON格式数据如下：

{"status":"{code=0, reasonPhrase=SUCCESS}","data":"{}"}

| 参数名        | 类型   | 中文意义  | 说明                    |
|---------------|--------|-----------|-------------------------|
| id            | String | ID        |                         |
| rtk_no        | String | rtk序列号 |                         |
| rtk_name      | String | rtk名称   |                         |
| user_id       | String | 拥有者id  |                         |
| rtk_version   | String | rtk型号   |                         |
| product_date  | String | 生产日期  |                         |
| activate_date | String | 激活时间  |                         |
| binding_date  | String | 绑定时间  |                         |
| status        | String | 状态      | 0:使用中;1维护中;2:报废 |
| remarks       | String | 备注      |                         |

示例:

{

"status": {

"code": 0,

"reasonPhrase": "SUCCESS"

},

"data": [{

"name": "植保队名称",

"list": [{

"id": "\*\*\*",

"rtk_no": "\*\*\*",

"rtk_name": "\*\*\*",

"user_id": "\*\*\*",

"rtk_version": "\*\*\*",

"product_date": "\*\*\*",

"activate_date": "\*\*\*",

"binding_date": "\*\*\*",

"status": "\*\*\*",

"remarks": "\*\*\*"

}, {

"id": "\*\*\*",

"rtk_no": "\*\*\*",

"rtk_name": "\*\*\*",

"user_id": "\*\*\*",

"rtk_version": "\*\*\*",

"product_date": "\*\*\*",

"activate_date": "\*\*\*",

"binding_date": "\*\*\*",

"status": "\*\*\*",

"remarks": "\*\*\*"

}]

}]

}

测绘APP部分接口
===============

新增地块
--------

### 程序描述

新建地块接口，修改地块也是此接口，修改时也是所有的地块信息。

### 调用地址

api/mapping/land/save   调用方式GET

### 输入

| 参数名         | 类型               | 中文意义     | 说明         |
|----------------|--------------------|--------------|--------------|
| land        | LandEntity             | 地块       | 格式参见下表 |

LandEntity为json字符串，字段格式如下：

| 参数名         | 类型               | 中文意义     | 说明         |
|----------------|--------------------|--------------|--------------|
| orderId        | String             | 订单id       |              |
| taskid         | String             | 任务id       |              |
| landid         | String             | 地块id       | 由客户端生成此id |
| areaid         | String             | 区域id       |              |
| mapping_area   | Double             | 测绘面积      |              |
| landSecDistance   | Double          | 地块安全距离    |              |
| obsSecDistance   | Double          | 障碍安全距离    |              |
| stopSecDistance   | Double           |  停喷安全距离     |              |
| landPoints     | List\<LandPoints\> | 地块点的信息 | 格式参见下表 |
| obstaclePoints | List\<List\<LandPoints\>\> | 障碍点的信息 | 格式参见下表 |
| stopAreaPoints | List\<List\<LandPoints\>\> | 停喷点的信息 | 格式参见下表 |
| landId         | String             | 地块ID       |              |

LandPoints为json字符串，字段格式如下：

| 参数名 | 类型   | 中文意义 | 说明                                                                                                                |
|--------|--------|----------|---------------------------------------------------------------------------------------------------------------------|
| serial | int    | 点顺序号 | 从0开始                                                                                                             |
| lon    | double | 经度     |                                                                                                                     |
| lat    | double | 纬度     |                                                                                                                     |
| radius | double | 半径     | type为2时有此参数，其它情况不需要。                                                                                 |
| type   | int    | 点的类型 | 0：普通的多边形组成点。 1：障碍点的多边形组成点 2：圆的信息，经纬度指定圆心，radius指定半径 3：停喷点的多边形组成点 |

### 输出

JSON格式数据如下：

{

"status": {

"code": 0,

"reasonPhrase": "SUCCESS"

},

"data": [{

"id": "ce3861b0e68641b6bdaa410281a16426",

"farmersName": "农户老赵",

"farmersPhone": "13899999999",

"landName": "无距地块",

"position": "辽宁沈阳市",

"photo": "/2017/12/def.jpg",

"area": 551130636886,

"distance": 12719032.6,

"landId": "1_99999"

}]

}

字段说明如下：

| 参数名       | 类型   | 中文意义 | 说明 |
|--------------|--------|----------|------|
| farmersName  | String | 农户名称 |      |
| farmersPhone | String | 农户电话 |      |
| landName     | String | 地块名称 |      |
| position     | String | 地块位置 |      |
| photo        | String | 地块图片 |      |
| area         | double | 地块面积 |      |
| distance     | double | 地块长度 |      |
| landId       | String | 地块ID   |      |

地块列表
--------

### 程序描述

根据任务ID获取地块列表。

### 调用地址

api/mapping/land/landlist

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| taskid | String | 任务id   |      |

### 输出

data为List<LandEntity>, LandEntity结构见新增地块接口，这里只有地块信息。

JSON格式数据如下：

{

	"status": {

		"code": 0,

		"reasonPhrase": "SUCCESS"

	},

	"data": [{
			"taskid": "111",
			"orderid": "211",
			"landid": "1234567890",
			"cropsid": "adfga",
			"areaid": "43",
			"mapping_area": 24,
			"landPoints": [{
					"serial": 0,
					"lon": 123.34534534,
					"lat": 41.123123,
					"radius": 0,
					"type": 0
				},
				{
					"serial": 0,
					"lon": 123.34534534,
					"lat": 41.123123,
					"radius": 0,
					"type": 0
				},
				{
					"serial": 0,
					"lon": 123.34534534,
					"lat": 41.123123,
					"radius": 0,
					"type": 0
				},
				{
					"serial": 0,
					"lon": 123.34534534,
					"lat": 41.123123,
					"radius": 0,
					"type": 0
				}
			]
		}
	]

}

地块详细信息
-----------

### 程序描述

根据任务ID获取地块列表。

### 调用地址

api/mapping/land/landDetail

### 输入

| 参数名  | 类型   | 中文意义 | 说明 |
|---------|--------|----------|------|
| landid | String | 地块id   |      |

### 输出

data为LandEntity, LandEntity结构见新增地块接口。

JSON格式数据如下：

{

	"status": {

		"code": 0,

		"reasonPhrase": "SUCCESS"

	},

	"data": {
			"taskid": "111",
			"orderid": "211",
			"landid": "1234567890",
			"cropsid": "adfga",
			"areaid": "43",
			"mapping_area": 24,
			"landPoints": [{
					"serial": 0,
					"lon": 123.34534534,
					"lat": 41.123123,
					"radius": 0,
					"type": 0
				},
				{
					"serial": 0,
					"lon": 123.34534534,
					"lat": 41.123123,
					"radius": 0,
					"type": 0
				},
				{
					"serial": 0,
					"lon": 123.34534534,
					"lat": 41.123123,
					"radius": 0,
					"type": 0
				},
				{
					"serial": 0,
					"lon": 123.34534534,
					"lat": 41.123123,
					"radius": 0,
					"type": 0
				}
			],
			"obstaclePoints": [
				[{
					"serial": 0,
					"lon": 123.2352345,
					"lat": 41.134124,
					"radius": 5.5,
					"type": 2
				}],
				[{
						"serial": 0,
						"lon": 123.34534534,
						"lat": 41.123123,
						"radius": 0,
						"type": 1
					},
					{
						"serial": 1,
						"lon": 123.34534534,
						"lat": 41.123123,
						"radius": 0,
						"type": 1
					},
					{
						"serial": 2,
						"lon": 123.34534534,
						"lat": 41.123123,
						"radius": 0,
						"type": 1
					},
					{
						"serial": 3,
						"lon": 123.34534534,
						"lat": 41.123123,
						"radius": 0,
						"type": 1
					}
				]
			],
			"stopAreaPoints": [
				[{
						"serial": 0,
						"lon": 123.34534534,
						"lat": 41.123123,
						"radius": 0,
						"type": 3
					},
					{
						"serial": 1,
						"lon": 123.34534534,
						"lat": 41.123123,
						"radius": 0,
						"type": 3
					},
					{
						"serial": 2,
						"lon": 123.34534534,
						"lat": 41.123123,
						"radius": 0,
						"type": 3
					},
					{
						"serial": 3,
						"lon": 123.34534534,
						"lat": 41.123123,
						"radius": 0,
						"type": 3
					}
				]
			],
			"infoPoints": [{
					"serial": 0,
					"lon": 123.34534534,
					"lat": 41.123123,
					"radius": 0,
					"type": 4
				},
				{
					"serial": 0,
					"lon": 123.34534534,
					"lat": 41.123123,
					"radius": 0,
					"type": 4
				}
			]
	}

}

删除地块
--------

### 程序描述

删除地块信息。

### 调用地址

api/mapping/land/delete    调用方式POST

### 输入

| 参数名 | 类型   | 中文意义 | 说明 |
|--------|--------|----------|------|
| landid | String | 地块id   |      |

### 输出

JSON格式数据如下：

{ "status": "{code=0, reasonPhrase=SUCCESS}"}

未完成任务列表
----------------------

### 程序描述

未完成任务列表，首页使用。

### 调用地址

api/mapping/task/latesttask 调用方式：GET

### 输入

| 参数名    | 类型 | 中文意义 | 说明 |
|-----------|------|----------|------|
| teamid    | String | 团队id  | 没有此参数返回单飞飞手任务  |
| page_no   | int  | 页码     | 默认为1     |
| page_size | int  | 每页个数 |  默认为10    |

### 输出

JSON格式数据如下：

{

    "status": {
        "code": 0,
        "reasonPhrase": "SUCCESS"
    },
    "data": {
        "pageNo": 1,
        "pageSize": 10,
        "count": 1,
        "list": [
            {
                "id": "2",
                "isNewRecord": false,
                "remarks": null,
                "createDate": 1542966374000,
                "updateDate": null,
                "userid": "03964634bcc942ce8b12642486722677",
                "orderid": "00435f1b94554577b0c834a76e472709",
                "teamid": "22",
                "name": "asd0（黑龙江道里区）",
                "cropsname": "玉米",
                "area": "232.0",
                "starttime": 1539137410000,
                "endtime": 1539137410000,
                "address": "asd",
                "mappedarea": "232.0",
                "username": "sdfgsdf"
            }
        ]
    }
    
}

字段说明如下：

| 参数名        | 类型   | 中文意义   | 说明 |
|---------------|--------|------------|------|
| pageNo        | int | 当前页码    |      |
| pageSize      | int | 总页数     |      |
| count         | int | 总任务数     |      |
| userid        | String | 用户id     |      |
| orderid       | String | 订单id     |      |
| name          | String | 任务名称   |      |
| cropsname     | String | 农作物名称 |      |
| area          | double | 地块面积   |      |
| mappedarea    | double | 已测绘亩数 |      |
| address       | double | 作业地址   |      |
| username      | String | 创建人   |      |

历史任务列表
--------------------

### 程序描述

已完成任务列表。

### 调用地址

api/mapping/task/histask 调用方式：GET

### 输入

| 参数名    | 类型 | 中文意义 | 说明 |
|-----------|------|----------|------|
| teamid    | String | 团队id  | 没有此参数返回单飞飞手任务  |
| page_no   | int  | 页码     | 默认为1     |
| page_size | int  | 每页个数 |  默认为10    |

### 输出

JSON格式数据如下：

{

    "status": {
        "code": 0,
        "reasonPhrase": "SUCCESS"
    },
    "data": {
        "pageNo": 1,
        "pageSize": 10,
        "count": 1,
        "list": [
            {
                "id": "2",
                "isNewRecord": false,
                "remarks": null,
                "createDate": 1542966374000,
                "updateDate": null,
                "userid": "03964634bcc942ce8b12642486722677",
                "orderid": "00435f1b94554577b0c834a76e472709",
                "teamid": "22",
                "name": "asd0（黑龙江道里区）",
                "cropsname": "玉米",
                "area": "232.0",
                "starttime": 1539137410000,
                "endtime": 1539137410000,
                "address": "asd",
                "mappedarea": "232.0",
                "username": "sdfgsdf"
            }
        ]
    }
    
}

字段说明如下：

| 参数名        | 类型   | 中文意义   | 说明 |
|---------------|--------|------------|------|
| pageNo        | int | 当前页码    |      |
| pageSize      | int | 总页数     |      |
| count         | int | 总任务数     |      |
| userid        | String | 用户id     |      |
| orderid       | String | 订单id     |      |
| name          | String | 任务名称   |      |
| cropsname     | String | 农作物名称 |      |
| area          | double | 地块面积   |      |
| mappedarea    | double | 已测绘亩数 |      |
| address       | double | 作业地址   |      |
| username      | String | 创建人   |      |

修改任务状态
--------------------

### 程序描述

完成任务、撤回任务、更新任务信息可以用此接口

### 调用地址

api/order/updateinfo 调用方式：POST

### 输入

| 参数名   | 类型   | 中文意义                  | 说明 |
|----------|--------|---------------------------|------|
| taskid | String | 任务id                    |  必填    |
| stauts   | String | 作业状态:0未完成  1:作业中;  2:已完成; |      |
| mapping_acreage | Double | 测绘面积                    |      |
| work_acreage | Double | 作业面积                    |      |
| work_mileage | Double | 作业里程                    |      |

### 输出

JSON格式数据如下：

{

"status": {

"code": 0,

"reasonPhrase": "SUCCESS"

},

"data": [{

"id": "1",

"isNewRecord": false,

"createDate": "2018-11-13 11:46:49", //创建时间

"userid": "1", //用户id

"orderid": "22", //订单id

"name": "22", //任务名称

"pesticidename": "2", //农作物名称

"area": "2", //订单亩数

"starttime": "2018-11-13 11:46:52", //开始时间

"endtime": "2018-11-13 11:46:54", //结束时间

"address": "沈阳", //作业地址

"mappedarea": "22" //已测绘亩数

}]

}

字段说明如下：

| 参数名        | 类型   | 中文意义   | 说明 |
|---------------|--------|------------|------|
| userid        | String | 用户id     |      |
| orderid       | String | 订单id     |      |
| name          | String | 任务名称   |      |
| pesticidename | String | 农作物名称 |      |
| area          | double | 地块面积   |      |
| mappedarea    | double | 已测绘亩数 |      |
| address       | double | 作业地址   |      |

获取禁飞区
--------------------

### 程序描述

获取禁飞区列表

### 调用地址

api/mapping/land/fence 调用方式：GET

### 输入

无

### 输出

JSON格式数据如下：

{

    "status": {
        "code": 0,
        "reasonPhrase": "SUCCESS"
    },
    "data": [
        {
            "id": "02be71c21c61418da66a0c34a4887268",
            "companyId": "a004f591418a4807a8c28c981709ef1d",
            "name": "博乐/阿拉山口",
            "spatialdetail": "82.525,44.895|82.506667,44.833333|82.393333,44.86|82.39091823503001,44.85513578829412|82.38809789411238,44.85049495620406|82.38489247979054,44.846111240382385|82.38132529390934,44.84201650836809|82.37742226822162,44.838240526924686|82.37321177587665,44.83481074564992|82.36872442516074,44.83175209743016|82.3639928369895,44.82908681719017|82.35905140776926,44.82683428025569|82.35393605935141,44.82501086150399|82.34868397789765,44.823629816326296|82.34333334355405,44.822701184267316|82.33792305289958,44.822231716042566|82.33249243618636,44.82222482446381|82.32708097142729,44.822680559629575|82.32172799740968,44.823595608560915|82.31647242772083,44.82496331928524|82.31135246786464,44.82677374919299|82.30640533752575,44.82901373731569|82.301667,44.831667|82.268333,44.833333|82.2633355773741,44.83286024693434|82.25831644551113,44.832782505664746|82.25330677874085,44.833100259050035|82.24833769260447,44.83381153349215|82.24344005059271,44.83491191119443|82.23864427244978,44.83639455760095|82.23398014523318,44.83825026384665|82.22947663830335,44.84046750395453|82.22516172339208,44.843032506424585|82.22106220086725,44.84592933977005|82.21720353327314,44.8491400114694|82.21360968717991,44.85264457971974|82.21030298432498,44.856421277297265|82.20730396297034,44.86044664675576|82.20463125033748,44.864695686123085|82.20230144691176,44.86914200419093|82.20032902333516,44.87375798443325|82.19872623052773,44.87851495653526|82.19750302359583,44.883383374467684|82.196667,44.888333|82.076667,44.895|82.091667,44.956667|82.205,44.93|82.2073350954181,44.93546129047507|82.21016875988056,44.94068132016645|82.21347635206592,44.94561469610995|82.2172291094149,44.950218518059636|82.2213943982472,44.954452751544956|82.22593599754148,44.95828057600734|82.23081441391048,44.961668704988845|82.23598722503235,44.96458767558857|82.24140944855185,44.96701210466968|82.24703393324327,44.96892090958915|82.25281176903383,44.97029749153081|82.2586927123217,44.971129879847254|82.2646256228905,44.97141083615571|82.27055890862046,44.9711379172824|82.27644097412941,44.9703134965082|82.28222066944222,44.96894474293077|82.28784773478684,44.967043559122686|82.29327323764929,44.96462647762754|82.29844999828698,44.961714517194316|82.303333,44.958333|82.333333,44.956667|82.3384111015225,44.95727704659053|82.34352177829001,44.95747768281225|82.34863207607042,44.95726761493972|82.35370904307534,44.95664819751476|82.3587199424371,44.955623424612234|82.3636324632998,44.95419990408579|82.36841492916335,44.952386814959645|82.37303650213737,44.9501958482412|82.37746738178728,44.94764113153608|82.38167899729105,44.94473913795168|82.38564419166708,44.941508579876704|82.38933739688557,44.9379702883215|82.39273479873412,44.93414707859735|82.39581449037453,44.930063603200644|82.39855661360058,44.92574619285083|82.40094348688602,44.92122268670685|82.40295971939717,44.916522252857035|82.40459231023468,44.91167520023995|82.40583073226489,44.90671278320885|82.406667,44.901667",
            "height": "12000",
            "beginTime": "2017-05-10 16:21:30",
            "endTime": "2099-05-10 16:21:30",
            "address": "新疆,博尔塔拉州,博乐市",
            "updateTime": "2018-07-16 16:38:56",
            ...
        }
    ]
    
}

字段说明如下：

| 参数名        | 类型   | 中文意义   | 说明 |
|---------------|--------|------------|------|
| companyId        | String | 公司id     |      |
| spatialdetail       | String | 禁飞区坐标点     |      |
| name          | String | 禁飞区名称   |      |
| height   | String | 高度 |      |

作业app部分接口
========================

获取附近的任务列表
------------------------

### 程序描述

获取附近的五条任务列表

### 功能

获取附近的五条任务列表

### 性能

网络环境稳定的情况下10秒内响应

### 请求方式

POST

### 请求地址

api/work/task/nearTaskList

### 输入

| 参数名   | 类型   | 中文意义                  | 说明 |
|----------|--------|-------------------------|------|
| user_id  | String | 用户id                  |      |
| lon      | Double | 经度                    |      |
| lat      | Double | 纬度                    |      |

### 输出

| 参数名          | 类型   | 中文意义                  | 说明 |
|----------       |--------|-------------------------|------|
| userId          | String | 用户id                  |      |
| id              | String | 任务id                  |      |
| orderId         | String | 订单id                  |      |
| orderName       | String | 订单名称                |      |
| startTime       | String | 开始时间                |      |
| endTime         | String | 结束时间                |      |
| mappingAcreage  | String | 测绘面积                |      |
| address         | String | 作业地址                |      |
| pesticideName   | String | 农药名称                |      |

JSON格式数据如下：

{
    
    "status":{"code":0,"reasonPhrase":"SUCCESS"},
	"data":{
            "list":[{
                     "userId":"***",
                     "id":"***",
                     "orderId":"***",
                     "orderName":"***",
                     "startTime":"***",
                     "endTime":"***",
                     "address":"***",
                     "pesticideName":"***",
                     "mappingAcreage":"***"
			},{
                    "userId":"***",
                     "id":"***",
                     "orderId":"***",
                     "orderName":"***",
                     "startTime":"***",
                     "endTime":"***",
                     "address":"***",
                     "pesticideName":"***",
                     "mappingAcreage":"***"

			}]
    }
    
}


历史任务列表
------------------------

### 程序描述

返回历史任务列表

### 功能

返回历史任务列表

### 性能

网络环境稳定的情况下10秒内响应

### 请求方式

POST

### 请求地址

api/work/task/historyTaskList

### 输入

| 参数名     | 类型   | 中文意义                  | 说明 |
|----------  |--------|-------------------------|------|
| user_id    | String | 用户id                  |      |
| page_no    | String | 当前页                  |      |
| page_size  | String | 总页数                  |      |


### 输出

| 参数名          | 类型   | 中文意义                  | 说明 |
|----------       |--------|------------------------|------|
| userid          | String | 用户id                 |      |
| id              | String | 任务id                 |      |
| orderId         | String | 订单id                  |      |
| orderName       | String | 订单名称                |      |
| startTime       | String | 开始时间                |      |
| endTime         | String | 结束时间                |      |
| workAcreage     | String | 作业面积                |      |
| workTime        | String | 作业时长                |      |
| address         | String | 作业地址               |      |
| pesticideName   | String | 农药名称                |      |

JSON格式数据如下：
{

	"status":{"code":0,"reasonPhrase":"SUCCESS"},
	"data":{
            "list":[{
                     "userid":"***",
                     "id":"***",
                     "orderId":"***",
                     "orderName":"***",
                     "startTime":"***",
                     "endTime":"***",
                     "address":"***",
                     "pesticideName":"***",
                     "workTime":"***",
                     "workAcreage":"***"


			},{
                    "userid":"***",
                     "id":"***",
                     "orderId":"***",
                     "orderName":"***",
                     "startTime":"***",
                     "endTime":"***",
                     "address":"***",
                     "pesticideName":"***",
                     "workTime":"***",
                     "workAcreage":"***"

			}]
    }
    
}

任务状态切换
------------------------

### 程序描述

更改任务状态

### 功能

更改任务状态

### 性能

网络环境稳定的情况下10秒内响应

### 请求方式

POST

### 请求地址

api/work/task/changeTaskStatus

### 输入

| 参数名   | 类型   | 中文意义                  | 说明 |
|----------|--------|-------------------------|-----------------------------|
| task_id  | String | 任务id                  |                             |
| status   | String | 状态                    | 0：作业中 1:已完成2:被完成  |


### 输出

JSON格式数据如下：
{"status":"{code=0, reasonPhrase=SUCCESS}"}

任务详情
------------------------

### 程序描述

返回任务详情

### 功能

返回任务详情

### 性能

网络环境稳定的情况下10秒内响应

### 请求方式

POST

### 请求地址

api/work/task/taskInfo

### 输入

| 参数名   | 类型   | 中文意义                  | 说明 |
|----------|--------|-------------------------|------  |
| task_id  | String | 任务id                  |        |


### 输出

| 参数名          | 类型   | 中文意义                  | 说明 |
|----------       |--------|-------------------------|-----------------------------|
| user_id         | String | 用户id                  |                             |
| id              | String | 任务id                  |                             |
| orderId         | String | 订单id                  |                             |
| orderIame       | String | 订单名称                |                             |
| startTime       | String | 开始时间                |                             |
| endTime         | String | 结束时间                |                             |
| mappingAcreage  | String | 测绘面积                |                             |
| address         | String | 作业地址                |                             |
| pesticideName   | String | 农药名称                |                             |
| status          | String | 作业状态                |  0:作业中;1:已完成;2:被完成'|


地块列表

| 参数名          | 类型   | 中文意义                  | 说明 |
|----------       |--------|-------------------------|-----------------------------|
| landId          | String | 地块id                  |                             |
| landName        | String | 地块名称                |                             |
| workStatus      | String | 作业状态                |  0未作业1正在作业2已完成    |

示例:
{

	"status":{"code":0,"reasonPhrase":"SUCCESS"},
	"data":{
		        "userId":"***",
                "id":"***",
                "orderId":"***",
                "orderName":"***",
                "startTime":"***",
                "endTime":"***",
                "address":"***",
                "pesticideName":"***",
                "mappingAcreage":"***"
        "land_list":
                    [{
				       "landId":"****",
                       "landName":"****",
                       "workStatus":"1"
			        },
			        {
				       "landId":"****",
                       "landName":"****",
                       "workStatus":"1"
			        }]
		    }
		    
}

地块作业信息下载
------------------------

### 程序描述

返回地块作业信息和所有的架次信息

### 调用地址

api/work/land/taskinfo 调用方式：GET

### 输入

| 参数名   | 类型   | 中文意义                  | 说明 |
|----------|--------|-------------------------|------|
| taskid   | String | 任务id                  |      |
| landid   | String | 地块id                  |      |

### 输出

JSON格式数据如下：

{

	"status": {

		"code": 0,

		"reasonPhrase": "SUCCESS"

	},

	"data": [{

		"id": "1",

		"taskid": "asdfasdf",    //任务id

		"landid": "asdfasdf",    //地块id

		"direction": 0,     //0顺时针  1逆时针

		"high": 10, //高度

		"speed": 10, //速度

		"dosage": 10, //用量

		"pwidth": 5, //喷幅

		"margin": 2, //边距

		"sorties": [{

			"id": "asfawefa", //架次id

			"homepoint": {
				"lat": 33,
				"lon": 44
			}, //起飞点

			"returnpoint": {
				"lat": 33,
				"lon": 44
			}, //返航点

			"planning": [{
				"lat": 33,
				"lon": 44
			}] //架次规划点

		}]

	}]

}

字段说明如下：

| 参数名        | 类型   | 中文意义   | 说明 |
|---------------|--------|------------|------|
| landid        | String | 地块id     |      |
| taskid        | String | 任务id     |      |
| direction     | int    | 作业方向   | 0顺时针  1逆时针 |
| high          | double | 高度 |      |
| speed         | double | 速度   |      |
| dosage        | double | 用量 |      |
| pwidth        | double | 喷幅   |      |
| margin        | double | 边距   |      |
| sorties       | List<Sortie> | 架次规划点信息   | Sortie说明如下  |

Sortie各字段说明如下：

| 参数名        | 类型   | 中文意义   | 说明 |
|---------------|--------|------------|------|
| id            | String | 架次id     |      |
| homepoint     | Point  | 起飞点     | Point说明如下 |
| returnpoint   | Point  | 返航点   |   |
| planning      | List<Point> | 架次规划点信息  |      |

Point各字段说明如下：

| 参数名        | 类型   | 中文意义   | 说明 |
|---------------|--------|------------|------|
| lat           | double | 纬度    |      |
| lon           | double | 经度     |      |


地块作业信息上传
------------------------

### 程序描述

上传地块作业信息和所有的架次信息

### 调用地址

api/work/land/uploadtaskinfo 调用方式：POST

### 输入

| 参数名   | 类型   | 中文意义                  | 说明 |
|----------|--------|-------------------------|------|
| taskinfo  | Taskinfo | 作业信息              |  Taskinfo说明如下  |

Taskinfo各字段说明如下：

| 参数名        | 类型   | 中文意义   | 说明 |
|---------------|--------|------------|------|
| landid        | String | 地块id     |      |
| taskid        | String | 任务id     |      |
| direction     | int    | 作业方向   | 0顺时针  1逆时针 |
| high          | double | 高度 |      |
| speed         | double | 速度   |      |
| dosage        | double | 用量 |      |
| pwidth        | double | 喷幅   |      |
| margin        | double | 边距   |      |
| sorties       | List<Sortie> | 架次规划点信息   | Sortie说明见地块作业信息下载接口  |

### 输出
JSON格式数据如下：

{

	"status": {

		"code": 0,

		"reasonPhrase": "SUCCESS"

	}

}

架次轨迹信息上传
------------------------

### 程序描述

上传架次实际飞行轨迹信息，保存到hbase，生成航迹kml文件

### 调用地址

api/work/land/uploadtasktrack 调用方式：POST

### 输入

| 参数名   | 类型   | 中文意义                  | 说明 |
|----------|--------|-------------------------|------|
| tasktrack  | Tasktrace |   架次飞行轨迹信息           |  Tasktrace说明如下  |

Tasktrace各字段说明如下：

| 参数名        | 类型   | 中文意义   | 说明 |
|---------------|--------|------------|------|
| high          | double | 高度 |      |
| speed         | double | 速度   |      |
| flow          | double | 流量 |      |
| pwidth        | double | 喷幅   |      |
| track         | List<TrackPoint> | 实际飞行点信息   | TrackPoint说明如下  |

TrackPoint各字段说明如下：

| 参数名        | 类型   | 中文意义   | 说明 |
|---------------|--------|------------|------|
| lat           | double | 纬度    |      |
| lon           | double | 经度     |      |
| alt           | double | 高度   |     |
| head          | double | 航向 |      |
| bswitch       | int | 开关泵   | 0关  1开   |

### 输出
JSON格式数据如下：

{

	"status": {

		"code": 0,

		"reasonPhrase": "SUCCESS"

	}

}
