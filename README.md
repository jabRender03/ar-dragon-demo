# AR Dragon Demo 🐉

An interactive Augmented Reality experience featuring a 3D dragon model with gestures, animations, and particle effects.

## Features

- **Professional 3D Model**: High-quality dragon from Khronos Group glTF samples
- **Interactive Animations**: Tap to make the dragon jump with particle effects
- **Gesture Controls**: Pinch to scale, rotate with two fingers
- **Real-time Shadows**: Dynamic shadow casting for realistic grounding
- **Audio Feedback**: Sound effects on interaction
- **Mobile Optimized**: Works on Android phones with camera access

## How to Use

1. **Open the demo**: Visit the GitHub Pages link (see below)
2. **Allow camera access** when prompted
3. **Print the Hiro marker**: [Download here](https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/hiro.png)
4. **Point your camera** at the marker
5. **Interact**: Tap the dragon or use the JUMP button

## Technologies

- [A-Frame](https://aframe.io/) - WebVR framework
- [AR.js](https://ar-js-org.github.io/AR.js-Docs/) - Augmented Reality for the web
- [glTF](https://www.khronos.org/gltf/) - 3D model format

## Live Demo

🔗 **[Launch AR Demo](https://YOUR-USERNAME.github.io/ar-dragon-demo/ar-demo.html)**

## Local Development

```bash
# Start local server
python -m http.server 8000

# Visit in browser
http://localhost:8000/ar-demo.html
```

**Note**: HTTPS is required for camera access on mobile devices.

## Credits

- Dragon Model: [Khronos Group glTF Sample Assets](https://github.com/KhronosGroup/glTF-Sample-Assets)
- Built with assistance from Google Deepmind's Antigravity AI
