#### 打印一个格式类似“2019-10-08”的日期

```javascript
function formatDate(dt){
	if(!dt){
	dt = new Date();
	}
	var y = dt.getFullYear();
	var m = (dt.getMonth() + 1).toString().padStart(2,'0');
	var d = (dt.getDate()).toString().padStart(2,'0');
	return `${y}-${m}-${d}`;
}
```

#### 输出定长字符串



#### 写一个函数，要求既能遍历数组，又能遍历对象

