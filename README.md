<!DOCTYPE html>
<html>
<head>
	<title>Calculadora</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
    <h1>
        Calculadora
    </h1>
	<div class="calculator">
		<div class="display">
			<input type="text" id="result" disabled>
		</div>
		<div class="buttons">
			<button onclick="clearResult()">C</button>
			<button onclick="backspace()">←</button>
			<button onclick="appendToResult('/')">÷</button>
			<button onclick="appendToResult('*')">x</button>
			<button onclick="appendToResult('7')">7</button>
			<button onclick="appendToResult('8')">8</button>
			<button onclick="appendToResult('9')">9</button>
			<button onclick="appendToResult('-')">-</button>
			<button onclick="appendToResult('4')">4</button>
			<button onclick="appendToResult('5')">5</button>
			<button onclick="appendToResult('6')">6</button>
			<button onclick="appendToResult('+')">+</button>
			<button onclick="appendToResult('1')">1</button>
			<button onclick="appendToResult('2')">2</button>
			<button onclick="appendToResult('3')">3</button>
			<button onclick="calculate()">=</button>
			<button onclick="appendToResult('0')">0</button>
			<button onclick="appendToResult('.')">.</button>
		</div>
	</div>

	<script src="script.js"></script>
</body>
</html>
