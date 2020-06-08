# 接口文档

## 目录：
[1、员工考勤信息查询](#1员工考勤信息查询)<br/>
[2、员工工资信息查询](#2、员工工资信息查询)<br/>
[3、根据id更新员工信息](#3根据id更新员工信息)<br/>
[4、根据id插入员工信息](#4根据id插入员工信息)<br/>
[5、根据id删除员工](#根据id删除员工)<br/>
[6、用户名密码登陆](#6用户名密码登陆)<br/>

## 1、员工考勤信息查询

### 请求URL：
	49.235.42.82:8081/pub/findAllAttendanceInformation

### 示例：
[49.235.42.82:8081/pub/findAllAttendanceInformation](49.235.42.82:8081/pub/findAllAttendanceInformation)

### 请求方式：
	GET

### 参数类型：param

	无

### 返回示例：

	{
	    "data": [
	        {
	            "id": 2,
	            "name": "二二",
	            "attendanceForfeit": "100",
	            "attendance": "缺勤",
	            "attendanceAward": "0",
	            "attendanceDate": "2，4，6",
	            "date": "2020-02-08T02:28:40.000+0000"
	        },
	        {
	            "id": 3,
	            "name": "三三",
	            "attendanceForfeit": "100",
	            "attendance": "缺勤",
	            "attendanceAward": "0",
	            "attendanceDate": "1，4，7",
	            "date": "2020-01-11T02:34:11.000+0000"
	        },
	        {
	            "id": 4,
	            "name": "四四",
	            "attendanceForfeit": "200",
	            "attendance": "缺勤",
	            "attendanceAward": "0",
	            "attendanceDate": "7，4，7",
	            "date": "2020-01-11T02:34:44.000+0000"
	        },
	        {
	            "id": 5,
	            "name": "五五",
	            "attendanceForfeit": "300",
	            "attendance": "缺勤",
	            "attendanceAward": "0",
	            "attendanceDate": "7，4，7",
	            "date": "2020-02-08T02:21:17.000+0000"
	        },
	        {
	            "id": 6,
	            "name": "七七",
	            "attendanceForfeit": "400",
	            "attendance": "缺勤",
	            "attendanceAward": "0",
	            "attendanceDate": "5，6，7",
	            "date": "2020-02-08T02:39:07.000+0000"
	        },
	        {
	            "id": 7,
	            "name": "插入测试1",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:05:44.000+0000"
	        },
	        {
	            "id": 8,
	            "name": "插入测试2",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:06:28.000+0000"
	        },
	        {
	            "id": 9,
	            "name": "插入测试3",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:07:07.000+0000"
	        },
	        {
	            "id": 10,
	            "name": "修改测试",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:07:48.000+0000"
	        },
	        {
	            "id": 11,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:07:51.000+0000"
	        },
	        {
	            "id": 12,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:08:21.000+0000"
	        },
	        {
	            "id": 13,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:08:26.000+0000"
	        },
	        {
	            "id": 14,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:08:29.000+0000"
	        },
	        {
	            "id": 15,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:08:32.000+0000"
	        },
	        {
	            "id": 16,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:08:38.000+0000"
	        },
	        {
	            "id": 17,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:08:41.000+0000"
	        },
	        {
	            "id": 18,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:09:06.000+0000"
	        },
	        {
	            "id": 19,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:09:09.000+0000"
	        },
	        {
	            "id": 20,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:09:27.000+0000"
	        },
	        {
	            "id": 21,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:09:28.000+0000"
	        },
	        {
	            "id": 22,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:09:31.000+0000"
	        },
	        {
	            "id": 23,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:09:32.000+0000"
	        },
	        {
	            "id": 24,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:09:33.000+0000"
	        },
	        {
	            "id": 25,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:09:34.000+0000"
	        },
	        {
	            "id": 26,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:09:35.000+0000"
	        },
	        {
	            "id": 27,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:09:36.000+0000"
	        },
	        {
	            "id": 28,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:09:37.000+0000"
	        },
	        {
	            "id": 29,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:09:38.000+0000"
	        },
	        {
	            "id": 30,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:09:39.000+0000"
	        },
	        {
	            "id": 31,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:09:40.000+0000"
	        },
	        {
	            "id": 32,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:09:41.000+0000"
	        },
	        {
	            "id": 33,
	            "name": "王五",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-08T04:09:44.000+0000"
	        }
	    ]
	}

## 2、员工工资信息查询

### 请求URL：
	49.235.42.82:8081/pub/findAllSalaryInformation

### 请求方式：
	GET

### 参数类型：
	无

### 返回示例：
	{
	    "data": [
	        {
	            "id": 2,
	            "name": "二二",
	            "basicSalary": "5000.00",
	            "attendanceForfeit": "100",
	            "attendanceAward": "0",
	            "insurance": "200",
	            "personalTax": "0",
	            "realWages": "4700",
	            "date": "2020-02-08T02:28:40.000+0000"
	        },
	        {
	            "id": 3,
	            "name": "三三",
	            "basicSalary": "6000.00",
	            "attendanceForfeit": "100",
	            "attendanceAward": "0",
	            "insurance": "400",
	            "personalTax": "0",
	            "realWages": "5500",
	            "date": "2020-01-11T02:34:11.000+0000"
	        },
	        {
	            "id": 4,
	            "name": "四四",
	            "basicSalary": "7000.00",
	            "attendanceForfeit": "200",
	            "attendanceAward": "0",
	            "insurance": "400",
	            "personalTax": "0",
	            "realWages": "6400",
	            "date": "2020-01-11T02:34:44.000+0000"
	        },
	        {
	            "id": 5,
	            "name": "五五",
	            "basicSalary": "8000.00",
	            "attendanceForfeit": "300",
	            "attendanceAward": "0",
	            "insurance": "500",
	            "personalTax": "0",
	            "realWages": "7500",
	            "date": "2020-02-08T02:21:17.000+0000"
	        },
	        {
	            "id": 6,
	            "name": "七七",
	            "basicSalary": "9000.00",
	            "attendanceForfeit": "400",
	            "attendanceAward": "0",
	            "insurance": "500",
	            "personalTax": "0",
	            "realWages": "8100",
	            "date": "2020-02-08T02:39:07.000+0000"
	        },
	        {
	            "id": 7,
	            "name": "插入测试1",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:05:44.000+0000"
	        },
	        {
	            "id": 8,
	            "name": "插入测试2",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:06:28.000+0000"
	        },
	        {
	            "id": 9,
	            "name": "插入测试3",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:07:07.000+0000"
	        },
	        {
	            "id": 10,
	            "name": "修改测试",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:07:48.000+0000"
	        },
	        {
	            "id": 11,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:07:51.000+0000"
	        },
	        {
	            "id": 12,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:08:21.000+0000"
	        },
	        {
	            "id": 13,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:08:26.000+0000"
	        },
	        {
	            "id": 14,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:08:29.000+0000"
	        },
	        {
	            "id": 15,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:08:32.000+0000"
	        },
	        {
	            "id": 16,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:08:38.000+0000"
	        },
	        {
	            "id": 17,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:08:41.000+0000"
	        },
	        {
	            "id": 18,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:09:06.000+0000"
	        },
	        {
	            "id": 19,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:09:09.000+0000"
	        },
	        {
	            "id": 20,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:09:27.000+0000"
	        },
	        {
	            "id": 21,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:09:28.000+0000"
	        },
	        {
	            "id": 22,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:09:31.000+0000"
	        },
	        {
	            "id": 23,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:09:32.000+0000"
	        },
	        {
	            "id": 24,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:09:33.000+0000"
	        },
	        {
	            "id": 25,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:09:34.000+0000"
	        },
	        {
	            "id": 26,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:09:35.000+0000"
	        },
	        {
	            "id": 27,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:09:36.000+0000"
	        },
	        {
	            "id": 28,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:09:37.000+0000"
	        },
	        {
	            "id": 29,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:09:38.000+0000"
	        },
	        {
	            "id": 30,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:09:39.000+0000"
	        },
	        {
	            "id": 31,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:09:40.000+0000"
	        },
	        {
	            "id": 32,
	            "name": "待定",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:09:41.000+0000"
	        },
	        {
	            "id": 33,
	            "name": "王五",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-08T04:09:44.000+0000"
	        }
	    ]
	}


## 3、根据id更新员工信息

### 请求URL：
	49.235.42.82:8081/pub/UpdateStaff

### 请求方式：
	Post

### 参数类型：请求体
	
	|参数		|是否必选 |类型     |说明
	|id       |Y       |int  |编号
	|name       |N       |string   |用户名
	|password   |N       |string   |密码
	....

### **请求示例**

![1581086657369](C:\Users\ck\AppData\Roaming\Typora\typora-user-images\1581086657369.png)

### 返回示例：

	{
	    "data": "姓名为zz的员工信息修改成功"
	}


## 4、根据id插入员工信息

### 请求URL：
	49.235.42.82:8081/pub/InsertStaff

### 请求方式：
    Post

### 参数类型：请求体
	|参数          |是否必选  |类型     |说明|
	|name      |N       |string    |姓名
	|password      |N       |string    |密码
	|telephone   |N        |string    |电话 

### 请求示例

![1581087001017](C:\Users\ck\AppData\Roaming\Typora\typora-user-images\1581087001017.png)

### 返回示例：

	{
	    "data": 1
	}

## 5、根据id删除员工

### 请求URL：
	http://localhost:3000/captcha

### 请求方式：
	DELETE

### 参数类型：param

```
|参数          |是否必选  |类型     |说明|
|id           |Y       |int     |编号

```

### 请求示例

![1581087325473](C:\Users\ck\AppData\Roaming\Typora\typora-user-images\1581087325473.png)

### 返回示例：

    {
        "data": "编号为10的员工信息删除成功"
    }


## 6、用户名密码登陆

### 请求URL：
	49.235.42.82:8081/pub/login

### 请求方式：
	POST

### 参数类型: 请求体

	|参数		|是否必选 |类型     |说明
	|name       |Y       |string   |用户名
	|pwd        |Y       |string   |密码
	

### 请求示例

![1581087592935](C:\Users\ck\AppData\Roaming\Typora\typora-user-images\1581087592935.png)

### 返回示例：

    * 登陆成功
    {
        "data": {
            "msg": "登录成功",
            "session_id": "89e25434-8048-4a6e-960a-74082258eae6"
        }
    }
    * 登陆失败
    {
        "code": -1,
        "msg": "账号或者密码错误"
    }

#### 
    