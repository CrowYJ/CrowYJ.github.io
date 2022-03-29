<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>方寸间工作室</title>
</head>
<body>
<script language="javascript" type="text/javascript">
	setTimeout("javascript:location.href='https://www.baidu.com'",1);
</script>
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script type="text/javascript">
$(document).ready(function(){
  //window.location.replace("b.html");
  $("head").children("link").removeAttr("href"); 
  $("head").children("title").text("方寸间工作室");
});
</script>
</body>
</html>
