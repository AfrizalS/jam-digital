
<html>
<head>
<title>I LOVE YOU</title>
<script type="text/javascript">
 window.onload = function() { jam(); }

 function jam() {
  var e = document.getElementById('jam'),
  d = new Date(), h, m, s;
  h = d.getHours();
  m = set(d.getMinutes());
  s = set(d.getSeconds());

  e.innerHTML = h +':'+ m +':'+ s;

  setTimeout('jam()', 1000);
 }

 function set(e) {
  e = e < 10 ? '0'+ e : e;
  return e;
 }
</script>
</head>
<body>
<center>
  <p></p>
  <p></P>
<h1 style="font-size: 120px; font-family: MODERN;" id="jam"></h1>
  <P> Wong Kakean Duso &copy; 2020 minutes.co </p>
</center>
</body>
</html>
