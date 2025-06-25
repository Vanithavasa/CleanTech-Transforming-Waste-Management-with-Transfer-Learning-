# CleanTech-Transforming-Waste-Management-with-Transfer-Learning-
## ♻️ CleanTech Waste Classifier

**CleanTech Waste Classifier** is a deep learning–based image classification project that leverages transfer learning to automate the identification and segregation of municipal waste. The goal is to support smart waste management systems by classifying waste images into three categories: **Biodegradable**, **Recyclable**, and **Trash**.

### 📌 Project Highlights

* **Model Architecture**: Built using MobileNetV2 as the feature extractor with a custom dense classification head.
* **Dataset**: Contains \~780 images across 3 classes with train-validation split and augmentation.
* **Training**: Achieved \~70% accuracy using TensorFlow and Keras with categorical crossentropy and Adam optimizer.
* **Frontend**: Developed a lightweight, interactive **Streamlit** web app to allow real-time waste image classification.
* **Deployment Ready**: Easily extendable for mobile and edge deployment using TensorFlow Lite.

### 🚀 Features

* Upload any image of waste through the browser interface.
* Get real-time classification output with probability scores.
* Clean UI powered by Streamlit and compatible with low-resource systems.

### 🔮 Future Enhancements

* Expand dataset with more diverse and edge-case samples.
* Test advanced architectures like Vision Transformers.
* Integrate geolocation and environmental sensors for context-aware classification.
* Build a mobile-ready version for real-world deployment.

