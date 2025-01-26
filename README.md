# Multi-Model Image Classification

## Overview
This repository contains the implementation of a **Multi-Model Image Classification** system. The project leverages multiple deep learning architectures to classify images into distinct categories. The objective is to achieve high accuracy by combining the strengths of different models through ensembling.

## Features
- Utilizes multiple pre-trained and custom models for image classification.
- Supports ensembling techniques to improve performance.
- Modular design for easy customization and extension.
- Detailed performance metrics and evaluation.

## Prerequisites
Ensure the following are installed before setting up the project:

- Python 3.8 or later
- PyTorch
- NumPy
- Matplotlib
- scikit-learn
- Jupyter Notebook (optional, for interactive usage)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/multi-model-image-classification.git
   cd multi-model-image-classification
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Training
To train the models, modify the `config` file to specify your dataset path and training parameters. Then, run:
```bash
python train.py
```

### Evaluation
To evaluate the trained models, use:
```bash
python evaluate.py
```

### Ensembling
For ensembling predictions from multiple models:
```bash
python ensemble.py
```

### Interactive Notebook
You can explore and modify the implementation using the provided Jupyter Notebook:
```bash
jupyter notebook Multi_Model_Image_Classification.ipynb
```


Modify the paths in the `config` file or notebook as needed.

## Models
The following models are implemented and can be ensembled:
- ResNet-110
- Wide ResNet 40-8
- DenseNet variations
- PreResNet-110
- Others (as listed in the notebook)

## Results
The final results of the ensembling process are saved as a CSV file and plotted for analysis. Evaluation metrics include:
- Accuracy
- Precision
- Recall
- F1-score

## Contributing
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.


