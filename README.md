# 🏎️ Lamborghini 3D Viewer

A high-performance, interactive 3D car model viewer built with **Three.js**. This project allows users to explore a detailed Lamborghini model with real-time controls and dynamic animations.

## 🌟 Features

- **High-Fidelity 3D Rendering**: Powered by Three.js and GLTFLoader for realistic car models.
- **Interactive Orbit Controls**: Rotate, zoom, and pan around the vehicle using your mouse.
- **Dynamic Input System**: 
  - Use **Arrow Keys** to rotate the car body.
  - Automatic **Wheel Spin Animation** for a life-like feel.
- **Responsive Design**: The viewport automatically adjusts to any screen size.
- **Pure Web Implementation**: Uses Skypack CDN for seamless dependency management without a heavy build step.

## 🛠️ Tech Stack

- **Core**: [Three.js](https://threejs.org/)
- **Loader**: GLTFLoader
- **Controls**: OrbitControls
- **Environment**: HTML5, CSS3, JavaScript (ES6+)

## 🚀 Getting Started

### Prerequisites

You only need a modern web browser to run this project. For a local development environment, a simple HTTP server is recommended.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/PIYAL-DATTA/3D-Car-Model-Three.js-.git
   ```
2. Navigate to the project directory:
   ```bash
   cd 3D-Car-Model-Three.js-
   ```
3. Open `src/index.html` in your browser, or use a tool like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code.

## 🎮 Controls

| Action | Control |
| :--- | :--- |
| **Rotate Camera** | Left Click + Drag |
| **Zoom** | Scroll Wheel |
| **Pan Camera** | Right Click + Drag |
| **Rotate Car (X-Axis)** | Up / Down Arrow Keys |
| **Rotate Car (Z-Axis)** | Left / Right Arrow Keys |

## 📁 Project Structure

```text
acar/
├── src/
│   ├── index.html     # Main entry point
│   ├── style.css      # Custom styling
│   ├── js/
│   │   └── scripts.js # Three.js logic & animation
│   └── car/           # 3D Model assets (.gltf)
├── package.json       # Dependency configuration
└── README.md          # Project documentation
```

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

Developed with ❤️ by [Piyal Datta](https://github.com/PIYAL-DATTA)

