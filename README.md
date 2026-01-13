# PyTorch for Deep Learning Professional Certificate

[![Course](https://img.shields.io/badge/DeepLearning.AI-PyTorch_Specialization-blue)](https://learn.deeplearning.ai/specializations/pytorch-for-deep-learning-professional-certificate)
[![Python](https://img.shields.io/badge/Python-3.8+-green.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.6.0-red.svg)](https://pytorch.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

This repository contains my coursework, assignments, and projects from the **PyTorch for Deep Learning Professional Certificate** offered by DeepLearning.AI. The specialization provides a comprehensive, structured path to learning PyTorch from fundamentals to advanced architectures and deployment.

## 📚 About the Specialization

PyTorch has become one of the most widely used frameworks in AI, powering much of the recent generative AI revolution. This professional certificate program offers a clear, structured learning path starting from fundamentals and building up to advanced architectures step by step.

**Course Link:** [PyTorch for Deep Learning Professional Certificate](https://learn.deeplearning.ai/specializations/pytorch-for-deep-learning-professional-certificate)

## 🗂️ Repository Structure

```
pytorch-specialisation/
├── 1. pytorch fundamental/
│   ├── module1_getting_started_with_pytorch/
│   │   ├── 1. building_simple_neural_network/
│   │   ├── 2. using_activation_function/
│   │   ├── 3. core_tensors/
│   │   └── 4. assignment/
│   ├── module2_pytorch_workflow/
│   │   ├── 1. image_classifier/
│   │   └── 2. assignment/
│   ├── module3_data_management/
│   │   ├── 1. data management/
│   │   └── 2. assignment/
│   └── module4_core_neural_network/
│       ├── 1. cnn nature classification/
│       ├── 2. assignment/
│       └── 2. model_debugging/
├── 2. pytorch tech and ecosystem tools/
└── 3. advanced arch and deployment/
```

## 📖 Course Content

### Course 1: PyTorch Fundamentals ✅ **COMPLETED**

#### Module 1: Getting Started with PyTorch
- **Topics Covered:**
  - The building blocks of neural networks
  - The ML Pipeline
  - Building a simple neural network
  - Activation functions and modeling non-linear patterns
  - Tensors: The core of PyTorch
  - Tensor math and broadcasting
- **Labs:**
  - Building a Simple Neural Network
  - Using Activation Functions
  - Working with Tensors
- **Assignment:** Deeper Regression with Smarter Features

#### Module 2: The PyTorch Workflow
- **Topics Covered:**
  - Complete ML workflow in PyTorch
  - Image classification with MNIST
  - Training, validation, and testing loops
  - Model evaluation and metrics
- **Labs:**
  - MNIST Image Classifier
- **Assignment:** EMNIST Character Classification

#### Module 3: Data Management in PyTorch
- **Topics Covered:**
  - DataLoaders and Datasets
  - Data preprocessing and augmentation
  - Custom dataset creation
  - Batch processing and data pipelines
- **Labs:**
  - Data Management Techniques
- **Assignment:** Custom Dataset Implementation

#### Module 4: Core Neural Network Components
- **Topics Covered:**
  - Convolutional Neural Networks (CNNs)
  - Model architecture design
  - Debugging neural networks
  - Performance optimization
- **Labs:**
  - CNN for Nature Classification
  - Model Debugging Techniques
- **Assignment:** Advanced CNN Implementation

### Course 2: PyTorch - Techniques and Ecosystem Tools 🔄 **IN PROGRESS**
Coming soon...

### Course 3: PyTorch - Advanced Architectures and Deployment 📅 **UPCOMING**
Coming soon...

## 🚀 Getting Started

### Prerequisites
- Python 3.8 or higher
- Basic understanding of Python programming
- Familiarity with machine learning concepts (helpful but not required)

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/yourusername/pytorch-specialisation.git
cd pytorch-specialisation
```

2. **Install dependencies using uv:**
```bash
uv sync
```

Or install from requirements:
```bash
uv pip install -r requirements.txt
```

### Using Jupyter Notebooks

All labs and assignments are provided as Jupyter notebooks. To run them:

```bash
jupyter notebook
```

Or use JupyterLab:
```bash
jupyter lab
```

### 📊 Datasets

Datasets are **not included** in this repository. They are automatically downloaded when you run the notebooks:

- **MNIST** - Handwritten digits (28x28 grayscale images)
- **EMNIST** - Extended MNIST with letters and digits
- **FashionMNIST** - Fashion product images
- **Custom datasets** - Automatically fetched via torchvision

**Storage location:** All datasets are saved in `data/` or `*_data/` directories (gitignored).

**First run:** The first time you run a notebook, datasets will be downloaded automatically. Subsequent runs will use the cached data.

## 📦 Dependencies

Core dependencies include:
- **PyTorch** (2.6.0+) - Deep learning framework
- **torchvision** (0.21.0+) - Computer vision utilities
- **NumPy** (2.3.0+) - Numerical computing
- **Matplotlib** (3.9.0+) - Visualization
- **Pillow** (11.3.0+) - Image processing
- **Jupyter** - Interactive notebooks

See `pyproject.toml` for the complete list of dependencies.

## 🎯 Learning Objectives

By completing this specialization, you will:
- ✅ Understand PyTorch fundamentals and tensor operations
- ✅ Build and train neural networks from scratch
- ✅ Implement CNNs for image classification
- ✅ Master data loading and preprocessing pipelines
- ✅ Debug and optimize neural network models
- 🔄 Learn advanced PyTorch techniques and ecosystem tools
- 📅 Deploy PyTorch models in production environments
- 📅 Work with cutting-edge architectures

## 🏆 Certificates

Certificates will be added upon completion of each course.

## 📝 Notes

- All datasets are automatically downloaded when running the notebooks
- Large datasets and model checkpoints are excluded from version control (see `.gitignore`)
- Each module contains helper utilities specific to that section
- Assignments include unit tests for validation

## 🤝 Contributing

This is a personal learning repository, but suggestions and improvements are welcome! Feel free to:
- Open an issue for bugs or questions
- Submit a pull request for improvements
- Share your own solutions and insights

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **DeepLearning.AI** for creating this comprehensive PyTorch specialization
- **Lawrence Moroney** for excellent instruction and course design
- **Andrew Ng** for continuous contributions to AI education
- The **PyTorch community** for amazing documentation and resources

## 📚 Additional Resources

- [Official PyTorch Documentation](https://pytorch.org/docs/stable/index.html)
- [PyTorch Tutorials](https://pytorch.org/tutorials/)
- [DeepLearning.AI Forum](https://community.deeplearning.ai/)
- [PyTorch GitHub Repository](https://github.com/pytorch/pytorch)

## 📧 Contact

For questions or discussions about this repository:
- Open an issue on GitHub
- Connect on [LinkedIn](https://www.linkedin.com/in/yourprofile)
- Visit the [DeepLearning.AI Forum](https://community.deeplearning.ai/)

---

**Last Updated:** January 2026

⭐ If you find this repository helpful, please consider giving it a star!
