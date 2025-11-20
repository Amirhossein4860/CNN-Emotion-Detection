# 📷 CNN-Emotion-Detection
A complete deep learning pipeline for facial emotion recognition, built with TensorFlow and Keras. Features custom CNN architectures, advanced preprocessing, performance visualization, and real-world applications. A clean, powerful demonstration of modern AI for understanding human emotions.


## 🎯 Project Goals

-   Build a robust CNN-based classifier for human emotions
-   Implement the full machine learning pipeline
-   Compare Keras and TensorFlow accuracy results
-   Visualize training history, confusion matrix, and predictions
-   Provide reproducible code for researchers and developers

## 🧠 Model Performance

  Model        Accuracy
  ------------ ------------
  **Keras**    **0.7616**
  TensorFlow   0.6515

The Keras-based architecture shows significantly better performance across precision, recall, and F1-score.

## 🏗️ Architecture Summary

The CNN architecture includes:

 -  Multiple Conv2D + ReLU feature extraction blocks
 -  Batch Normalization & Dropout to stabilize and regularize training
 -  MaxPooling for spatial downsampling
 -  Dense layers for classification
 -  Softmax output for multi-class emotion probabilities

Training uses:

 -  Categorical Crossentropy
 -  Adam optimizer
 -  Early stopping
 -  Data augmentation to improve generalization

## 📚 Dataset

The notebook supports datasets containing labeled facial expressions (such as FER2013 or custom-labeled datasets).

Dataset pipeline includes:

 -  Loading and preprocessing
 -  Normalization
 -  One-hot encoding
 -  Train/Validation Split
 -  Visualization of samples

## 📊 Visualizations

The notebook generates:

- 📈 Accuracy & Loss curves
- 🔄 Confusion matrix
- 🧪 Example predictions with true labels
- 🎭 Emotion distribution across dataset

These plots help track performance, diagnose overfitting, and understand misclassifications.

## 💻 How to Run

1. Clone the repository
``` bash
git clone https://github.com/Amirhossein4860/CNN-Emotion-Detection.git
```
2. Open the notebook
``` bash
jupyter notebook CNN-Emotion_Detection.ipynb
```
3. Train the model

Run all cells in order — the notebook handles:

✔ Data loading
✔ Model building
✔ Training
✔ Evaluation
✔ Visualization

## 🏆 Results

- The Keras CNN achieves 76% accuracy, outperforming the baseline TensorFlow model.
- Confusion matrix indicates strong performance for Happy, Neutral, and Surprise.
- Harder classes include Disgust and Fear, common in FER datasets due to subtle facial cues.

## 🚀 Future Improvements

To extend the project:

 -  Add ResNet50/ EfficientNet as backbone
 -  Train with larger or high-quality datasets
 -  Use transfer learning to boost accuracy
 -  Deploy model as an API or web app
 -  Convert to TensorFlow Lite for mobile devices

## 🤝 Contributing

Pull requests, model improvements, or dataset suggestions are welcome!


## 🙌 Acknowledgements

Special thanks to the open-source community and authors of facial expression datasets that make FER research possible.
