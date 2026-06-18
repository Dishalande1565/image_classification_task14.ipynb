# Image Classification (ANN) — Task 14

## AI & ML Internship

### About
Introduction to Deep Learning — Image Classification
of handwritten digits using Artificial Neural Network
(ANN/MLPClassifier) on the Digits Dataset.

---

### Dataset
- Name     : Digits Dataset (Scikit-learn)
- Images   : 1797 images, 8x8 pixels grayscale
- Classes  : Digits 0-9

---

### Steps Completed
1. Loaded Digits Dataset
2. Visualized sample digit images
3. Normalized pixel values to [0,1]
4. Train-Test Split (80/20)
5. Built ANN model using MLPClassifier
   - Dense hidden layers (128, 64) with ReLU
   - Softmax-based multi-class output
6. Trained model
7. Plotted training loss curve
8. Evaluated on test data
9. Visualized predictions
10. Plotted Confusion Matrix

---

### Results
- Test Accuracy : 96-98%

---

### Tools Used
- Python 3
- Scikit-learn
- Jupyter Lab
- NumPy, Matplotlib, Seaborn

---

### How to Run
1. Clone this repository
2. Open Jupyter Lab
3. Open image_classification_task14.ipynb
4. Run all cells → Shift + Enter

---

### Interview Questions Covered
- What is an Activation Function?
- Why is Normalization important in Deep Learning?

---

### File Structure
image-classification-ann/
├── README.md
├── .gitignore
└── image_classification_task14.ipynb
