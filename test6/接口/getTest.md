### 接口：getTest
用例：<a href="用例/查看实验.md">查看实验</a>
<li>功能：查看实验</li>
<li>权限：学生老师</li>
<li>API请求地址：/api/getTest</li>
<li>请求方式：GET</li>
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
{"status":"1","test_id":"1","name":"test1","selected_course_id":"1","weight":"0.2","update_date":"2018.6.8","test_item_list":[{"test_item_id":"1","test_item_name":"评分项1","test_item_description":"格式正确","test_item_weight":"0.2"}]}
```

<li>参数说明</li>

<li>参数说明<li>
|参数|说明|
|:-|:-|
|status|返回状态，1为查询成功，0为查询失败|
|test_id|实验id|
|name|实验名称|
|selected_course_id|所属开课课程id|
|weight|实验评分权重|
|update_date|修改日期|
|test_item_list|实验评分项列表|
|test_item_id|评分项id|
|test_item_name|评分项名称|
|test_item_description|评分项描述|
|test_item_weight|评分项评分权重|