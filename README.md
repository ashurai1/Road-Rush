# 🚗 Road Rush

An exciting 3D Unity-based racing game where you navigate through challenging roads, avoid obstacles, and escape from pursuing police cars in this high-octane racing experience!

![Game Preview](https://img.shields.io/badge/Unity-Game-blue?style=for-the-badge&logo=unity)
![Version](https://img.shields.io/badge/Version-2.0-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

## 🎮 About The Game

Road Rush is an adrenaline-pumping racing game built with Unity WebGL technology. Drive through dynamic environments, dodge obstacles, and outrun the police in this thrilling endless runner experience.

### ✨ Features

- 🎯 **Smooth 3D Graphics** - Powered by Unity WebGL
- 🚓 **Police Chase Action** - Escape from pursuing vehicles
- 📱 **Mobile Responsive** - Play on desktop or mobile devices
- 🎨 **Custom Loading Screen** - Stylish loading animation with progress bar
- 🔥 **Real-time Analytics** - Firebase integration for tracking
- 🎵 **Immersive Experience** - Engaging gameplay mechanics

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, or Edge)
- Internet connection for CDN resources

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ashurai1/road-rush.git
   cd road-rush
   ```

2. **Open the game**
   - Navigate to the `dist` folder
   - Open `index.html` in your web browser
   
   Or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```

3. **Play!**
   - Visit `http://localhost:8000` in your browser
   - Wait for the game to load
   - Use keyboard controls to play

## 🎮 How to Play

- **Arrow Keys / WASD** - Control your vehicle
- **Space** - Brake/Handbrake
- **Escape** - Pause menu

## 🛠️ Technology Stack

- **Game Engine**: Unity WebGL
- **Frontend**: HTML5, CSS3, JavaScript
- **Backend Services**: Firebase (Authentication, Analytics, Firestore)
- **CDN**: jsDelivr for asset delivery
- **Debugging**: Eruda (mobile debugging console)

## 📁 Project Structure

```
road-rush/
├── dist/               # Production build
│   └── index.html     # Main game file
├── src/               # Source files
│   └── index.html     # Development version
├── TemplateData/      # Unity WebGL template assets
│   ├── loader.js      # Unity loader script
│   ├── style.css      # Game styling
│   ├── data.unityweb  # Game data
│   ├── framework.js.unityweb
│   └── wasm.unityweb  # WebAssembly binary
├── favicon.ico        # Game favicon
└── README.md          # This file
```

## 🔧 Configuration

The game uses Firebase for analytics and authentication. Configuration is included in the HTML files:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "escape-road-gm1.firebaseapp.com",
  projectId: "escape-road-gm1",
  // ... other config
};
```

## 🌐 Deployment

### GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select the `main` branch and `/dist` folder
4. Your game will be live at `https://ashurai1.github.io/road-rush/`

### Other Platforms

- **Netlify**: Drag and drop the `dist` folder
- **Vercel**: Connect your GitHub repository
- **Firebase Hosting**: Use Firebase CLI to deploy

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Ashwani Rai**

- GitHub: [@ashurai1](https://github.com/ashurai1)
- Email: raishwani151104@gmail.com

## 🙏 Acknowledgments

- Unity Technologies for the WebGL platform
- Firebase for backend services
- The gaming community for inspiration

## 📊 Version History

- **v2.0** (Current) - Enhanced gameplay and performance improvements
- **v1.0** - Initial release

---

<div align="center">
  
**© 2025 Made by Ashwani Rai**

⭐ Star this repository if you enjoyed the game!

</div>
