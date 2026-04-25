# 🐰 Rabbit World
 
An interactive educational web application about rabbits with bilingual support (English & Bengali), featuring quizzes, videos, text-to-speech functionality, and a beautiful animated interface.
 
![Rabbit World Preview](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
 
## ✨ Features
 
### 🌍 Bilingual Support
- **English** and **বাংলা (Bengali)** language options
- Seamless language switching with full content translation
### 🎨 Modern UI/UX
- Beautiful gradient backgrounds with smooth animations
- Floating rabbit SVG animations
- Dark/Light theme toggle
- Responsive design for all devices
- Smooth page transitions and effects
### 🔐 Login System
- Name entry page
- Password-protected access (Hint: 3 letters starting with 'w')
- Smart password reveal after 4 failed attempts
### 📚 Educational Content
Interactive information cards covering:
- 🥕 **Diet & Behavior** - What rabbits eat and their "binky" behavior
- 🧬 **Biology** - Hearing, vision, and unique traits
- 🍼 **Breeding** - Rabbit reproduction facts
- 🏠 **Habitat** - Where rabbits live
- 🐇 **Rabbit vs Hare** - Key differences
### 🔊 Text-to-Speech
- Read aloud functionality for all educational content
- Optimized voice selection (male voices for English)
- Language-appropriate speech synthesis
### 🎬 Video Resources
Three curated YouTube search links:
1. What Rabbits Eat
2. Rabbit Farming
3. Feeding Baby Rabbits
### ❓ Interactive Quiz
- 5 medium-difficulty questions
- Real-time scoring
- Share results on social media (Twitter, Facebook, WhatsApp)
- Copy score to clipboard functionality
### ⌨️ Keyboard Shortcuts
- **Enter** - Login / Continue
- **R** - Toggle text-to-speech
- **V** - Navigate to Videos
- **Q** - Start Quiz
- **H** - Return to Home
- **L** - Logout
- **D** - Toggle Dark Mode
## 🚀 Getting Started
 
### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required - pure HTML/CSS/JavaScript!
### Installation
 
1. Clone the repository:
```bash
git clone https://github.com/tamimashraf132-blip/-Rabbit-World.git
```
 
2. Navigate to the project directory:
```bash
cd -Rabbit-World
```
 
3. Open `index.html` in your web browser:
```bash
# On macOS
open index.html
 
# On Linux
xdg-open index.html
 
# On Windows
start index.html
```
 
Or simply drag and drop the `index.html` file into your browser.
 
### Quick Start
1. Enter your name on the welcome page
2. Enter the password: **web**
3. Explore rabbit facts, watch videos, or take the quiz!
## 📁 Project Structure
 
```
-Rabbit-World/
│
├── index.html          # Main HTML file (complete single-file application)
├── rabbit.jpg          # Rabbit image (optional - uses fallback if missing)
└── README.md          # This file
```
 
## 🎯 Quiz Answers
 
The quiz includes questions about:
- Rabbit behavior (binkying)
- Dietary requirements
- Group terminology
- Vision capabilities
- Differences between rabbits and hares
*Answers are validated client-side for instant feedback!*
 
## 🌐 Browser Compatibility
 
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)
## 🎨 Customization
 
### Changing Colors
Edit the CSS variables in the `:root` section:
```css
:root {
    --cream: #fff8f0;
    --peach: #ffb347;
    --rose: #ff6b8a;
    --lavender: #c084fc;
    /* etc. */
}
```
 
### Changing Password
Update the `PASSWORD` constant in the JavaScript:
```javascript
const PASSWORD = "web"; // Change this to your desired password
```
 
### Adding More Languages
Extend the `T` translation object in the JavaScript section.
 
## 📱 Mobile Support
 
Fully responsive design with:
- Touch-friendly buttons
- Optimized layouts for small screens
- Mobile-specific adjustments (cards, grids, etc.)
## 🤝 Contributing
 
Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve translations
## 📄 License
 
This project is open source and available under the [MIT License](LICENSE).
 
## 👨‍💻 Author
 
**tamimashraf132-blip**
- GitHub: [@tamimashraf132-blip](https://github.com/tamimashraf132-blip)
## 🙏 Acknowledgments
 
- Rabbit SVG illustrations created with pure SVG
- Fonts: Google Fonts (Playfair Display, Nunito)
- Icons: Emoji (cross-platform compatible)
- Educational content about rabbits from various wildlife resources
## 📞 Support
 
If you encounter any issues or have questions:
- Open an issue on GitHub
- Contact via GitHub profile
## 🌟 Show Your Support
 
If you like this project, please give it a ⭐️ on GitHub!
 
---
 
**Made with 💖 and 🐰 by tamimashraf132-blip**
