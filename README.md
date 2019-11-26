<html>
<head>
<title>firstPage</title>
<style type="text/css">
body { background:white; color:white; font-size:10pt; }
</style>
</head>
<body>
<br><br>
<form name=pw><input type=text name=input_pwd><input type=button value="check" onclick=ck()></form>
<script>
function ck(){
  var ul=document.URL;
  ul=ul.indexOf("C");
  ul=ul*10;
  if(ul==pw.input_pwd.value) { /*location.href="?"+ul*pw.input_pwd.value;*/ location.href="secondPage.html" }
  else { alert("Wrong"); }
}
</script>
</body>
</html>
