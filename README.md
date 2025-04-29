# Wordle Assistant Script

This JavaScript snippet helps you solve Wordle games on [wordlegame.org](https://wordlegame.org) by listing all candidate words matching the current game state.

## Requirements

- A modern web browser (Chrome, Firefox, Edge, etc.)
- Access to the browser's Developer Console (`F12` or right-click → Inspect)

## Usage

1. Open the file `main.js` in your code editor and copy its entire contents.  
2. In your browser, navigate to **[wordlegame.org](https://wordlegame.org)** and start a Wordle game.  
3. Open the Developer Console:  
   - Press **F12**, or  
   - Press **Ctrl+Shift+I** / **Cmd+Option+I** (depending on your system).  
4. Paste the copied script into the console and press **Enter**.  
5. The script will analyze your previous guesses and display:  
   - A list of all possible valid words based on green, yellow, and gray feedback.  
   - Additional statistics like letter frequency and candidate counts.  
6. Choose one of the suggested words and submit it in the game.  
7. After each guess, repeat steps 3–6 to refine the candidate list.  

> **Tip:** Run the script after each guess. With four well-chosen words, the solution set usually narrows down to just 1–4 possibilities.

## Notes

- If no guesses have been entered yet, the script returns `undefined`.  
- Accuracy improves as more feedback (green, yellow, gray letters) is provided.  
- This script does **not** auto-submit words; you must manually input the suggested guesses.

## Contributing

Contributions and suggestions are highly encouraged!

1. Fork the repository.  
2. Create a feature branch:  
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Open a Pull Request to propose your changes.

Please ensure that all tests are updated and passing when submitting new features.

*Enjoy near-certain Wordle victories—provided you choose your words wisely!*
      
