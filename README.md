# 🐾 Oxford-IIIT Pet Dataset Segmentation using U-Net

Deep learning based semantic segmentation project built using PyTorch and the Oxford-IIIT Pet Dataset. This repository focuses on accurate foreground pet segmentation using U-Net architectures, attention mechanisms, and multi-task learning techniques.

---

## 📌 Project Summary

This project implements and evaluates multiple U-Net based architectures for semantic segmentation on the Oxford-IIIT Pet Dataset. The workflow covers the complete deep learning pipeline including:

* Data preprocessing and augmentation
* Custom PyTorch dataset and dataloaders
* U-Net and Attention U-Net implementation
* Training and validation pipeline
* Quantitative performance evaluation
* Visualization of segmentation predictions
* Experimental multi-task learning extensions

The primary objective was to improve segmentation quality while maintaining stable training performance across different architectural variations.

---

## ✨ Key Features

* Custom implementation of U-Net architecture
* Attention U-Net with attention gating mechanism
* Multi-task learning setup for segmentation and classification
* End-to-end training and evaluation workflow in PyTorch
* GPU training support
* Visualization pipeline for masks and predictions
* Multiple evaluation metrics including Dice Score and IoU

---

## 📂 Dataset

**Dataset:** Oxford-IIIT Pet Dataset

The dataset contains annotated pet images with corresponding segmentation masks.

### Dataset Information

* 37 cat and dog breeds
* Pixel-level segmentation annotations
* RGB images with trimap masks
* Real-world image variations in pose, lighting, and background

---

## 🧠 Model Architectures

### 🔹 U-Net

A convolutional encoder-decoder architecture with skip connections designed for precise semantic segmentation.

### 🔹 Attention U-Net

An enhanced variation of U-Net that incorporates attention gates to focus on relevant spatial features during decoding.

---

## ⚙️ Tech Stack

| Category                | Technologies        |
| ----------------------- | ------------------- |
| Programming Language    | Python              |
| Deep Learning Framework | PyTorch             |
| Data Processing         | NumPy, Pandas       |
| Visualization           | Matplotlib, Seaborn |
| Image Processing        | PIL, torchvision    |
| Utilities               | tqdm, scikit-learn  |

---

## 🔄 Project Workflow

```text
Data Collection
      ↓
Preprocessing & Augmentation
      ↓
Dataset & DataLoader Creation
      ↓
Model Development
      ↓
Training & Validation
      ↓
Performance Evaluation
      ↓
Prediction Visualization
```

---

## 📊 Evaluation Metrics

The models were evaluated using:

* Dice Coefficient
* Intersection over Union (IoU)
* Mean IoU (mIoU)
* Pixel Accuracy
* Classification Accuracy
* Precision and Recall

---

## 📈 Results

### ✅ Base U-Net

| Metric                  | Score  |
| ----------------------- | ------ |
| Dice Score              | 0.9064 |
| Mean IoU                | 0.8641 |
| Pixel Accuracy          | 0.9289 |
| Classification Accuracy | 0.5407 |

### ✅ Attention U-Net

| Metric                  | Score  |
| ----------------------- | ------ |
| Dice Score              | 0.9178 |
| Mean IoU                | 0.8816 |
| Pixel Accuracy          | 0.9387 |
| Classification Accuracy | 0.5159 |

The Attention U-Net achieved better segmentation performance with improvements in Dice Score and IoU metrics.

---

## 📁 Repository Structure

```text
├── notebook.ipynb
├── README.md
├── requirements.txt
├── images/
│   ├── predictions/
│   └── training/
└── models/
```

---

## 🚀 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Notebook

```bash
jupyter notebook
```

---

## 🖼️ Sample Outputs

The notebook includes:

* Original input images
* Ground truth masks
* Predicted segmentation masks
* Training logs and performance curves
* Comparative model evaluation

You can add screenshots after uploading the repository.

```markdown
![Prediction Result](images/sample_output.png)
```

---

## 🔮 Future Improvements

Potential future enhancements include:

* Transfer learning with pretrained encoders
* Lightweight architectures for faster inference
* Real-time segmentation deployment
* Improved breed classification accuracy
* Hyperparameter optimization
* Deployment using Streamlit or Flask

---

## 🎓 Learning Outcomes

This project helped strengthen practical understanding of:

* Semantic segmentation
* Encoder-decoder neural networks
* Attention mechanisms in computer vision
* PyTorch model development
* Deep learning evaluation techniques
* Multi-task learning approaches

---

## 👨‍💻 Author

**Your Name**

Undergraduate student focused on Machine Learning, Deep Learning, and Computer Vision.

---

## 📜 License

This project is intended for educational and research purposes.
