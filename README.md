# DenseNet121 for Apple Leaf Disease Detection

This repository contains the implementation of **DenseNet121** for detecting apple leaf diseases using deep learning. The model classifies leaves into **Healthy, Rust, Scab, or Multiple Diseases** using transfer learning.

## **Dataset**
- Dataset: [Plant Pathology 2020 - FGVC7 | Kaggle](https://www.kaggle.com/competitions/plant-pathology-2020-fgvc7)
- Images of apple leaves for different diseases.

## **Model Overview**
- Uses **DenseNet121** as the backbone for feature extraction.
- Pre-trained on **ImageNet**, with transfer learning applied.
- **Global Average Pooling (GAP)** to reduce overfitting.
- Final classification with a **Softmax layer**.

## **Installation & Requirements**
To run this project, install the required dependencies:

```bash
pip install tensorflow keras numpy pandas matplotlib seaborn
```

## **Usage**
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/DenseNet121-AppleLeaf-Disease-Detection.git
   cd DenseNet121-AppleLeaf-Disease-Detection
   ```
2. Open and run `Densenet_final.ipynb` in Jupyter Notebook.
3. Load the dataset and start training the model.

## **Results**
- **94% accuracy** on test data.
- High **precision & recall** in disease classification.

## **Future Improvements**
- Fine-tuning with a larger dataset.
- Implementing advanced augmentation techniques.

## **License**
This project is licensed under the **MIT License**.

---

