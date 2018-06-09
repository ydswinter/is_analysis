### 接口：deleteTest
用例：<a href="用例/删除实验.md">删除实验</a>
<li>功能：删除实验</li>
<li>权限：老师</li>
<li>API请求地址：/api/deleteTest</li>
<li>请求方式：POST</li>
<li>请求实例：</li>

```json
{"test_id"}
```

<li>参数说明<li>
|参数|说明|
|:-|:-|
|test_id|实验id|

<li>返回实例</li>

```json
{"status":"1"}
```

<li>参数说明</li>
|参数|说明|
|:-|:-|
|status|返回状态，1为删除成功，0为删除失败|