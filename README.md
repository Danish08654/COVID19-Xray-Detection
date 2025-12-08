# COVID19-Xray-Detection
CNN-based classifier detecting COVID-19 vs Normal X-rays using PyTorch.
# COVID-19 Detection from Chest X-Ray using PyTorch

This project uses a Convolutional Neural Network (CNN) built with PyTorch to detect 
COVID-19 from chest X-ray images. The model classifies images as **COVID-19** or **Normal**.

## Features
- CNN model built using PyTorch
- Image preprocessing using torchvision
- Train/Evaluate/Predict scripts included
- Achieved high validation accuracy (> 95%)
- Saved model included (`covid_cnn.pth`)

## Project Structure
COVID19-Xray-Detection/
│── notebooks/ → Jupyter notebook for training  
│── src/ → All python source code  
│── saved_models/ → Trained model  
│── samples/ → Sample X-ray images  
│── requirements.txt  
│── README.md  

##  Model
- Conv2D layers with ReLU activation  
- MaxPooling layers  
- Fully connected classifier  
- CrossEntropy loss + Adam optimizer  


