# MNIST_Digit_Classification_using_Neural_Networks
    
This project is a basic implementation of a neural network to classify handwritten digits (0–9) from the famous MNIST dataset using TensorFlow and Keras.

## 🗂️ Dataset

The [MNIST dataset](http://yann.lecun.com/exdb/mnist/) consists of 60,000 training images and 10,000 test images of handwritten digits, each sized 28x28 pixels in grayscale.

## 🚀 Features

- Neural network with fully connected (Dense) layers
- Data normalization and reshaping
- Model evaluation on test data
- Visualization of predictions
- Accuracy & loss curves

## 🧠 Model Architecture

- Input Layer: Flatten (28x28)
- Dense Layer: 128 units (ReLU)
- Dense Layer: 64 units (ReLU)
- Dense Layer: 64 units (ReLU)
- Output Layer: 10 units (Softmax for classification)

## 📦 Dependencies

Install the required libraries with:

    pip install tensorflow numpy matplotlib
    
📈 Sample Output
     
Accuracy Plot and Loss Plot
 ![Accuracyand losspng](https://github.com/user-attachments/assets/a31df3f3-f910-4afb-8778-cd5e8998b016)

Predicted digit for a sample test image
    ![output](https://github.com/user-attachments/assets/dca6d7e3-3572-46f5-a9a6-9f3747c5eb5d)

📊 Model Performance
      
 Trained for 10 epochs
 Final test accuracy: ~98% (may vary slightly)

🖼️ Sample Prediction
      
The script visualizes one test image and shows the predicted digit.

✅ To Do (Future Improvements)
      
Switch to a Convolutional Neural Network (CNN) for better accuracy
Add confusion matrix and classification report
Save and load model (.h5 format)

🧑‍💻 Author

This project was created as a learning exercise.
Feel free to fork, clone, or improve it!
