# Aether Gift - Interactive 3D Particle Experience

A romantic, interactive web experience that transforms hand gestures into beautiful 3D particle formations using Three.js and MediaPipe hand tracking technology.

## 🌟 Features

### Hand Gesture Recognition
- **Open Hand** → Forms a glowing pink heart shape
- **Closed Fist** → Displays "Happy Monthsary" text in golden particles
- **Peace Sign** → Shows "I love you Kaye" in pink particles

### Visual Effects
- **12,000+ animated particles** with customizable glow effects
- **Real-time physics simulation** with smooth transitions
- **Dynamic color changes** based on gesture type
- **Automatic particle dispersion** when no hand is detected
- **Responsive design** optimized for all screen sizes

### Interactive Elements
- **Draggable video feed** with momentum physics
- **Keyboard controls** for precise positioning
- **Double-click to center** functionality
- **Position persistence** using localStorage
- **Touch support** for mobile devices

## 🚀 Technologies Used

- **Three.js** - 3D graphics and particle system
- **MediaPipe Hands** - Real-time hand tracking
- **HTML5 Canvas** - Text rendering and particle textures
- **CSS3** - Responsive design and animations
- **JavaScript ES6+** - Modern web development

## 📱 Performance Optimizations

- **Adaptive particle count** based on device capabilities
- **FPS limiting** for smooth performance on mobile
- **Responsive scaling** for different screen sizes
- **Hardware acceleration** with CSS transforms
- **Memory-efficient particle system** using BufferGeometry

## 🎮 Controls

### Hand Gestures
1. **Show open palm** → Create heart shape
2. **Make fist** → Display monthsary message
3. **Show peace sign** → Display love message
4. **Remove hand** → Particles disperse naturally

### Video Feed Controls
- **Drag** to move the video preview
- **Double-click** to center the video
- **Arrow keys** for precise positioning
- **Spacebar** to center quickly

## 🛠️ Setup & Installation

1. **Clone or download** the project files
2. **Open `index.html`** in a modern web browser
3. **Allow camera access** when prompted
4. **Start gesturing** to interact with the particles!

### Requirements
- Modern browser with WebGL support
- Webcam or camera device
- HTTPS connection (required for camera access)

## 🎨 Customization

### Particle Count
Adjust `optimizedParticleCount` in the JavaScript to balance performance vs. visual quality:
- Desktop: 12,000 particles
- Mobile: 6,000 particles
- Low-end devices: 8,000 particles

### Colors & Text
Modify the gesture functions to customize:
- Particle colors for each gesture
- Text messages and fonts
- Animation speeds and transitions

## 📄 Browser Compatibility

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers with WebRTC support

## 🎯 Use Cases

- **Romantic gestures** and special occasions
- **Interactive presentations** and demonstrations
- **Educational purposes** for web technologies
- **Creative coding** and digital art projects

## 🐛 Troubleshooting

### Camera Not Working
- Ensure HTTPS connection
- Check browser camera permissions
- Try refreshing the page

### Performance Issues
- Close other browser tabs
- Reduce particle count in code
- Check hardware acceleration settings

### Hand Detection Problems
- Ensure good lighting
- Keep hand within camera view
- Make clear, distinct gestures

## 💡 Inspiration

This project combines romantic expression with cutting-edge web technologies, creating an immersive experience that responds to human interaction. Perfect for anniversaries, monthsaries, or any special moment worth celebrating.

---

*Created with ❤️ using modern web technologies*
