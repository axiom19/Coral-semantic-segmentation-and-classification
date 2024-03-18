## Workflow Overview

### 1. Preprocessing and Label Generation

- **Convert `.cpc` Annotations and Images**: Transform `.cpc` annotations and associated `.jpeg` images into structured text files for easier data manipulation.
- **Label Extraction and Refinement**: Prepare the dataset for processing by extracting and refining labels.

### 2. Label Verification and Class Distribution Analysis

- **Verification by Marine Biologists**: Engage marine biologists in the label verification process to ensure accuracy.
- **Analysis of Class Distribution**: Identify imbalances within the dataset to inform effective data augmentation strategies.

### 3. Data Augmentation for Class Balancing

- **Addressing Class Imbalance**: Employ data augmentation techniques to balance classes, enhancing model robustness.
- **Tailored Augmentation Techniques**: Use geometric transformations, color space adjustments, and synthetic data generation, specifically designed for coral imagery.

### 4. Dataset Splitting for Model Evaluation

- **Training, Validation, and Test Sets**: Split the dataset to support iterative model development, tuning, and evaluation.
- **Preventing Overfitting**: Ensure model generalizability by using separate data sets for training and evaluation.

### 5. Weakly Supervised Learning for Coral Classification

- **Leveraging Minimal Annotations**: Develop a model that classifies coral species with minimal manual annotations.
- **Efficient Learning and Improved Performance**: Reduce dependency on extensive labeled datasets by utilizing unlabeled data structure.


