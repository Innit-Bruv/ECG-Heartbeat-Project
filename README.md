ECG Project: Automated Data Preprocessing, Model Training, and Evaluation
This project automates key tasks for working with Electrocardiogram (ECG) data, using the MIT-BIH Arrhythmia dataset. The notebook provides steps to set up directories, download the dataset, preprocess the data, and train an LSTM model.

Features
Automatic Directory Creation: Sets up directories for datasets, models, and reports.
Dataset Download: Downloads the MIT-BIH Arrhythmia dataset using curl.
Data Preprocessing: Preprocesses the ECG signals for use in training.
LSTM Model Training: Implements a model to classify arrhythmias.
Evaluation & Reports: Generates performance reports and saves the trained models.
Installation
Ensure the required Python libraries are installed:

pip install wfdb biosppy numpy pandas matplotlib tensorflow scikit-learn fpdf
Steps
Install Dependencies: Install necessary libraries listed in the requirements.

Directory Setup & Data Download: The script creates directories for storing datasets, models, and reports. It uses curl to download the MIT-BIH Arrhythmia dataset.

Preprocessing & Model Training: Preprocesses the downloaded ECG data, and trains a Long Short-Term Memory (LSTM) model to classify heart arrhythmias.

Saving Models and Reports: After training, the model and evaluation reports are saved for later use.

Data
The project downloads and uses the MIT-BIH Arrhythmia dataset from PhysioNet:

MIT-BIH Arrhythmia Dataset
Usage
After setting up the environment and downloading the dataset, you can run the entire pipeline in the notebook to preprocess the data and train the model. The results will be saved in the ./models and ./reports directories.

Directory Structure
.
├── dataset
│   ├── 100.dat
│   ├── 100.hea
│   └── 100.atr
├── models
│   └── # Trained models will be saved here
├── reports
│   └── # Generated evaluation reports will be saved here
└── ECG_PROJECT.ipynb
