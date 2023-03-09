#1 html表单主要功能是收集信息，具体是收集浏览者的信息，HTML表单是HTML页面与浏览器实现交互重要手段。
#2 表单标记：HTML表单用于搜集不同类型的用户输入，使用<form>定义。
例如：<form action="action_page.php"
method="GET"
target="_blank"
ectype="application/x-www-form-urlencoded">

#3 html表单元素主要包括<input>元素，//<textarea>,<select>,<button>元素；
#4 表单属性：
1，name 属性规定表单的名称；
2，action 属性规定当提交表单，向何处发送表单数据；
3，method 方法规定如何发送表单数据（form-data）(表单数据会被发送到在action属性中规定的页面中)
get:默认。将表单数据（form-data）以名称/值对的形式附加到URL中：URL？name=value&name=value.
Post:以HTTPpost事务的形式发送表单数据（form-data）。
4 target：属性规定一个名称或者一个关键词，指示在何处打开actionURL，即在何处显示提交表单后接收到的响应；
