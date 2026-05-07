# CIFAR-10 Image Recognition

This project implements a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset into 10 different classes.

## Dataset

This project uses the **CIFAR-10** dataset.

**Source:** Kaggle Kernel - [parkminho3/cifar-10](https://www.kaggle.com/parkminho3/cifar-10)

### Dataset Details:
- Total images: 60,000
- Image size: 32×32 pixels
- Classes: 10
- Training set: 50,000 images
- Test set: 10,000 images

### Classes:
Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck

## Model Architecture

- 3 Convolutional layers with ReLU activation
- 3 MaxPooling layers
- Dropout (0.5) for regularization
- Dense layers: 256 units → 10 units (Softmax)

## Results

| Metric | Value |
|--------|-------|
| Test Accuracy | 74.96% |
| Validation Accuracy | 74.92% |
| Loss | 0.7439 |

## How to Run

1. Open `cifar-10.ipynb` in Google Colab or Kaggle
2. Run all cells sequentially
3. Model will train automatically

## Requirements

- TensorFlow 2.x
- Python 3.x
- NumPy, Pandas, Matplotlib, Scikit-learn

## License

MIT License
