 
# Hemorrhage Detection Using Deep Learning

This project focuses on detecting brain hemorrhages in CT scan images using a Convolutional Neural Network (CNN) model built with Keras and TensorFlow. It is designed as a prototype for medical image classification that aids in quick and reliable hemorrhage diagnosis.

## Project Structure

```
hemorrhage-detection/
├── hemorrhage_detection.ipynb   # Jupyter notebook with complete code
├── README.md                    # Project documentation (this file)
├── /dataset/                    # Folder containing CT scan images (not included here)
└── /models/                     # Saved model files (if exported)
```

## Features

* Image pre-processing using OpenCV and PIL
* Custom CNN architecture
* Binary classification: Hemorrhage vs. No Hemorrhage
* Model training and evaluation
* Accuracy and loss visualization using Matplotlib
* TensorFlow and Keras for deep learning implementation

##  Sample Input

The model is trained on brain CT images. You need to provide a dataset structured like:

```
dataset/
├── yes/   # CT scans with hemorrhage
└── no/    # CT scans without hemorrhage
```

##  Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/RohiniReddyRemata/hemorrhage-detection.git
   cd hemorrhage-detection
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook hemorrhage_detection.ipynb
   ```

##  Model Performance

The notebook includes plots for training and validation accuracy/loss. Sample output:

* Training Accuracy: \~97%
* Validation Accuracy: \~94%
* Model optimized using Adam optimizer and binary crossentropy loss

##  Dataset

>   [Kaggle](https://www.kaggle.com/c/rsna-intracranial-hemorrhage-detection).

##  Technologies Used

* Python 3.x
* TensorFlow / Keras
* NumPy
* Matplotlib
* OpenCV
* PIL

##  Future Enhancements

* Integration with transfer learning (e.g., VGG16, ResNet)
* Deployment as a web app using Flask or Streamlit
* Integration with DICOM file formats
* Clinical validation with radiologists

   
