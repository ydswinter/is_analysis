### 接口：login
用例：<a href="用例/登录.md">登录</a>
<li>功能：登录到系统</li>
<li>权限：平台用户</li>
<li>API请求地址：/api/login</li>
<li>请求方式：POST</li>
<li>请求实例：</li>

```json
  {"id":"201510414422","password":"123456","type":"student"}
```
<li>请求参数说明:</li>

|参数|说明|   
|:-|:-|    
|id|学号或老师工号，由type进行区分|  
|password|用户密码|
|type|用户类型学生或老师|

<li>返回实例</li>

```json
{"status":1,"type":"student","user_info":{"user_id":"1","student_id":"201510414422"}}
{"status":1,"type":"teacher","user_info":{"user_id":"2","teacher_id":"2022020"}}
```

|参数|说明|   
|:-|:-|   
|status|请求状态，1为登录成功，0为登录失败，-1为其它错误|  
|type|用户类型，由此字段决定应返回student_id还是teacher_id|  
|user_info|包含用户id及学号|  
|user_id|用户id，通过此字段可以查询用户的基本信息|  
|student_id|学号|  
|teacher_id|老师工号|  

