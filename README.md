# Smart Object Detection App

A powerful web-based object detection application built with TensorFlow.js COCO-SSD model. This project can identify and locate 80 different types of objects in real-time through your webcam or uploaded images.

## 🚀 Features

- **Real-time Detection**: Live object detection using your webcam
- **Image Upload**: Analyze objects in your own photos
- **80 Object Classes**: Detects people, animals, vehicles, furniture, and more
- **Browser-based**: No installation required - runs directly in your web browser
- **Fast & Accurate**: Powered by Google's pre-trained COCO-SSD model
- **Mobile Friendly**: Works on both desktop and mobile devices

## 🎯 What Can It Detect?

The app can identify common objects including:
- **People & Body Parts**: person, hand, face
- **Animals**: dog, cat, bird, horse, cow, sheep
- **Vehicles**: car, truck, bus, motorcycle, bicycle, airplane
- **Food**: apple, banana, sandwich, pizza, cake
- **Electronics**: laptop, phone, TV, keyboard, mouse
- **Furniture**: chair, table, sofa, bed
- And many more!

## 📱 How to Use

1. **Open the Demo**: Navigate to the `demo` folder and open `index.html` in your browser
2. **Choose Input**: Select between webcam or file upload
3. **Start Detection**: Click "Start" to begin real-time object detection
4. **View Results**: See detected objects highlighted with bounding boxes and confidence scores

## 🛠️ Installation & Setup

```bash
# Clone or download this repository
# Navigate to the project folder
cd my-coco-ssd-project

# Install dependencies
npm install

# Run the demo
# Simply open demo/index.html in your browser
```

## 🎨 Customization Options

- Modify detection confidence threshold
- Customize bounding box colors and styles
- Add custom object filtering
- Integrate with your own applications
- Train on custom datasets

## 📊 Technical Details

- **Model**: COCO-SSD (Single Shot MultiBox Detector)
- **Framework**: TensorFlow.js
- **Dataset**: Trained on COCO (Common Objects in Context)
- **Performance**: ~30-60 FPS on modern devices
- **Model Size**: ~27MB (mobilenet_v1) or ~78MB (mobilenet_v2)

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements!

## 📄 License

This project is based on TensorFlow.js models and maintains the original Apache 2.0 license.

## 🙏 Credits

Built upon the excellent work from:
- [TensorFlow.js COCO-SSD Model](https://github.com/tensorflow/tfjs-models/tree/master/coco-ssd)
- Google Research Team
- TensorFlow.js Community

## 🔗 Links

- [Live Demo](#) (Add your GitHub Pages link here)
- [Original TensorFlow Model](https://github.com/tensorflow/tfjs-models/tree/master/coco-ssd)
- [TensorFlow.js Documentation](https://www.tensorflow.org/js)

---

**Built with ❤️ using TensorFlow.js**