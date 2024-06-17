# JavaScript Football Game Simulation

This JavaScript code simulates a football game between two teams, Bayern Munich and Borrussia Dortmund. The code includes tasks to create player arrays, substitute players, calculate odds, and print goals.

## Features

- **Player Arrays**: The code creates an array for each team with the first player as the goalkeeper and the rest as field players.
- **All Players Array**: An array containing all players from both teams is created.
- **Substitute Players**: During the game, Bayern Munich uses 3 substitute players. The code creates a new array containing all the original team1 players plus 'Thiago', 'Coutinho' and 'Perisic'.
- **Game Odds**: Based on the game.odds object, a variable for each odd is created.
- **Print Goals Function**: A function that receives an arbitrary number of player names (not an array) and prints each of them to the console, along with the number of goals that were scored in total (number of player names passed in).
- **Winning Team Prediction**: The code predicts the team more likely to win based on the lower odd, without using an if/else statement or the ternary operator.

## Test Data

For the 'printGoals' function, the test data includes players 'Davies', 'Muller', 'Lewandowski' and 'Kimmich'. The function is then called again with players from game.scored.

## Usage

To use this code, simply include it in your JavaScript project and call the appropriate functions with the necessary parameters.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

MIT License
