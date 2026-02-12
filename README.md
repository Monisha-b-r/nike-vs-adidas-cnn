# Nike vs Adidas Image Classification using CNN

This project builds a Convolutional Neural Network (CNN) model 
to classify shoe images as Nike or Adidas.

## 📌 Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- PIL

## 🧠 Model Architecture
- 3 Convolutional Blocks
- MaxPooling Layers
- Flatten Layer
- Dense Layer (512 neurons)
- Softmax Output (2 classes)

## 📊 Results
The model achieved 100% training accuracy after learning rate tuning and 
successfully predicted unseen Nike and Adidas images.

Example Predictions:

Adidas Image → Correctly Predicted  
Nike Image → Correctly Predicted  

## 🚀 How to Run
1. Open the notebook in Google Colab
2. Upload dataset folders (train/test)
3. Run all cells

## 📌 Future Improvements
- Data augmentation
- Validation split
- Confusion matrix
- Model deployment using Flask
