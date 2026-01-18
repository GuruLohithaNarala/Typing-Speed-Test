# ⌨️ Typing Speed Test

A beautiful, interactive typing speed test web application with multiple difficulty levels. Test your typing speed, accuracy, and track your progress!


## 🌟 Features

- **🎯 Three Difficulty Levels**
  - 🟢 Easy: 30 seconds with simple sentences
  - 🟡 Medium: 60 seconds with moderate complexity
  - 🔴 Hard: 90 seconds with advanced vocabulary

- **📊 Real-time Statistics**
  - Words Per Minute (WPM) tracking
  - Accuracy percentage
  - Correct vs Wrong word count
  - Live character-by-character feedback

- **🎨 Beautiful UI**
  - Modern gradient design
  - Color-coded text feedback (green for correct, red for incorrect)
  - Responsive layout for all devices
  - Smooth animations and transitions

- **⏱️ Dynamic Timer**
  - Countdown timer based on difficulty
  - Automatic test completion
  - Start typing to begin

## 🚀 Demo

https://github.com/GuruLohithaNarala/Typing-Speed-Test.git

## 📸 Screenshots
<img width="1115" height="893" alt="image" src="https://github.com/user-attachments/assets/2622bfff-3eb5-4e07-a8f4-dd2215a4f683" />



## 🛠️ Technologies Used

- **HTML5** - Structure
- **CSS3** - Styling
- **JavaScript** - Functionality
- **Tailwind CSS** - UI Framework (via CDN)

## 📦 Installation

1. Clone the repository:
```bash
[git clone https://github.com/yourusername/typing-speed-test.git](https://github.com/GuruLohithaNarala/Typing-Speed-Test.git)
```

2. Navigate to the project directory:
```bash
cd typing-speed-test
```

3. Open `index.html` in your browser:
```bash
# On Windows
start index.html

# On Mac
open index.html

# On Linux
xdg-open index.html
```

That's it! No build process or dependencies required.

## 🎮 How to Use

1. **Select Difficulty**: Choose Easy, Medium, or Hard level
2. **Start Typing**: Click on the text area and start typing the displayed text
3. **Watch Your Stats**: Monitor your WPM and accuracy in real-time
4. **Complete the Test**: Finish before time runs out or type the entire text
5. **View Results**: See your final score with detailed statistics
6. **Try Again**: Click "New Test" to start over

## 📊 Scoring System

- **WPM (Words Per Minute)**: Calculated based on words typed and time elapsed
- **Accuracy**: Percentage of correctly typed characters
- **Correct Words**: Number of words typed exactly as shown
- **Wrong Words**: Number of words with errors

## 🌐 Deploy to GitHub Pages

1. Push your code to GitHub:
```bash
git add .
git commit -m "Initial commit"
git push origin main
```

2. Go to your repository settings
3. Navigate to **Pages** section
4. Select **main** branch as source
5. Click **Save**
6. Your site will be live at [`https://yourusername.github.io/typing-speed-test/`](https://github.com/GuruLohithaNarala/Typing-Speed-Test.git)

## 🎨 Customization

### Change Difficulty Settings
Edit the `levelSettings` object in the JavaScript section:
```javascript
const levelSettings = {
    easy: { time: 30, color: 'green', emoji: '🟢', name: 'Easy' },
    medium: { time: 60, color: 'yellow', emoji: '🟡', name: 'Medium' },
    hard: { time: 90, color: 'red', emoji: '🔴', name: 'Hard' }
};
```

### Add More Texts
Add new sentences to the `textsByLevel` object:
```javascript
const textsByLevel = {
    easy: [
        "Your new sentence here.",
        // Add more...
    ],
    // ...
};
```

### Change Colors
Modify Tailwind CSS classes in the HTML or update the custom CSS in the `<style>` section.

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

## 📝 Future Enhancements

- [ ] Add leaderboard functionality
- [ ] Save personal best scores
- [ ] Add more difficulty levels
- [ ] Dark mode toggle
- [ ] Multiplayer mode
- [ ] Custom text input
- [ ] Detailed statistics dashboard
- [ ] Export results as PDF
- [ ] Sound effects
- [ ] Keyboard heatmap

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Your Name**
- GitHub: https://github.com/GuruLohithaNarala
- LinkedIn: https://www.linkedin.com/in/gurulohitha-narala-2b84602a2
- Email: naralagurulohitha@gmail.com



