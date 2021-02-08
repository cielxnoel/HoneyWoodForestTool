
<html>
<head>
	<style>
	p {font-family: Arial, Helvetica, sans-serif;}
	h1 {font-family: Arial, Helvetica, sans-serif;}
	</style>
</head>
<body>

<!-- Edited code to make it suitable for Honeywood Forest -->
<center>
	<img src="https://files.peakd.com/file/peakd-hive/justatouchfey/3HMqsZhy-honeywood_small_header.png">
<h1>&nbsp;</h1>
<h1>Press to roll for your turn:</h1>

<button onclick="myD6()">Roll!</button>
<p></p>
<h1>You rolled a:</h1>
<p id="d6"></p>

<p>Return to today's game post and comment to make your move!</p>

<script>
function myD6() {
  var x = document.getElementById("d6")
  x.innerHTML = Math.floor((Math.random() * 6) + 1);
}
</script>
<p></p>

</center>
</body>
</html>
