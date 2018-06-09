### 接口：getStudentList
用例：<a href="用例/学生列表.md">学生列表</a>
<li>功能：获取学生列表</li>
<li>权限：平台用户</li>
<li>API请求地址：/api/getStudentList</li>
<li>请求方式：GET</li>
<li>请求实例：</li>

```json
{"base_course_id":"1"}
```
<li>参数说明</li>
|参数|说明|
|:-|:-|
|base_course_id|基本课程id，查找selected_course表中base_course_id相同的student_id字段|

<li>返回实例</li>

```json
{"status":"1","student_list":[{"student_id":"1"},{"student_id":"2"}]}
```
<li>参数说明</li>
|参数|说明|
|:-|:-|
|status|返回状态，1为查询到数据，0为未查询到数据|
|student_list|学生id列表|
|student_id|学生id|