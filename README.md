
# 🖼️ Computer Vision Assignment 1

## 👤 Author
**Omer Kamal Ali Ebead**

---

## 📝 Overview
This project explores various approaches to solving computer vision challenges using Python and deep learning frameworks. The assignment includes tasks such as building custom architectures, applying transfer learning, and implementing advanced techniques like Snapshot Ensembles.

### 🌟 Problems Addressed:
1. **🔍 Custom Architectures on CIFAR-10**:
   - 🛠️ Built simple CNNs and added regularization, dropout, and batch normalization.
   - 🚦 Used early stopping and snapshot ensembles for performance improvement.

2. **🚀 Transfer Learning with Inception V3**:
   - 📦 Leveraged pre-trained Inception V3 for feature extraction, adding a custom classifier for CIFAR-10.
   - 📈 Achieved significant accuracy improvements.

3. **🧩 Occlusion Sensitivity Analysis**:
   - 🖼️ Analyzed the impact of occluding parts of an image on model predictions.
   - 🔥 Visualized prediction probabilities with a heatmap.

---

## 📂 Directory Structure
```
.
├── omer_cv_assignment_1.py     # Python implementation of the assignment
├── omer_CV_Assignment_1.pdf    # Detailed description and results
```

---

## 🛠️ Dependencies
This project requires the following Python libraries:
- TensorFlow/Keras
- NumPy
- Matplotlib
- Seaborn
- PIL (Pillow)
- OpenCV
- Requests

Install dependencies with:
```bash
pip install tensorflow numpy matplotlib seaborn pillow opencv-python requests
```

---

## ▶️ Running the Code
1. 📥 Clone this repository or download the files.
2. ✅ Ensure all dependencies are installed.
3. 🏃 Run the Python script:
   ```bash
   python omer_cv_assignment_1.py
   ```
   The script will:
   - 🧪 Train models with various configurations for CIFAR-10.
   - 🤖 Perform transfer learning using Inception V3.
   - 🗺️ Generate occlusion maps for a sample image.

---

## 📊 Results
### Problem 1:
- 🧱 Custom CNNs achieved up to **70% validation accuracy** using batch normalization and early stopping.
- 💡 Snapshot Ensembles yielded an average of **72% test accuracy**.

### Problem 2:
- 🌐 Transfer learning with Inception V3 improved accuracy to **83%**.

### Problem 3:
- 📉 Visualized the sensitivity of a ResNet V2 model to occlusions, showing prediction drops when key features were hidden.

---

## 🔗 References
- 📄 Snapshot Ensemble paper: [1704.00109v1](https://arxiv.org/pdf/1704.00109v1)
- 📘 Kaggle tutorial on Snapshot Ensembles: [Snapshot Ensemble Tutorial](https://www.kaggle.com/code/fkdplc/snapshot-ensemble-tutorial-with-keras)

