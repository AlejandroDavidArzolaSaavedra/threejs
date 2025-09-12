# Getting Started with Three.js and WebGL Examples

This repository contains various examples demonstrating computer graphics programming using Three.js and pure WebGL.

## Project Structure

```
threejs/
├── index.html                     # Main navigation page
├── README.md                      # Project documentation
├── examples/
│   ├── webgl-basic/              # Pure WebGL examples
│   │   ├── car-game.html         # 2D car racing game
│   │   └── spinning-triangle.html # Basic WebGL triangle
│   ├── threejs-examples/         # Three.js examples
│   │   ├── rotating-cube.html    # Basic 3D cube (requires CDN)
│   │   └── geometric-shapes.html # Various 3D shapes (requires CDN)
│   └── shaders/                  # Custom shader examples
│       └── custom-shaders.html   # Advanced shader effects (requires CDN)
└── docs/
    └── GETTING_STARTED.md        # This file
```

## Running the Examples

1. **Simple HTTP Server** (Recommended):
   ```bash
   python3 -m http.server 8080
   # OR
   python -m SimpleHTTPServer 8080
   # OR
   npx serve .
   ```

2. **Open in Browser**:
   - Navigate to `http://localhost:8080`
   - Click on any example to view it

## Example Categories

### 🎮 WebGL Basic Examples
These examples use pure WebGL without external libraries, perfect for learning graphics programming fundamentals.

- **Car Racing Game**: A complete 2D game with custom shaders and animations
- **Spinning Triangle**: Basic WebGL setup with vertex/fragment shaders

### 📦 Three.js Examples  
These examples use the Three.js library for easier 3D graphics programming.

- **Rotating Cube**: Basic 3D rendering with lighting and controls
- **Geometric Shapes**: Interactive gallery of 3D primitives

### ✨ Custom Shaders
Advanced examples demonstrating custom GLSL shader programming.

- **Animated Effects**: Multiple shader modes with real-time uniforms

## Learning Path

1. **Start with Pure WebGL**: Begin with `spinning-triangle.html` to understand WebGL fundamentals
2. **Explore Game Development**: Try `car-game.html` for more complex WebGL applications  
3. **Learn Three.js**: Move to Three.js examples for higher-level 3D graphics
4. **Advanced Shaders**: Experiment with custom shader programming

## Browser Compatibility

- **Modern Browsers**: Chrome, Firefox, Safari, Edge (latest versions)
- **WebGL Support**: Required for all examples
- **Hardware Acceleration**: Recommended for better performance

## Troubleshooting

### WebGL Not Working
- Check if WebGL is enabled: Visit `chrome://flags` and enable WebGL
- Update graphics drivers
- Try different browser

### Three.js Examples Not Loading
- Examples using CDN may not work in offline environments
- Check browser console for network errors
- Consider downloading Three.js locally for offline use

### Performance Issues
- Enable hardware acceleration in browser settings
- Close other browser tabs/applications
- Try examples on a device with dedicated graphics

## Resources

- [WebGL Fundamentals](https://webglfundamentals.org/)
- [Three.js Documentation](https://threejs.org/docs/)
- [OpenGL ES Shading Language](https://www.khronos.org/opengl/wiki/Core_Language_(GLSL))
- [Computer Graphics Course Materials](https://www.ulpgc.es/)

## Contributing

Feel free to add more examples or improve existing ones! Follow these guidelines:

1. Keep examples self-contained when possible
2. Add clear documentation and comments
3. Test across different browsers
4. Update the main index.html navigation
5. Include example in this getting started guide

## Author

**Alejandro David Arzola Saavedra**  
Universidad de Las Palmas de Gran Canaria  
Computer Graphics Course 2024/25