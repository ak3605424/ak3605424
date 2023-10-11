<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Meta tags and stylesheets -->
    <!-- Link to external fonts and stylesheets -->
    <title>Tic Tac Toe</title>
</head>
<body>
    <!-- Your game elements will go here -->
</body>
</html>
/* Your provided CSS styles */
// Constants for player marks and winning combinations
const X_CLASS = 'x';
const O_CLASS = 'o';
const WINNING_COMBINATIONS = [
    [0, 1, 2],
    [3, 4, 5],
    // ... (other combinations)
];

// Initialize game variables
let currentPlayerMark = O_CLASS;
let isVsPlayer = false;
let oTurn = false;

let xWin = 0;
let oWin = 0;
let tie = 0;

let winningArray;
let currentClass;

// ... (Other constants and variables)

// Function to handle game mode selection
function setGameModeHandler() {
    // Handle game mode selection here
}

// ... (Other functions)

// Event listeners for game mode buttons
vsCpuBtn.addEventListener('click', setGameModeHandler);
vsPlayerBtn.addEventListener('click', setGameModeHandler);
// Function to handle player's turn
function playHandler(event) {
    // Handle player's turn and gameplay logic here
}

// Function to check for a win
function checkWin(currentClass) {
    // Check if there is a win based on the current class
    // Return true if there's a win, false otherwise
}

// Function to check for a draw
function isDraw() {
    // Check if the game is a draw
    // Return true if it's a draw, false otherwise
}

// ... (Other functions)

// Event listener for player's moves
cells.forEach(cell => {
    cell.addEventListener('click', playHandler, { once: true });
});

// ... (Other event listeners and function calls)
// Function to handle end of the game
function endGame(draw) {
    // Handle displaying game result and options here
}

// Function to handle restarting the game
function setNextRound() {
    // Handle restarting the game here
}

// ... (Other functions)

// Event listeners for modal buttons
nextRoundBtn.addEventListener('click', setNextRound);
quitBtn.addEventListener('click', () => {
    location.reload();
});
