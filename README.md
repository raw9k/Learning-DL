# 🧠 Learning Deep Learning (Learning-DL)

Welcome to my Deep Learning repository! This workspace is dedicated to my journey of learning, experimenting, and practicing Deep Learning concepts. It contains implementations of various neural network architectures, custom projects, and notebook experiments.

## 🚀 Goals
- Understand the core concepts of Deep Learning and Neural Networks.
- Build classic and modern architectures from scratch (CNNs, RNNs, LSTMs, Transformers, etc.).
- Practice building, compiling, training, and tuning models.
- Apply deep learning concepts to real-world datasets.

## 🛠️ Tech Stack & Tools
- **Frameworks:** TensorFlow, Keras
- **Languages:** Python
- **Environment:** VS Code
- **Libraries:** NumPy, Pandas, Matplotlib, VisualKeras

## 📂 Projects & Implementations

Here is a log of the architectures and concepts I have implemented so far:

| Project / Architecture | Description | Code / Notebook |
| :--- | :--- | :--- |
| **Credit Card Customer Churn Prediction** | Artificial Neural Network model used to predict customer churn using credit card data. | [`Credit-card-customer-churn-prediction.ipynb`](./Credit-card-customer-churn-prediction.ipynb) |
| **AlexNet (From Scratch)** | Implementation of the classic 2012 AlexNet CNN architecture using Keras Sequential API. Includes Conv blocks, Max Pooling, and Fully Connected layers. | [`AlexNet_Architechture.ipynb`](./AlexNet_Architechture.ipynb) |
| **MNIST Dataset Classification** | Artificial Neural Network (ANN) used to classify handwritten digits from the MNIST dataset. | [`mnist-data.ipynb`](./mnist-data.ipynb) |
| **Transfer Learning with VGG16** | Implementation of Transfer Learning (Feature Extraction and Fine-Tuning) using the pre-trained VGG16 model on a Cats vs. Dogs dataset. | [`Transfer-learning.ipynb`](./Transfer-learning.ipynb) |
| **Data Augmentation** | Demonstrates image data augmentation techniques using Keras `ImageDataGenerator` and training a custom CNN model from scratch. | [`Data-Augmentation.ipynb`](./Data-Augmentation.ipynb) |

## ⚙️ Setup & Installation

To run the notebooks in this repository locally, you'll need to set up a Python environment with the required dependencies.

1. **Clone the repository (if hosted on GitHub):**
   ```bash
   git clone https://github.com/your-username/Learning-DL.git
   cd Learning-DL
   ```

2. **Create a Conda Environment (Recommended):**
   ```bash
   conda create -n dl_env python=3.10
   conda activate dl_env
   ```

3. **Install Dependencies:**
   ```bash
   pip install tensorflow numpy pandas matplotlib jupyter visualkeras 
   conda install -y -c conda-forge graphviz pydot # for plot_model visualizations
   ```

## 📚 Resources & References
* [TensorFlow / Keras Documentation](https://www.tensorflow.org/api_docs)
* [ImageNet Classification with Deep Convolutional Neural Networks (AlexNet Paper)](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks.pdf)

---
*Happy Learning! 🚀 Feel free to explore the notebooks to see the code in action.*

