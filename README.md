# Credit Card Fraud Detection using GAN

## Project Overview
This project implements a Generative Adversarial Network (GAN) to detect fraudulent transactions from credit card data. The model architecture includes separate generator and discriminator networks designed to learn and generate the distribution of transactional data to identify anomalies indicative of fraud.

### Key Features
- **Data Preprocessing**: Standard scaling, feature selection, and train-test split.
- **Model Architecture**: Custom GAN with distinct generator and discriminator.
- **Training Strategy**: Use of Adam optimizer, binary cross-entropy loss, and model checkpoints.
- **Evaluation**: Precision-recall analysis and confusion matrix visualization.

## Installation

### Prerequisites
- Python 3.8 or higher
- PyTorch
- PyTorch Lightning
- Pandas
- NumPy
- scikit-learn
- Matplotlib

### Setup Environment
To set up your environment to run this code, follow these steps:

```bash
# Clone the repository
git clone https://github.com/your-github-username/credit-card-fraud-detection-gan.git
cd credit-card-fraud-detection-gan

# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows
venv\Scripts\activate
# On Unix or MacOS
source venv/bin/activate

# Install the requirements
pip install -r requirements.txt
