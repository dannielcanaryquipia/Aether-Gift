# Aether Gift - Interactive 3D Particle Experience

A romantic, interactive web experience that transforms hand gestures into beautiful 3D particle formations using Three.js and MediaPipe hand tracking technology.

## 🌟 Features

### Hand Gesture Recognition
- **Open Hand** → Forms a glowing pink heart shape
- **Closed Fist** → Displays "D ❤️ K" text in golden particles
- **Peace Sign** → Shows "I ❤️ u" in pink particles
- **OK Sign** → Creates stunning galaxy formation with circular ring loops and bright white glowing central sphere

### Visual Effects
- **Ultra-optimized particle system** with adaptive performance (400-2500 particles)
- **Real-time physics simulation** with smooth transitions
- **Dynamic color changes** based on gesture type
- **Automatic particle dispersion** when no hand is detected
- **Cosmic background** with northern lights aurora effects
- **Floating cosmic ash** particles for galaxy atmosphere
- **Responsive design** optimized for all screen sizes

### Galaxy Formation Features
- **Circular ring loops** instead of spiral arms - 8 concentric rings with 3D volume
- **Realistic white light yellow star core** - 35% particles form bright glowing central sphere
- **Enhanced ring visibility** - Thicker rings with better separation from sphere
- **Dynamic galaxy rotation** - Faster clockwise rotation (0.03 speed)
- **Camera zoom** - Automatic zoom to 0.3x for detailed galaxy view
- **Volumetric particles** - Multiple layers for substantial ring structure

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

### Ultra-Optimized Particle System
- **Smart device classification** (mobile, tablet, desktop, high-end, low-end)
- **Dynamic particle scaling** based on device capabilities:
  - **Small Mobile**: 400 particles (0.04px size, 30 FPS)
  - **Large Mobile**: 600 particles (0.06px size, 30 FPS)
  - **Tablets**: 1,200 particles (0.07px size, 45 FPS)
  - **Low-end Desktop**: 1,500 particles (0.08px size, 45 FPS)
  - **High-DPI Displays**: 1,800 particles (0.09px size, 45 FPS)
  - **High-end Desktop**: 2,500 particles (0.10px size, 60 FPS)
  - **Standard Desktop**: 1,800 particles (0.09px size, 45 FPS)

### Enhanced Physics & Movement Optimization
- **Ultra-smooth particle physics** with optimized acceleration (0.035)
- **Advanced damping system** (0.78) for natural movement without bounce
- **Smooth dispersion transitions** with reduced speed (0.025) for graceful animations
- **Fluid position interpolation** (0.12 factor) between formation and dispersion states

### Frame Rate & Performance Management
- **Adaptive FPS targeting** based on device capabilities (30-60 FPS)
- **Intelligent FPS monitoring** with adaptive performance recovery
- **Aggressive performance scaling** only when severely poor (< 15 FPS)
- **Auto-recovery system** that gradually restores optimal FPS when performance improves

### Memory & Rendering Efficiency
- **Hardware-accelerated CSS transforms** for better mobile performance
- **Quality-based texture rendering** (32px/64px canvas based on device)
- **Optimized BufferGeometry** for memory-efficient particle management
- **Enhanced galaxy rotation speed** (0.03) for more dynamic visual effects

### Visual Quality Optimizations
- **Adaptive particle sizing** for each formation type:
  - Heart formations: 0.12px particles
  - Text formations: 0.13px particles  
  - Galaxy formations: 0.22px particles (enhanced for maximum glow)
  - Explosion/dispersion: 0.10px particles
- **Enhanced color blending** with cosmic glow effects
- **Optimized star textures** with quality-based rendering
- **Realistic star core colors** - White light yellow for authentic galaxy appearance

### Mobile-Specific Enhancements
- **Touch-optimized interactions** with momentum physics
- **Battery-conscious performance** modes
- **Responsive video container** with adaptive sizing
- **Performance-mode CSS classes** for reduced visual effects on small devices
- **CSS custom properties** for dynamic particle size optimization across all screen types

## 🎮 Controls

### Hand Gestures
1. **Show open palm** → Create heart shape
2. **Make fist** → Display "D ❤️ K" monthsary message
3. **Show peace sign** → Display "I ❤️ u" love message
4. **Make OK sign** → Create stunning galaxy formation with ring loops
5. **Remove hand** → Particles disperse naturally

### Video Feed Controls
- **Drag** to move the video preview anywhere on screen
- **Hide/Show toggle** button for camera privacy
- **Double-click** to center the video
- **Arrow keys** for precise positioning
- **Spacebar** to center quickly
- **High z-index** ensures video stays above 3D particles
- **Touch support** for mobile devices

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
Adjust `optimizedParticleCount` in JavaScript to balance performance vs. visual quality:
- **High-end Desktop**: 2,500 particles (maximum quality, 60 FPS)
- **Standard Desktop**: 1,800 particles (high quality, 45 FPS)  
- **High-DPI Displays**: 1,800 particles (optimized, 45 FPS)
- **Tablets**: 1,200 particles (medium quality, 45 FPS)
- **Low-end Desktop**: 1,500 particles (medium quality, 45 FPS)
- **Large Mobile**: 600 particles (medium quality, 30 FPS)
- **Small Mobile**: 400 particles (low quality, 30 FPS)

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

## 🆕 Recent Updates & Enhancements

### Galaxy Formation System (Latest)
- **Circular Ring Loops**: Transformed from spiral to 8 concentric circular rings
- **Realistic Star Core**: White light yellow glowing central sphere (35% particles)
- **Enhanced Visual Effects**: Thicker rings with better separation and 3D volume
- **Dynamic Rotation**: Faster clockwise rotation (0.03 speed) for engaging visuals
- **Camera Zoom**: Automatic 0.3x zoom for detailed galaxy viewing

### Ultra-Performance Optimization
- **Drastically Reduced Particles**: 33-40% reduction across all device types
- **Adaptive FPS**: 30-60 FPS targeting based on device capabilities
- **CSS Custom Properties**: Dynamic particle sizing for all screen types
- **Enhanced Mobile Performance**: Ultra-low particle counts for smooth mobile experience

### Enhanced User Experience
- **Concise Text Messages**: "D ❤️ K" and "I ❤️ u" for cleaner display
- **Heart Emoji Integration**: Native ❤️ emoji instead of HTML entities
- **Improved Gesture Recognition**: More flexible OK sign detection
- **Better Visual Hierarchy**: More prominent central sphere with enhanced ring visibility

### Technical Improvements
- **Optimized Physics**: Enhanced particle movement and damping systems
- **Memory Efficiency**: Improved BufferGeometry and texture rendering
- **Cross-Device Compatibility**: Comprehensive media query optimizations
- **Performance Monitoring**: Intelligent FPS tracking and recovery systems

---

*Created with ❤️ using modern web technologies*
