# 接口文档

## 目录：
[1、员工考勤信息查询](#1员工考勤信息查询)<br/>
[2、员工工资信息查询](#2、员工工资信息查询)<br/>
[3、根据id更新员工信息](#3根据id更新员工信息)<br/>
[4、插入员工信息](#4根据id插入员工信息)<br/>
[5、根据id删除员工](#根据id删除员工)<br/>
[6、用户名密码登陆](#6用户名密码登陆)<br/>
[7、查询所有垃圾桶信息](#7、查询所有垃圾桶信息)<br/>
[8、垃圾桶信息新增](#8、垃圾桶信息新增)<br/>
[9、垃圾桶编号查询](#9、垃圾桶编号查询)<br/>
[10、垃圾桶信息删除](#10垃圾桶信息删除)<br/>
[11、查询全部管理员信息](#11查询全部管理员信息)<br/>
[12、根据id查询管理员信息](#12、根据id查询管理员信息)<br/>
[13、管理员信息新增](#13、管理员信息新增)<br/>
[14、管理员信息修改](#14、管理员信息修改)<br/>
[15、管理员信息删除](#15、管理员信息删除)<br/>
[16、查询全部APP员工信息](#16、查询全部APP员工信息)<br/>
[17、根据id查询APP员工信息](#17、根据id查询APP员工信息)<br/>
[18、APP员工信息新增](#8、APP员工信息新增)<br/>
[19、APP员工信息修改](#9、APP员工信息修改)<br/>
[20、APP员工信息删除](#10APP员工信息删除)<br/>

## 1、员工考勤信息查询

### 请求URL：
	49.235.42.82:8081/authc/findAllAttendanceInformation

### 示例：
[49.235.42.82:8081/authc/findAllAttendanceInformation](49.235.42.82:8081/pub/findAllAttendanceInformation)

### 请求方式：
	GET

### 参数类型：param

	无

### 返回示例：

	{
	    "code": 2,
	    "data": [
	        {
	            "id": 2,
	            "name": "一一",
	            "attendanceForfeit": "100",
	            "attendance": "缺勤",
	            "attendanceAward": "0",
	            "attendanceDate": "2，4，6",
	            "date": "2020-02-13T02:34:55.000+0000"
	        },
	        {
	            "id": 3,
	            "name": "三三",
	            "attendanceForfeit": "100",
	            "attendance": "缺勤",
	            "attendanceAward": "0",
	            "attendanceDate": "1，4，7",
	            "date": "2020-02-13T02:35:09.000+0000"
	        },
	        {
	            "id": 4,
	            "name": "四四",
	            "attendanceForfeit": "200",
	            "attendance": "缺勤",
	            "attendanceAward": "0",
	            "attendanceDate": "7，4，7",
	            "date": "2020-02-13T02:35:11.000+0000"
	        },
	        {
	            "id": 5,
	            "name": "五五",
	            "attendanceForfeit": "300",
	            "attendance": "缺勤",
	            "attendanceAward": "0",
	            "attendanceDate": "7，4，7",
	            "date": "2020-02-13T02:35:12.000+0000"
	        },
	        {
	            "id": 6,
	            "name": "七七",
	            "attendanceForfeit": "400",
	            "attendance": "缺勤",
	            "attendanceAward": "0",
	            "attendanceDate": "5，6，7",
	            "date": "2020-02-13T02:35:13.000+0000"
	        },
	        {
	            "id": 7,
	            "name": "二二",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-13T02:35:14.000+0000"
	        },
	        {
	            "id": 8,
	            "name": "六六",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-13T02:35:19.000+0000"
	        },
	        {
	            "id": 9,
	            "name": "员工信息更新测试",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-13T03:33:29.000+0000"
	        },
	        {
	            "id": 11,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-12T23:10:49.000+0000"
	        },
	        {
	            "id": 12,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-12T23:10:50.000+0000"
	        },
	        {
	            "id": 13,
	            "name": "待定",
	            "attendanceForfeit": "0",
	            "attendance": "0",
	            "attendanceAward": "0",
	            "date": "2020-02-12T23:11:06.000+0000"
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
	            "date": "2020-02-13T02:35:16.000+0000"
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
	        },
	        {
	            "id": 34,
	            "name": "zz"
	        },
	        {
	            "id": 35,
	            "name": "测试"
	        },
	        {
	            "id": 36,
	            "name": "333"
	        }
	    ],
	    "msg": "传入成功"
	}

## 2、员工工资信息查询

### 请求URL：
	49.235.42.82:8081/authc/findAllSalaryInformation

### 请求方式：
	GET

### 参数类型：
	无

### 返回示例：
	{
	    "code": 2,
	    "data": [
	        {
	            "id": 2,
	            "name": "一一",
	            "basicSalary": "5000.00",
	            "attendanceForfeit": "100",
	            "attendanceAward": "0",
	            "insurance": "200",
	            "personalTax": "0",
	            "realWages": "4700",
	            "date": "2020-02-13T02:34:55.000+0000"
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
	            "date": "2020-02-13T02:35:09.000+0000"
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
	            "date": "2020-02-13T02:35:11.000+0000"
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
	            "date": "2020-02-13T02:35:12.000+0000"
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
	            "date": "2020-02-13T02:35:13.000+0000"
	        },
	        {
	            "id": 7,
	            "name": "二二",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-13T02:35:14.000+0000"
	        },
	        {
	            "id": 8,
	            "name": "六六",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-13T02:35:19.000+0000"
	        },
	        {
	            "id": 9,
	            "name": "员工信息更新测试",
	            "basicSalary": "0.00",
	            "attendanceForfeit": "0",
	            "attendanceAward": "0",
	            "insurance": "0",
	            "personalTax": "0",
	            "realWages": "0",
	            "date": "2020-02-13T03:33:29.000+0000"
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
	            "date": "2020-02-12T23:10:49.000+0000"
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
	            "date": "2020-02-12T23:10:50.000+0000"
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
	            "date": "2020-02-12T23:11:06.000+0000"
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
	            "date": "2020-02-13T02:35:16.000+0000"
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
	        },
	        {
	            "id": 34,
	            "name": "zz"
	        },
	        {
	            "id": 35,
	            "name": "测试"
	        },
	        {
	            "id": 36,
	            "name": "333"
	        }
	    ],
	    "msg": "传入成功"
	}


## 3、根据id更新员工信息

### 请求URL：
	49.235.42.82:8081/authc/UpdateStaff

### 请求方式：
	Post

### 参数类型：请求体

	|参数		|是否必选 |类型     |说明
	|id       |Y       |int  |编号
	|name       |N       |string   |用户名
	|password   |N       |string   |密码
	....

### **请求示例**

![1581570053285](C:\Users\ck\AppData\Roaming\Typora\typora-user-images\1581570053285.png)

### 返回示例：

	{
	    "code": 2,
	    "data": "姓名为员工信息更新测试的员工信息修改成功",
	    "msg": "传入成功"
	}


## 4、插入员工信息

### 请求URL：
	49.235.42.82:8081/authc/InsertStaff

### 请求方式：
    Post

### 参数类型：请求体
	|参数          |是否必选  |类型     |说明|
	|name      |N       |string    |姓名
	|password      |N       |string    |密码
	|telephone   |N        |string    |电话 

### 请求示例

![1581570227644](C:\Users\ck\AppData\Roaming\Typora\typora-user-images\1581570227644.png)

### 返回示例：

	{
	    "code": 2,
	    "data": 1,
	    "msg": "传入成功"
	}

## 5、根据id删除员工

### 请求URL：
	49.235.42.82:8081/authc/DeleteStaffById

### 请求方式：
	DELETE

### 参数类型：param

```
|参数          |是否必选  |类型     |说明|
|id           |Y       |int     |编号

```

### 请求示例

![1581570612043](C:\Users\ck\AppData\Roaming\Typora\typora-user-images\1581570612043.png)

### 返回示例：

    {
        "code": 2,
        "data": "编号为35的员工信息删除成功",
        "msg": "传入成功"
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

![1581570695440](C:\Users\ck\AppData\Roaming\Typora\typora-user-images\1581570695440.png)

### 返回示例：

    * 登陆成功
    {
        "code": 2,
        "data": {
            "msg": "登录成功",
            "session_id": "b5cd8c98-a66c-49dc-87d7-efc3946fba0d"
        },
        "msg": "传入成功"
    }
    * 登陆失败
    {
        "code": -1,
        "msg": "账号或者密码错误"
    }

#### 

### 7.查询所有垃圾桶信息 

### 请求URL：

```
49.235.42.82:8081/authc/findAllTrashCanInfo
```

### 请求方式：

```
GET
```

### 参数类型: 请求体

```
无
```

### 返回示例

```
{
    "code": 2,
    "data": [
        {
            "id": 1,
            "address": "中南民族大学北区",
            "status": "70%",
            "x": "114.4017145129112",
            "y": "30.500638050731386",
            "health": "正常",
            "lable": 2,
            "tel": "10086",
            "contact": "一一"
        },
        {
            "id": 2,
            "address": "中南民族大学北区",
            "status": "70%",
            "x": "114.4017145129112",
            "y": "30.500638050731386",
            "health": "正常",
            "lable": 2,
            "tel": "10087",
            "contact": "二二"
        },
        {
            "id": 3,
            "address": "中南民族大学北区",
            "status": "70%",
            "x": "114.4017145129112",
            "y": "30.50063805073138630.500638050731386",
            "health": "正常",
            "lable": 2,
            "tel": "10088",
            "contact": "三三"
        },
        {
            "id": 4,
            "address": "中南民族大学北区",
            "status": "70%",
            "x": "114.4017145129112",
            "y": "30.500638050731386",
            "health": "正常",
            "lable": 2,
            "tel": "10089",
            "contact": "四四"
        },
        {
            "id": 5,
            "address": "中南民族大学北区",
            "status": "70%",
            "x": "114.4017145129112",
            "y": "30.500638050731386",
            "health": "正常",
            "lable": 2,
            "tel": "10090",
            "contact": "五五"
        },
        {
            "id": 6,
            "address": "中南民族大学北区",
            "status": "70%",
            "x": "114.4017145129112",
            "y": "30.500638050731386",
            "health": "正常",
            "lable": 2,
            "tel": "10091",
            "contact": "六六"
        }
    ],
    "msg": "传入成功"
}
```

### 8.垃圾桶信息新增

### 请求URL：

```
49.235.42.82:8081/authc/insertTrashCan
```

### 请求方式：

POST

### 参数类型: 请求体

```
|参数		|是否必选 |类型     |说明
|address  |N      |String   |垃圾桶地址
....
....
```

### 请求示例

![1581571312841](C:\Users\ck\AppData\Roaming\Typora\typora-user-images\1581571312841.png)

### 返回示例

```
{
    "code": 2,
    "data": "8号垃圾桶信息插入成功",
    "msg": "传入成功"
}
```

### 9.垃圾桶编号查询

### 请求URL：

```
49.235.42.82:8081/authc/findAllTrahCanId
```

### 请求方式：

GET

### 参数类型

```
无
```

### 返回示例

```
{
    "code": 2,
    "data": [
        1,
        2,
        3,
        4,
        5,
        6,
        8
    ],
    "msg": "传入成功"
}
```

### 10.垃圾桶信息删除

### 请求URL：

```
49.235.42.82:8081/authc/deleteTrashCanById
```

### 请求方式：

DELETE

### 参数类型：param

```
|参数		|是否必选 |类型     |说明
|id      |Y       |int     |垃圾桶编号
....
....
```

### 返回示例

```
{
    "code": 2,
    "data": "8号垃圾桶删除成功",
    "msg": "传入成功"
}
```



### 11.查询全部管理员信息

### 请求URL：

```
49.235.42.82:8081/authc/findAllAdminInfo
```

### 请求方式：

GET

### 参数类型：param

```
无
```

### 返回示例

```
{
    "code": 2,
    "data": [
        {
            "id": 1,
            "username": "admin",
            "password": "123456",
            "name": "zqx",
            "tel": "13647658974",
            "permission": "系统管理员",
            "status": "正常"
        },
        {
            "id": 2,
            "username": "admin",
            "password": "123456",
            "name": "zqx1",
            "tel": "11",
            "permission": "系统管理员",
            "status": "正常"
        },
        {
            "id": 3,
            "username": "admin",
            "password": "123456",
            "name": "zqx2",
            "tel": "12",
            "permission": "系统管理员",
            "status": "正常"
        },
        {
            "id": 4,
            "username": "admin",
            "password": "123456",
            "name": "zqx3",
            "tel": "12",
            "permission": "系统管理员",
            "status": "正常"
        },
        {
            "id": 5,
            "username": "admin",
            "password": "123456",
            "name": "zqx4",
            "tel": "331",
            "permission": "系统管理员",
            "status": "正常"
        }
    ],
    "msg": "传入成功"
}
```



### 12.根据id查询管理员信息

### 请求URL：

```
49.235.42.82:8081/authc/findAdminInfoById
```

### 请求方式：

GET

### 参数类型：param

```
|参数		|是否必选 |类型     |说明
|id      |Y       |int     |管理员编号
....
....
```

### 返回示例

```
{
    "code": 2,
    "data": {
        "id": 1,
        "username": "admin",
        "password": "123456",
        "name": "zqx",
        "tel": "13647658974",
        "permission": "系统管理员",
        "status": "正常"
    },
    "msg": "传入成功"
}
```



### 13.管理员信息新增

### 请求URL：

```
49.235.42.82:8081/authc/insertAdmin
```

### 请求方式：

POST

### 参数类型: 请求体

```
|参数		|是否必选 |类型     |说明
|name    |N      |String     |登录名
|password|N       |String    |登陆密码
....
....
```

### 请求示例

![1581572373097](C:\Users\ck\AppData\Roaming\Typora\typora-user-images\1581572373097.png)

### 返回示例

```
{
    "code": 2,
    "data": 1,
    "msg": "传入成功"
}
```



### 14.管理员信息修改

### 请求URL：

```
49.235.42.82:8081/authc/updateAdmin
```

### 请求方式：

POST

### 参数类型: 请求体

```
|参数		|是否必选 |类型     |说明
|id      |Y     |int     |管理员编号
|password|N       |String    |登陆密码
....
....
```

### 请求示例

![1581572578059](C:\Users\ck\AppData\Roaming\Typora\typora-user-images\1581572578059.png)

### 返回示例

```
{
    "code": 2,
    "data": "id为7的员工信息修改成功",
    "msg": "传入成功"
}
```

### 15.管理员信息删除

### 请求URL：

```
49.235.42.82:8081/authc/deleteAdminById
```

### 请求方式：

DELETE

### 参数类型：param

```
|参数		|是否必选 |类型     |说明
|id      |Y     |int     |管理员编号

```

### 返回示例

```
{

    "code": 2,

    "data": "id为7的员工信息删除成功",

    "msg": "传入成功"

}
```



### 16.查询全部APP员工信息

### 请求URL：

```
49.235.42.82:8081/authc//findAllStaffBaseInfo
```

### 请求方式：

GET

### 参数类型：param

```
无
```

### 返回示例

```
{
    "code": 2,
    "data": [
        {
            "id": 2,
            "name": "一一",
            "telephone": "10086",
            "password": "123456",
            "canNum": 1,
            "username": "yiyi",
            "status": "正常"
        },
        {
            "id": 3,
            "name": "三三",
            "telephone": "10088",
            "password": "1242121",
            "canNum": 3,
            "username": "sansan",
            "status": "正常"
        },
        {
            "id": 4,
            "name": "四四",
            "telephone": "10089",
            "password": "123456789",
            "canNum": 4,
            "username": "sisi",
            "status": "正常"
        },
        {
            "id": 5,
            "name": "五五",
            "telephone": "10090",
            "password": "1113133",
            "canNum": 5,
            "username": "wuwu",
            "status": "正常"
        },
        {
            "id": 6,
            "name": "七七",
            "telephone": "10092",
            "password": "jjjjdkc",
            "canNum": 7,
            "username": "qiqi",
            "status": "正常"
        },
        {
            "id": 7,
            "name": "二二",
            "telephone": "10087",
            "password": "sssss",
            "canNum": 2,
            "username": "erer",
            "status": "正常"
        },
        {
            "id": 8,
            "name": "六六",
            "telephone": "10091",
            "password": "sssss",
            "canNum": 6,
            "username": "liuliu",
            "status": "正常"
        },
        {
            "id": 9,
            "name": "员工信息更新测试",
            "telephone": "4444",
            "password": "sssss",
            "canNum": 7,
            "status": "test"
        },
        {
            "id": 11,
            "name": "员工信息更新测试",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 12,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 13,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 14,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 15,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 16,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 17,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 18,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 19,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 20,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 21,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 22,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 23,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 24,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 25,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 26,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 27,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 28,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 29,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 30,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 31,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss",
            "status": "正常"
        },
        {
            "id": 32,
            "name": "待定",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 33,
            "name": "王五",
            "telephone": "4444",
            "password": "sssss"
        },
        {
            "id": 34,
            "name": "zz"
        },
        {
            "id": 36,
            "name": "333",
            "password": "zqx123456"
        },
        {
            "id": 37,
            "name": "员工信息插入测试"
        }
    ],
    "msg": "传入成功"
}
```



### 17.根据id查询APP员工信息

### 请求URL：

```
49.235.42.82:8081/authc/findStaffBaseInfoById
```

### 请求方式：

GET

### 参数类型：param

```
|参数		|是否必选 |类型     |说明
|id      |Y       |int     |APP员工编号
....
....
```

### 返回示例

```
{
    "code": 2,
    "data": {
        "id": 2,
        "name": "一一",
        "telephone": "10086",
        "password": "123456",
        "canNum": 1,
        "username": "yiyi",
        "status": "正常"
    },
    "msg": "传入成功"
}
```



### 18.APP员工信息新增

### 请求URL：

```
49.235.42.82:8081/authc/InsertStaff
```

### 请求方式：

```
Post
```

### 参数类型：请求体

```
|参数          |是否必选  |类型     |说明|
|name      |N       |string    |姓名
|password      |N       |string    |密码
|telephone   |N        |string    |电话 
```

### 请求示例

![1581570227644](C:\Users\ck\AppData\Roaming\Typora\typora-user-images\1581570227644.png)



### 返回示例

```
{
    "code": 2,
    "data": 1,
    "msg": "传入成功"
}
```



### 19.APP员工信息修改

### 请求URL：

```
49.235.42.82:8081/authc/UpdateStaff
```

### 请求方式：

POST

### 参数类型: 请求体

```
|参数		|是否必选 |类型     |说明
|id      |Y     |int       |员工编号 
...
....
....
```

### 请求示例

![1581570053285](C:\Users\ck\AppData\Roaming\Typora\typora-user-images\1581570053285.png)

### 返回示例

```
{
    "code": 2,
    "data": "姓名为员工信息更新测试的员工信息修改成功",
    "msg": "传入成功"
}
```

### 20.APP员工信息删除

### 请求URL：

```
49.235.42.82:8081/authc/DeleteStaffById
```

### 请求方式：

DELETE

### 参数类型：param

```
|参数		|是否必选 |类型     |说明
|id      |Y     |int     |APP员工编号

```

### 返回示例

```
{

    "code": 2,

    "data": "id为7的员工信息删除成功",

    "msg": "传入成功"

}
```

