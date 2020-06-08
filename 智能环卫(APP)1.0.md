# 接口文档

## 目录：
[1、登陆](#1登陆)<br/>
[2、签到](#2、签到)<br/>
[3、考勤记录查询](#3根据id更新员工信息)<br/>

## 1、登陆

### 请求URL：
	49.235.42.82:8081/pub/Applogin

### 示例：
![1583563532923](C:\Users\ck\AppData\Roaming\Typora\typora-user-images\1583563532923.png)

### 请求方式：
	POST

### 参数类型：请求体

	|参数		|是否必选 |类型     |说明
	|name       |Y       |string   |用户名
	|password       |Y       |string   |密码

### 返回示例：

	* 登陆成功
	{
	    "code": 2,
	    "data": 2,  //data里的数据为员工编号
	    "msg": "传入成功"
	}
	* 登陆失败
	{
	    "code": -1,
	    "msg": "账号或密码错误"
	}

## 2、签到

### 请求URL：
	49.235.42.82:8081/pub/InsertAttenceRecord

### 请求方式：
	POST

### 参数类型：请求体
	|参数		     |是否必选 |类型           |说明
	|staffId      |Y       |int      |员工编号
	|x            |Y       |string   |位置坐标
	|y            |Y       |string   |位置坐标

### 返回示例：
	{
	    "code": 2,
	    "data": 1,
	    "msg": "传入成功"
	}


## 3、考勤记录查询

### 请求URL：
	49.235.42.82:8081/pub/findAttendanceRecrodByStaffId

### 请求方式：
	GET

### 参数类型：Param

	|参数		|是否必选 |类型     |说明
	|staffId  |Y      |int     |员工编号
	

### **请求示例**

49.235.42.82:8081/pub/findAttendanceRecrodByStaffId?staffId=2

### 返回示例：

	{
	    "code": 2,
	    "data": [
	        "2020-03-06T16:28:18.715+0000",
	        "2020-03-06T16:28:19.668+0000",
	        "2020-03-06T16:28:20.524+0000",
	        "2020-03-06T16:28:21.321+0000",
	        "2020-03-07T06:48:48.402+0000"
	    ],
	    "msg": "传入成功"
	}

