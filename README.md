# Image Classification Project using Teachable Machine and Python

This project is a practical application of training a Machine Learning model to recognize and classify images using Google's **Teachable Machine**, then exporting and running it locally via **Python** within the **Anaconda** environment.

## 📁 Repository Structure
* `main.py`: The Python script that loads the model, processes the input image, and predicts its class.
* `keras_Model.h5`: The trained model exported in TensorFlow/Keras format.
* `labels.txt`: A text file containing the names of the classes the model was trained on.
* **Screenshot:** An image showing the successful execution of the code and the terminal output.

## 🛠 Prerequisites
To run the code successfully, make sure to install the following libraries inside your Conda environment:

```bash
pip install tensorflow pillow numpy
```

## 🚀 How to Run
1. Download all the files in this repository and place them in a single folder on your local machine.

2. Open the **Anaconda Prompt**.

3. Activate the project's environment using the following command:
```bash
conda activate TeachableMachine
```

4. Navigate to the folder containing the files using the `cd` command (example):
```bash
cd C:\Users\wasee\Downloads\converted_keras
```

5. Run the Python script to test the model:
```bash
python main.py
```

## 📊 Results
When testing the model on the input image, it successfully recognized and classified it with very high confidence:
<img width="1036" height="255" alt="image" src="https://github.com/user-attachments/assets/999cd0cd-db62-4f1d-868d-53d102f1f419" />
<img width="1588" height="913" alt="image" src="https://github.com/user-attachments/assets/ffea76d3-a073-4cf7-b4de-103ae7913c06" />

* **Predicted Class:** Appels (Apples)
* **Confidence Score:** 0.998 (equivalent to 99.8%)
