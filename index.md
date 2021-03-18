<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title></title>	
	</head>
	<body>
		<div id="app">
			下午的课程是{{message}}.
		</div>
		
		<script src="js/vue.js" type="text/javascript" charset="utf-8"></script>
		<script type="text/javascript">
			let v=new Vue({
				el:'#app',
				data:{
					message:"HTML5开发技术"
				}
			})	
		</script>
		
	</body>
</html>
