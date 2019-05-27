## cdn:
https://cdn.bootcss.com/vue

## 第一步：
引入vuejs源：<script src="https://cdn.bootcss.com/vue/2.6.10/vue.common.dev.js"></script>

## 使用方式：

```
<head>
	<meta charset="utf-8">
	<title></title>
	<script src="https://cdn.bootcss.com/vue/2.6.10/vue.common.dev.js"></script>
</head>
<body>
	<div id="app"> 这个声明vue的挂载点
		My name is {{name}},
		I'm {{age}} years old.
	</div>
</body>
<script>
	let vm = new Vue({
		el:"#app",
		data:{
			name:'stark',
			age:18
		},
	})
</script>

```