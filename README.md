```markdown
# CIFAR-10 Image Classification

This project implements image classification using the CIFAR-10 dataset in Python. The goal is to train a deep learning model that can correctly classify images from one of ten classes, showcasing an effective approach to solving image recognition tasks.

## Features
- **Image Classification:** Train and evaluate a deep learning model on the CIFAR-10 dataset.
- **Data Augmentation:** Utilize data augmentation techniques to improve model generalization.
- **Simple and Modular Codebase:** Organized Python modules for dataset handling, model architecture, and training routines.

## Getting Started

### Prerequisites
- Python 3.6 or higher
- Required packages (see `requirements.txt`):
  - numpy
  - tensorflow or pytorch (depending on your preference)
  - matplotlib
  - scikit-learn

Install dependencies using:
```bash
pip install -r requirements.txt
```

### The CIFAR-10 Dataset
The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The dataset is automatically downloaded and preprocessed by the script, so no manual download is necessary.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/devcristi/cifar-10.git
   ```
2. Change to the project directory:
   ```bash
   cd cifar-10
   ```
3. Install the required Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage
Run the main training script to start model training and evaluation:
```bash
python main.py
```
This script will:
- Load and preprocess the CIFAR-10 dataset.
- Build and compile the model.
- Train the model while logging key performance metrics.
- Evaluate the model on the test set and print the results.

## File Structure
- **main.py:** The entry point of the project, handling data loading, model training, and evaluation.
- **models.py:** Contains definitions for one or more model architectures.
- **utils.py:** Utility functions for data preprocessing, augmentation, and visualization.
- **requirements.txt:** List of required Python packages.
- **LICENSE:** Project license information.

## Results
Upon running the training script, the model will output performance metrics such as accuracy and loss. My maximum accuracy was 87.5%.

##Note
Since the model is light, there is no need for having a dedicated GPU. In this case, you can use Google Collab for best results.

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request with suggestions, bug fixes, or improvements.

## License
This project is open source and available under the MIT License. See the [LICENSE](LICENSE) file for details.
```
