<!DOCTYPE html>
<html>
<head>
	<title>Random Number Generator</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
	<h1>Random Number Generator</h1>
	<p>Click the button to generate a random number between 1 and 10:</p>
	<button onclick="generateNumber()">Generate</button>
	<p id="result"></p>

	<script>
		function generateNumber() {
			var number = Math.floor(Math.random() * 10) + 1;
			document.getElementById("result").innerHTML = "Your random number is: " + number;
		}
	</script>
</body>
</html>
