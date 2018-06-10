### 接口：addTest
用例：<a href="用例/添加实验.md">添加实验</a>
<li>功能：添加实验</li>
<li>权限：老师</li>
<li>API请求地址：/api/addTest</li>
<li>请求方式：POST</li>
<li>请求实例：</li>

{"test_name":"test1","selected_course_id":"1","weight":"0.5","item_list":[{"item_name":"test_item1","item_description":"格式正确","item_weight":"0.2"}]}

<li>参数说明</li>
|参数|说明|
|:-|:-|
|test_name|实验名称|
|selected_course_id|选课id|
|weight|实验评分权重|
|item_list|评分项信息列表|
|item_name|评分项名称|
|item_description|格式正确|
|item_weight|评分项评分权重|

<li>返回实例</li>

{"status":"1"}

<li>参数说明</li>
|参数|说明|
|:-|:-|
|status|返回响应，1为添加成功，0为添加失败|