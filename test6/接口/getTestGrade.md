### 接口：getTestGrade
用例：<a href="用例/查看实验成绩.md">查看实验成绩</a>
<li>功能：查看实验成绩</li>
<li>权限：学生，老师</li>
<li>API请求地址：/api/getTestGrade</li>
<li>请求方式：POST</li>
<li>请求实例：</li>

```json
{"student_id":"1","test_id":"1"}
```

<li>参数说明</li>
|参数|说明|
|:-|:-|
|student_id|学号|
|test_id|实验id|

<li>返回实例</li>

```json
{"status":"1","test_id":"1","total_grade_id":"1","test_name":"test1","test_weight":"0.5","result":"90","item_list":[{"test_item_id":"1","item_name":"test_item1","item_description":"格式正确","item_weight":"0.2","item_grade_id":"1","item_result":"90","item_memo":"格式正确","item_update_date":"2018-6-5"}]}
```

<li>参数说明<li>
|参数|说明|
|:-|:-|
|status|返回状态，1为返回查询成功，2为查询失败|
|test_id|实验id|
|total_grade_id|总分id|
|test_name|实验名称|
|test_weight|实验评分权重|
|result|当前实验总分|
|item_list|实验评分项信息数组|
|test_item_id|评分项id|
|item_name|评分项名称|
|item_description|评分项描述|
|item_weight|评分项评分权重|
|item_grade_id|评分项分数id|
|item_result|评分项分数|
|item_memo|评分项评价|
|item_update_date|评分项评改日期|
