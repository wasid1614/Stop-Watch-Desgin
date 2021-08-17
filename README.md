# Stop-Watch-Desgin
Html,css,jss  using WEB DESIGN


<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Stopwatch | @IT.Man Wasid Mohammad</title>
	<link href="https://fonts.googleapis.com/css2?family=Open+Sans&display=swap" rel="stylesheet">
	<link rel="stylesheet" href="./style.css">
</head>

<body>
	<div class="container">
		<h1>Stopwatch</h1>
		<p class="time">00 : 00.0</p>
		<div class="buttons">
			<button id="start" onclick="this.disabled= true;calltimer()">Start</button>
			<button id="stop" onclick="stoptimer()">Stop</button>
			<button id="clear" onclick="cleartimer()">Clear</button>
		</div>
	</div>


	<script src="./script.js"></script>
</body>

</html>
