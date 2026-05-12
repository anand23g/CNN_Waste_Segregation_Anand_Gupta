# CNN Waste Segregation

A Convolutional Neural Network (CNN) project to classify waste images into 7 categories using TensorFlow and Keras.

## Categories
Cardboard, Food Waste, Glass, Metal, Other, Paper, Plastic

## Dataset
7,625 images across 7 classes. Download: `CNN_Waste_Segregation.zip` (stored via Git LFS)

## Setup

```bash
# Create and activate virtual environment (Python 3.12)
python3.12 -m venv venv
source venv/bin/activate

# Install dependencies
pip install tensorflow numpy pandas seaborn matplotlib Pillow scikit-learn ipykernel

# Register Jupyter kernel
python -m ipykernel install --user --name "waste-segregation-tf" --display-name "Python 3.12 (TensorFlow)"
```

## Usage
Open `CNN_Assg_Waste_Segregation_Starter_Anand_Gupta.ipynb` in Jupyter and select the **Python 3.12 (TensorFlow)** kernel.

## Results

| Model | Test Accuracy |
|---|---|
| Baseline CNN | 53.06% |
| Augmented CNN | 55.94% |

## Tech Stack
Python 3.12 · TensorFlow 2.21 · Keras 3.14 · scikit-learn · NumPy · Pandas · Matplotlib
