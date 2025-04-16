# Early Detection of Alzheimer's Disease from MRI Images 

This repo contains my machine learning project where I built a model to detect signs of **Alzheimer’s Disease** using **MRI brain scan images**.  

---

## What I Did in This Project

- Collected MRI image data (from Kaggle or other open datasets)
- Preprocessed the images:
  - Resized them
  - Converted them to grayscale or normalized them
  - Structured into folders (like `train`, `test`, and `val`)
- Built a **Convolutional Neural Network (CNN)** using **TensorFlow/Keras**
- Trained the model to classify MRI scans into Alzheimer’s stages (like Mild, Moderate, etc.)
- Plotted accuracy and loss graphs
- Saved the trained model for reuse or deployment

---

## What's in the Repo

```bash
.
├── Alzheimer_Detection_Model.ipynb   
├── dataset/                          
├── model/                            
└── README.md                         
```

---

## How the Model Works

1. Images are loaded and resized
2. CNN model is created with:
   - Conv2D layers
   - MaxPooling
   - Dropout (to avoid overfitting)
3. Model is trained on labeled MRI data
4. Accuracy and loss are plotted for visualization
5. You can test the model with new MRI images!

---
