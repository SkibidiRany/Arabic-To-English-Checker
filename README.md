# Arabic-English Vocabulary Quiz

A fun, interactive website for practicing English vocabulary using Arabic meanings!  
Perfect for students and children, this quiz presents an Arabic word and asks the user to type its English equivalent. The site features keyboard-only navigation, keeps score, and tracks your answer history—highlighting mistakes for easier review.

---

## Features

- **Easy Word Management**: Add or edit vocabulary in simple CSV files—no coding required.
- **Keyboard-Friendly**: Type your answer and press Enter to check; press Enter again for the next word—no mouse needed!
- **Scoreboard**: Tracks how many words you got right, wrong, and your total attempts.
- **Progress Bar**: Visual feedback on your progress through the word list.
- **Encouragement**: Random positive messages when you get a correct answer.
- **History Table**: See your recent attempts, including your answer, the correct answer, and which words you missed (highlighted in red).

---

## Usage

1. **Add your vocabulary**
   - Edit or add CSV files like `words.csv`, `words2.csv`, etc.
   - Each row: `english,arabic`
   - Example:
     ```
     english,arabic
     sleep,نوم
     speak,يتكلم
     ```

2. **Run the Website**
   - Place `index.html` and your CSV files in the same folder.
   - Open `index.html` in your browser.
   - The site will load `words.csv` by default.  
     _(To use a different file, modify the fetch path in the HTML's JavaScript section.)_

3. **How to Play**
   - The site shows an Arabic word.
   - Type the English meaning and press Enter.
   - If correct, you get a positive message; if not, the correct answer is shown.
   - Press Enter again for the next question.
   - See your answer history below the quiz.

---

## Customization

- **Add More Words**:  
  Just add more lines to your CSV file. You can use multiple CSVs for different units or topics.
- **Change Data File**:  
  Edit the `fetch('words.csv')` line in `index.html` to load a different file.
- **Merge Word Lists**:  
  Combine CSV files into one for a larger quiz.

---

## Example File Structure

```
project-folder/
├── index.html
├── words.csv
├── words2.csv
├── README.md
```

---

## Credits

- Design and code by [SkibidiRany](https://github.com/SkibidiRany) and [GitHub Copilot].
- Made for learning, fun, and practicing English vocabulary!

---

## License

MIT License. Free to use and modify.