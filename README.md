# OIBSIP_Calculator
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet"href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Anton&family=Bebas+Neue&family=Dancing+Script&family=Dongle&family=Libre+Baskerville:wght@700&family=Redressed&family=Source+Serif+4:ital@1&display=swap" rel="stylesheet">
    <title>Calculator</title>
</head>
<body>
        <div id="calculator">
            <div id="result">
                <div id="history">
                    <p id="history-value"></p>
                </div>
                <div id="output">
                    <p id="output-value"></p>
                </div>
            </div>

            <div id="keyword">
                <button class="operator" id="clear">C</button>
					<button class="operator" id="backspace">CE</button>
					<button class="operator" id="%">%</button>
					<button class="operator" id="/">&#247;</button>
					<button class="number" id="7">7</button>
					<button class="number" id="8">8</button>
					<button class="number" id="9">9</button>
					<button class="operator" id="*">&times;</button>
					<button class="number" id="4">4</button>
					<button class="number" id="5">5</button>
					<button class="number" id="6">6</button>
					<button class="operator" id="-">-</button>
					<button class="number" id="1">1</button>
					<button class="number" id="2">2</button>
					<button class="number" id="3">3</button>
					<button class="operator" id="+">+</button>
					<button class="empty" id="empty"></button>
					<button class="number" id="0">0</button>
					<button class="empty" id="empty"></button>
					<button class="operator" id="=">=</button>
            </div>
        </div>

    <script src="index.js"></script>
</body>
</html>

<! This will implement the calculator.//-->
