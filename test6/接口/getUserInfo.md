### 接口：getUserInfo
用例：<a href="用例/查看用户信息.md">查看用户信息</a>
<li>功能：查看用户信息</li>
<li>权限：平台用户</li>
<li>API请求地址：/user/getUserInfo</li>
<li>请求方式：GET</li>
<li>请求实例：</li>

```json
{"user_id","type":"student"}
```

<li>请求参数说明</li>
|参数|参数说明|
|:-|:-|
|user_id|用户的id，对应表user.user_id值|
|type|用户类型，决定返回哪种用户的数据|

<li>返回实例</li>

```json
{"status:1","type":"student","user_id","student_id(teacher_id)":"201510414422","name":"xxx","class(department)":"15软工4班","github":"ydswinter"}
```

<li>返回参数说明</li>
|参数|参数说明|  
|status|响应状态，1为返回成功，0为失败|  
|type|用户类型，student或teacher，决定返回student_id或teacher_id，以及class或department|  
|user_id|用户id|  
|student_id(teacher_id)|学号或老师工号|  
|name|用户真实姓名|  
|class(department)|班级或部门|  
|github|github用户名|  

