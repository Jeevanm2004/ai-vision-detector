# 🔍 AI Vision Detector

[![GitHub Pages](https://img.shields.io/badge/demo-live-brightgreen)](https://jeevanm2004.github.io/ai-vision-detector)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-FF6F00?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/js)

A powerful, real-time object detection web application built with **TensorFlow.js** and the **COCO-SSD model**. Detect and identify 80 different types of objects instantly through your webcam or by uploading images—all running directly in your browser with zero installation required.

## ✨ Features

### 🎥 **Real-time Detection**
Live object detection using your device's webcam with smooth performance

### 📸 **Image Upload & Analysis**
Upload and analyze your own photos for object detection

### 🎯 **80+ Object Classes**
Comprehensive detection including:
- **People & Body Parts**: person, hand, face
- **Animals**: dog, cat, bird, horse, cow, sheep
- **Vehicles**: car, truck, bus, motorcycle, bicycle, airplane
- **Food Items**: apple, banana, sandwich, pizza, cake
- **Electronics**: laptop, phone, TV, keyboard, mouse
- **Furniture**: chair, table, sofa, bed
- **Sports Equipment**: frisbee, skis, snowboard, sports ball
- **Kitchen Items**: bottle, wine glass, cup, fork, knife, spoon, bowl

### 🌐 **Browser-Based**
No installation, downloads, or server setup required—runs entirely in your web browser

### ⚡ **High Performance**
- Powered by Google's pre-trained COCO-SSD model
- Optimized for 30-60 FPS on modern devices
- Lightweight and efficient processing

### 📱 **Cross-Platform**
Works seamlessly on desktop, tablet, and mobile devices

## 🚀 Quick Start

### Option 1: Try the Live Demo
Visit the [**Live Demo**](https://jeevanm2004.github.io/ai-vision-detector) to start detecting objects immediately!

### Option 2: Run Locally
```bash
# Clone the repository
git clone https://github.com/Jeevanm2004/ai-vision-detector.git

# Navigate to project directory
cd ai-vision-detector

# Open in your browser
# Simply open index.html in any modern web browser
```

## 📋 Requirements

- **Browser**: Modern web browser (Chrome 60+, Firefox 55+, Safari 11+, Edge 79+)
- **Camera Access**: Required for real-time webcam detection
- **JavaScript**: Must be enabled in browser
- **Internet**: Required to load TensorFlow.js models
- **RAM**: Minimum 2GB recommended for smooth performance

## 📱 Browser Compatibility

| Browser | Version | Real-time Detection | Image Upload | Performance |
|---------|---------|--------------------|--------------| ------------|
| Chrome | 60+ | ✅ Excellent | ✅ Full | 🚀 Best |
| Firefox | 55+ | ✅ Excellent | ✅ Full | ⚡ Great |
| Safari | 11+ | ✅ Good | ✅ Full | ⚡ Great |
| Edge | 79+ | ✅ Excellent | ✅ Full | ⚡ Great |
| Mobile Safari | 11+ | ✅ Good | ✅ Full | 📱 Variable |
| Chrome Mobile | 60+ | ✅ Good | ✅ Full | 📱 Variable |

## ⚠️ Known Limitations

- **Lighting Sensitivity**: Detection accuracy decreases in poor lighting conditions
- **Object Overlap**: May struggle with heavily overlapping objects in crowded scenes  
- **Mobile Performance**: Frame rate varies based on device processing power
- **Model Loading**: Initial load time of 5-10 seconds for downloading the AI model
- **Camera Permissions**: Requires explicit camera access permission from user

## 🚀 Performance Optimization Tips

- **🔆 Lighting**: Ensure good, even lighting for optimal detection accuracy
- **📏 Distance**: Keep objects at moderate distance from camera (1-3 meters ideal)
- **🧹 Clean Background**: Less cluttered backgrounds improve detection precision
- **💻 System Resources**: Close unnecessary browser tabs and applications
- **📶 Network**: Stable internet connection recommended for initial model loading
- **🔄 Browser Updates**: Use the latest browser version for best performance

## ❓ Frequently Asked Questions

**Q: Why is the app loading slowly?**  
A: The app downloads a ~27MB AI model on first use. Subsequent loads are faster due to browser caching.

**Q: Can I use this app offline?**  
A: No, internet connection is required to download the TensorFlow.js model, though it may work offline after initial load.

**Q: Why aren't some objects being detected?**  
A: The model is trained on 80 specific object types. Objects outside this scope won't be detected. Check the "What Can It Detect?" section for supported objects.

**Q: Is my camera data sent to any servers?**  
A: No! All processing happens locally in your browser. No images or video data are transmitted anywhere.

**Q: Can I adjust detection sensitivity?**  
A: The app uses optimized confidence thresholds, but you can modify these in the source code if needed.

**Q: Why is mobile performance different?**  
A: Mobile devices have varying processing capabilities. Performance depends on your device's CPU/GPU power.

## 📖 How to Use

1. **🌐 Access the App**: Open the application in your web browser
2. **📷 Choose Input Method**: 
   - Select "Camera" for live webcam detection
   - Choose "Upload" to analyze your own images
3. **▶️ Start Detection**: Click the "Start Detection" button
4. **👀 View Results**: 
   - See detected objects highlighted with colored bounding boxes
   - View confidence scores for each detection
   - Real-time object labels and statistics

## 🛠️ Technical Specifications

| Feature | Details |
|---------|---------|
| **AI Model** | COCO-SSD (Single Shot MultiBox Detector) |
| **Framework** | TensorFlow.js |
| **Training Dataset** | COCO (Common Objects in Context) |
| **Model Variants** | MobileNet v1 (~27MB) / MobileNet v2 (~78MB) |
| **Performance** | 30-60 FPS on modern devices |
| **Browser Support** | Chrome, Firefox, Safari, Edge (latest versions) |
| **Device Support** | Desktop, Tablet, Mobile |

## 🎨 Customization Options

The application supports various customization options:

- **🎯 Detection Threshold**: Adjust confidence levels for detection sensitivity
- **🎨 Visual Styling**: Customize bounding box colors, thickness, and label appearance  
- **🔧 Object Filtering**: Show/hide specific object categories
- **📊 Performance Tuning**: Switch between model variants for speed vs accuracy
- **📱 UI Themes**: Light/dark mode support

## 📁 Project Structure

```
ai-vision-detector/
├── index.html          # Main application file
├── index.js            # Core JavaScript logic
├── index.ts            # TypeScript source
├── classes.ts          # Object class definitions
├── package.json        # Project dependencies
├── README.md           # This file
├── cat.jpg            # Sample test image
├── image1.jpg         # Sample test image  
├── image2.jpg         # Sample test image
└── test_inline.html   # Testing utilities
```

## 🔧 Development Setup

For developers wanting to contribute or modify the application:

```bash
# Install dependencies
npm install

# Development build
npm run build

# Run tests
npm test

# Type checking
npm run type-check
```

## 🌟 Use Cases

- **📚 Education**: Learn about computer vision and AI
- **🔬 Research**: Prototype object detection applications  
- **🏠 Smart Home**: Integrate with IoT devices
- **📊 Analytics**: Count and track objects in images/video
- **♿ Accessibility**: Assist visually impaired users
- **📱 Mobile Apps**: Build cross-platform detection features

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **🍴 Fork** the repository
2. **🌿 Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **💾 Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **📤 Push** to the branch (`git push origin feature/AmazingFeature`)
5. **🔃 Open** a Pull Request

### 📋 Contribution Ideas
- Add new object detection models
- Improve mobile responsiveness
- Add export functionality for results
- Create batch processing features
- Enhance accessibility features

## 📄 License

This project is licensed under the **Apache License 2.0** - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

Built with ❤️ using these amazing technologies:

- **[TensorFlow.js](https://www.tensorflow.org/js)** - Machine learning for JavaScript
- **[COCO Dataset](http://cocodataset.org)** - Common Objects in Context
- **[Google Research](https://research.google/)** - Pre-trained COCO-SSD model
- **[TensorFlow.js Community](https://github.com/tensorflow/tfjs)** - Open source contributors

## 🔗 Useful Links

- 🌐 [**Live Demo**](https://jeevanm2004.github.io/ai-vision-detector)
- 📚 [TensorFlow.js Documentation](https://www.tensorflow.org/js/guide)
- 🧠 [COCO-SSD Model Details](https://github.com/tensorflow/tfjs-models/tree/master/coco-ssd)
- 💻 [GitHub Repository](https://github.com/Jeevanm2004/ai-vision-detector)

## 📞 Support

Having issues or questions?
- 🐛 **Bug Reports**: [Open an issue](https://github.com/your-username/ai-vision-detector/issues)
- 💬 **Discussions**: [Join our community](https://github.com/your-username/ai-vision-detector/discussions)
- 📧 **Contact**: jeevanm.bit@gmail.com

---

<div align="center">

**⭐ Star this repository if you found it helpful!**

Made with 🤖 and ❤️ for the AI community

</div>
