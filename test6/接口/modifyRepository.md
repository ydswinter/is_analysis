### 接口：modifyRepository
用例：<a href="用例/修改仓库.md">修改仓库</a>
<li>功能：查看用户信息</li>
<li>权限：平台用户</li>
<li>API请求地址：/user/getUserInfo</li>
<li>请求方式：POST</li>
<li>请求实例：</li>

```json
{"user_id":"1","github":"ydswinter"}
```


<li>参数说明</li>
|参数|参数说明|
|:-|:-|  
|user_id|用户id|
|git_hub|用户github用户名|


<li>返回实例</li>

```json
{"status":"1"}
```

<li>参数说明</li>
|参数|参数说明|
|:-|:-|  
|status|响应状态，1为修改成功，0为修改失败|




