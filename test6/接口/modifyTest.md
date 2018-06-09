### 接口：modifyTest
用例：<a href="用例/修改实验.md">修改实验</a>
<li>功能：修改实验</li>
<li>权限：老师</li>
<li>API请求地址：/api/modifyTest</li>
<li>请求方式：POST/li>
<li>请求实例：</li>

```json
{"test_id":"1","name":"test_one",weight:"0.2","modify_item_length":"1","new_item_length":"1","modify_item":[{"test_item_id":"1","name":"评分项1","description":"格式正确","item_weight":0.2}],"new_item":[{"name":"评分项2","description":"格式正确","item_weight":0.2}]}
```

<li>参数说明</li>
|参数|参数说明|  
|:-|:-|  
|test_id|实验id| 
|name|实验名称|  
|weight|实验评分权重|  
|modify_item_length|修改的评分项数量|  
|new_item_length|新增评分项数量|  
|test_item_id|评分项id|
|name|评分项名称|
|description|评分项描述|
|item_weight|评分项评分权重|

<li>返回实例</li>

{"status":1}

<li>参数说明</li>

|参数|参数说明|  
|:-|:-|  
|status|响应状态，1为修改成功，0为修改失败|
