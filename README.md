# CNN Activation Functions Comparison

TensorFlow · Keras · Python · MIT License

An academic research project comparing ReLU vs Sigmoid activation functions in CNN for image classification (Anime, Cartoon, Human).

## Project Overview

This project implements and compares Convolutional Neural Networks (CNNs) with different activation functions for multi-class image classification.

## Key Features

- CNN implementation with ReLU activation
- CNN implementation with Sigmoid activation
- Comprehensive performance comparison
- Detailed analysis and visualization

## Project Structure
```
cnn-activation-comparison/
├── notebooks/
│ ├── CNN_Model_Relu.ipynb
│ └── CNN_Model_Sigmoid.ipynb
├── reports/
│ └── Image_Classification_Project_Report.pdf
├── requirements.txt
├── README.md
└── LICENSE
```
## Quick Start

```bash
git clone https://github.com/Safaa-Abdallah/cnn-activation-comparison.git
cd cnn-activation-comparison
pip install -r requirements.txt
jupyter notebook notebooks/
```

## Results

| Model | Accuracy | F1-Score | Status |
|----------|----------|----------|-------------|
| **ReLU** | **99.21%** | **99.22%** | ✅ Recommended |
| Sigmoid | 34.64% | 17.83% | ❌ Not suitable |

## Author

**Safaa Kamaleldin Izzeldin Abdallah**
Data Analytics Student - Berlin School of Business & Innovation

## License

MIT License - see LICENSE file for details.
