### 接口：modifyPassword
用例：<a href="用例/修改密码.md">修改密码</a>
<li>功能：修改用户密码</li>
<li>权限：平台用户</li>
<li>API请求地址：/api/login</li>
<li>请求方式：POST</li>
<li>请求实例：</li>

```json
{"user_id":"1","password"}
```

<li>参数说明</li>
|参数|说明|
|:-|:-|
|user_id|用户id|
|password|通过本地合法性验证的密码|

<li>返回实例</li>

```json
{"status":"1"}
```

<li>参数说明</li>
|参数|说明|
|:-|:-|
|status|返回状态，1为修改成功，0为修改失败|