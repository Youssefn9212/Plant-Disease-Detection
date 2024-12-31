# Plant Disease Detection

This project focuses on leveraging machine learning to detect and classify apple tree leaf conditions into three categories: **Healthy**, **Rust**, and **Powdery**. Early detection of plant diseases is essential for effective crop management, and this project aims to provide a robust solution to support farmers and the agriculture industry.

---

### Project Contributors
- **Youssef Nakhla**
- **Charbel El Fakhry**

---

### Project Overview

Plant diseases pose a significant threat to agricultural productivity, often leading to economic losses. This project explores state-of-the-art image classification techniques to identify diseases in apple tree leaves, enabling timely interventions and improved yield management. By integrating data augmentation and advanced neural networks, this project enhances the model's accuracy and robustness.

---

### Project Phases

#### **Phase 1: Problem Identification**
- **Objective:** Identify the need for automated plant disease detection and establish a machine learning solution.
- **Key Points:**
  - Defined the problem of classifying apple tree leaf conditions.
  - Highlighted the potential benefits of using image-based machine learning models in agriculture.

#### **Phase 2: Dataset Preparation**
- **Objective:** Prepare a high-quality dataset for training and testing the models.
- **Key Steps:**
  - Curated a dataset containing images of apple tree leaves labeled as Healthy, Rust, or Powdery.
  - Applied data augmentation techniques (e.g., rotation, flipping, cropping) to artificially expand the dataset.

#### **Phase 3: Baseline Model**
- **Objective:** Implement a simple convolutional neural network (CNN) as the baseline model.
- **Outcome:** The baseline model provided initial insights but showed limitations in complexity and accuracy.

#### **Phase 4: Model Improvement**
- **Objective:** Experiment with advanced architectures and compare their performance.
- **Proposed Models:**
  - **Revised CNN:** Enhanced architecture of the baseline model.
  - **ResNet-34:** Deep residual network for robust image classification.
  - **Inception V3:** Complex architecture optimized for feature extraction.
  - **Ensemble Learning:** Combined predictions from multiple models.

#### **Phase 5: Results and Analysis**
- **Objective:** Evaluate model performance and identify the best approach.
- **Results:**
  - The revised CNN achieved the best balance between accuracy and computational efficiency.
  - Data augmentation significantly improved model robustness.

#### **Phase 6: Conclusion and Future Work**
- **Conclusion:**
  - CNN proved to be the most effective model for this task.
  - Data preprocessing and augmentation had a greater impact than hyperparameter tuning.
- **Future Work:**
  - Expand the dataset to include other crops and diseases.
  - Explore more advanced CNN architectures and broader parameter ranges.

---

### Repository Contents

- **`notebooks/`**: Contains Jupyter notebooks for data preprocessing, training, and evaluation.
- **`models/`**: Saved models and architecture files.
- **`data/`**: Dataset used for training and testing.
- **`reports/`**: Detailed project reports and presentations.
- **`requirements.txt`**: Dependencies for setting up the project environment.

---

This project demonstrates the potential of machine learning in revolutionizing agricultural practices, paving the way for smarter and more sustainable farming solutions.
