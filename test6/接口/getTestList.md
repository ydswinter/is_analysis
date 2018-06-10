### 接口：getTestList
用例：<a href="用例/实验列表.md">实验列表</a>
<li>功能：获取实验列表</li>
<li>权限：学生老师</li>
<li>API请求地址：/api/getTestList</li>
<li>请求方式：GET</li>
<li>请求实例：</li>

```json
{"selected_course_id"}
```

<li>参数说明</li>
|参数|说明|
|:-|:-|
|selected_course_id|选课id|

<li>返回实例</li>

```json
{"status":"1","test_list":[{"test_id":"1"},{"test_id","2"}]}
```

<li>参数说明</li>
|参数|说明|
|:-|:-|
|status|返回状态，1为查到数据并返回，0为未查到数据|
|test_list|实验id列表|
|test_id|实验id|