
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
<h1>Press to pull a card for your turn:</h1>
<button onclick="myItem()">Pull a card!</button>

<script>
function myItem() {
var myArray = [
  "You found berries!",
  "You found nuts!",
  "You found roots!",
  "You found a fish!",
  "You found a honeycomb!",
  "You found insects!",
  "You found some meat!",
  "You found some mushrooms!",
  "You found berries!",
  "You found nuts!",
  "You found roots!",
  "You found a fish!",
  "You found a honeycomb!",
  "You found insects!",
  "You found some meat!",
  "You found some mushrooms!",
  "You found berries!",
  "You found nuts!",
  "You found roots!",
  "You found a fish!",
  "You found a honeycomb!",
  "You found insects!",
  "You found some meat!",
  "You found some mushrooms!",
  "You found a flute! Pick a bear to put to sleep for one turn!",
  "You found some water! Drink and add +1 to your next roll!",
  "You found some water! Drink and add +1 to your next roll!",
  "You found some water! Drink and add +1 to your next roll!",
  "You found some water! Drink and add +1 to your next roll!",
  "You found a PAL token!",
  "You found 10 DEC tokens!",
  "You found a HIVE token!",
  "You found a BEE token!"
  "You found 0.5 LEO token!"
  "You found a DEIA token!"
  "You found 10 SIM tokens!"
  "You found 10 NEOXAG tokens!"
  "You heard something in the trees! Move backwards 1 space!",
  "You heard something in the trees! Move backwards 1 space!",
  "You heard something in the trees! Move backwards 1 space!",
  "You heard something in the trees! Move backwards 1 space!"
];

var randomItem = myArray[Math.floor(Math.random()*myArray.length)];
alert(randomItem);
}
</script>
</center>
</body>
</html>
