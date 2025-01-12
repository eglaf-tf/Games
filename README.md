# Ping Pong Game

A classic Ping Pong game implemented in both C++ and JavaScript. Play the web version live at [https://eglaf-tf.github.io/Games/](https://eglaf-tf.github.io/Games/)!

## 🎮 Play Online

Visit [https://eglaf-tf.github.io/Games/](https://eglaf-tf.github.io/Games/) to play the web version directly in your browser.

### Controls
- **Up Arrow**: Move paddle up
- **Down Arrow**: Move paddle down

## 📦 Repository Contents

This repository contains two versions of the game:

1. **Web Version (JavaScript/HTML5)**
   - Located in `index.html`
   - Playable directly in browser
   - No installation required

2. **C++ Version**
   - Located in main source files
   - Built with Raylib
   - Requires compilation to run locally

## 🚀 Running the C++ Version Locally

### Prerequisites
- C++ compiler
- Raylib library

### Build Instructions

1. Clone the repository:
```bash
git clone https://github.com/eglaf-tf/Games.git
cd Games
```

2. Install Raylib:
```bash
# For Ubuntu/Debian
sudo apt-get install libasound2-dev mesa-common-dev libx11-dev libxrandr-dev libxi-dev xorg-dev libgl1-mesa-dev libglu1-mesa-dev

# For Windows
# Download and install raylib from https://www.raylib.com/
```

3. Compile the game:
```bash
g++ -o pong main.cpp -lraylib -lGL -lm -lpthread -ldl -lrt -lX11
```

4. Run the game:
```bash
./pong
```

## 🎯 Game Features

- Player vs CPU gameplay
- Score tracking
- Realistic ball physics
- Smooth paddle controls
- Responsive CPU opponent
- Clean, modern visual design

## 🛠️ Technical Details

### Web Version
- Built with HTML5 Canvas
- Pure JavaScript implementation
- Responsive design
- No external dependencies

### C++ Version
- Built with Raylib graphics library
- Object-oriented design
- Custom physics implementation
- High-performance native code

## 📝 Project Structure

```
Games/
├── index.html          # Web version of the game
├── main.cpp            # C++ source code
└── README.md          # This file
```

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License

This project is open source and available under the MIT License.

## 👨‍💻 Author

Created by [eglaf-tf](https://github.com/eglaf-tf)

## 🙏 Acknowledgments

- Raylib library for the C++ version
- HTML5 Canvas for web implementation
- Classic Pong game for inspiration
