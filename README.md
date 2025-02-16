# Brain_Tumor_Classification and Creating a GUI using Tkinter

## About Brain Tumor
A brain tumor is a mass or growth of abnormal cells in your brain. Many different types of brain tumors exist. Some brain tumors are noncancerous (benign), and some brain tumors are cancerous (malignant).

Brain tumors can begin in your brain (primary brain tumors), or cancer can begin in other parts of your body and spread to your brain as secondary (metastatic) brain tumors.

How quickly a brain tumor grows can vary greatly. The growth rate as well as the location of a brain tumor determines how it will affect the function of your nervous system.

Brain tumor treatment options depend on the type of brain tumor you have, as well as its size and location.

## Problem Definition
Brain tumors are complex, with many abnormalities in their sizes and locations. This complexity makes it difficult to fully understand the nature of the tumor. Additionally, a professional neurosurgeon is required for MRI analysis. In developing countries, the lack of skilled doctors and knowledge about tumors makes it challenging and time-consuming to generate reports from MRIs. An automated system on the cloud can solve this problem.

## Task
Detect and classify brain tumors using Convolutional Neural Networks (CNN) and Random Forest.

---

## Project Overview

This project aims to create a system that detects and classifies brain tumors from MRI images using deep learning and machine learning techniques. The project will also involve creating a graphical user interface (GUI) using Tkinter for ease of use.

### Key Components

1. **Data Collection**: Gather MRI images for training and testing the model.
2. **Data Preprocessing**: Preprocess the images to ensure they are suitable for the CNN.
3. **Model Training**:
   - **CNN**: Train a Convolutional Neural Network to classify the images.
   - **Random Forest**: Use Random Forest for additional classification and validation.
4. **Model Evaluation**: Evaluate the performance of the trained models.
5. **GUI Development**: Develop a GUI using Tkinter to allow users to upload MRI images and view the classification results.

### Requirements

- Python 3.x
- TensorFlow/Keras for CNN
- Scikit-learn for Random Forest
- Tkinter for GUI
- Other libraries: NumPy, Pandas, Matplotlib, OpenCV

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Brain_Tumor_Classification.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Brain_Tumor_Classification
    ```
3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

### Usage

1. **Train the model**:
    ```bash
    python train_model.py
    ```
   This will train the CNN model using the provided dataset.

2. **Run the GUI**:
    ```bash
    python gui.py
    ```
   This will open the Tkinter GUI where you can upload MRI images and get the classification results.

### Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request.

### License

This project is licensed under the MIT License.

### Contact

For any questions or feedback, please contact [your-email@example.com](mailto:your-email@example.com).

---

By using this system, we aim to assist medical professionals in the early detection and classification of brain tumors, ultimately contributing to better patient outcomes.
