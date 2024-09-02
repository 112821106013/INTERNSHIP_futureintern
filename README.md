# INTERNSHIP_futureintern
c/c++
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tic Tac Toe Game</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Tic Tac Toe</h1>
    <div class="game-board">
        <div class="cell" id="cell-0" onclick="makeMove(0)"></div>
        <div class="cell" id="cell-1" onclick="makeMove(1)"></div>
        <div class="cell" id="cell-2" onclick="makeMove(2)"></div>
        <div class="cell" id="cell-3" onclick="makeMove(3)"></div>
        <div class="cell" id="cell-4" onclick="makeMove(4)"></div>
        <div class="cell" id="cell-5" onclick="makeMove(5)"></div>
        <div class="cell" id="cell-6" onclick="makeMove(6)"></div>
        <div class="cell" id="cell-7" onclick="makeMove(7)"></div>
        <div class="cell" id="cell-8" onclick="makeMove(8)"></div>
    </div>
    <p id="game-status"></p>
    <button onclick="resetGame()">Restart Game</button>

    <script src="script.js"></script>
</body>
</html>
