<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>IFE JavaScript Task 01</title>
</head>
<body>
	<lable>请输入北京今天空气质量：<input id="aqi-input" type="text"></lable>
	<button id="button">确认填写</button>

	<div>您输入的值是:<span id="aqi-display">尚无记录</span></div>

	<script type="text/javascript">
		(function(){
			document.getElementById('button').onclick=function(){
				var inputVar=document.getElementById("aqi-input").value;
				document.getElementById("aqi-display").innerHTML=inputVar;
			};
		})();
	</script>
</body>
</html>
