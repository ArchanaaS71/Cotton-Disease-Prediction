# Cotton-Disease-Prediction
A deep learning-based project for detecting and classifying cotton plant diseases using a hybrid ShuffleNetV2 + MHSA model in PyTorch. The model leverages transfer learning and attention mechanisms for enhanced accuracy on a dataset sourced from Kaggle.



## 📁 Dataset

- **Source**: [Kaggle - Cotton Plant Disease]([https://www.kaggle.com/datasets](https://www.kaggle.com/datasets/dhamur/cotton-plant-disease/data))
- **Classes**:
  - Diseased cotton leaf
  - Diseased cotton plant
  - Fresh cotton leaf
  - Fresh cotton plant



## 🧠 Model Architecture

The core model integrates:
- **ShuffleNetV2**: A lightweight CNN pretrained on ImageNet.
- **MHSA (Multi-Head Self Attention)**: Added after the feature extraction layer to enhance spatial and contextual understanding.

> The classifier head is fully customized with dropout and linear layers for classification.



## 🛠️ Implementation Details

- **Framework**: PyTorch
- **Data Augmentation**:
  - Resize to 224x224
  - Random horizontal flip
  - Random rotation
- **Train/Val/Test Split**: 70% / 15% / 15%



## 📊 Evaluation

The notebook includes:
- Training and validation accuracy tracking
- Loss visualization
- Prediction examples



## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/cotton-plant-disease
   cd cotton-plant-disease


2. Install dependencies:
   '''bash
    pip install -r requirements.txt

    
3. Run the notebook in a Jupyter environment::
   '''bash
   jupyter notebook cotton-plant-disease.ipynb


##📌 Results
The model achieves high classification accuracy on the test set and is lightweight enough for real-time inference on edge devices.


##🤝 Acknowledgments
Dataset by contributors on Kaggle
PyTorch & TorchVision libraries


##📬 Contact
For any questions or collaborations, feel free to reach out!


