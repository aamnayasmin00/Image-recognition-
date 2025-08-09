# Image-recognition-
This is my face recognition project where I trained a model to recognize different people from images.
I collected the dataset myself from Google and used it to train and test the model inside a Jupyter notebook.

Dataset
I collected the dataset manually from Google and saved it as a .7z file (Training Faces.7z).
After extracting, I arranged the images in folders where each folder represents one person.

The folder structure after extraction looks like this:

kotlin
Copy
Edit
data/
  train/
    person_1/
    person_2/
    ...
  val/              # optional validation set
  test/             # optional test set
Each folder name is the label for that person’s images.

Tools & Libraries I Used
Python

TensorFlow / Keras

NumPy

Pandas

Matplotlib

scikit-learn

OpenCV

What I Did in This Project
Data Preprocessing

Loaded images from folders

Resized them to a fixed size

Normalized pixel values

Split the data into training and validation sets

Model Building

Created a CNN model using Keras

Used ReLU activation in hidden layers and Softmax for the output layer

Model Training

Used Adam optimizer and categorical cross-entropy loss

Trained the model for multiple epochs while tracking accuracy and loss

Model Evaluation

Plotted training/validation accuracy and loss curves

Calculated accuracy and checked the confusion matrix

Predictions

Tested the model on new images to see how well it recognizes the correct person

How to Run My Project
Extract the Training Faces.7z dataset into a folder named data/.

Open the notebook face recognition.ipyng.ipynb in Jupyter Notebook.

Change the dataset path in the first cell to match where you extracted the data.

Run all the cells in order to train and test the model.

Try running the prediction section with your own image.

Output
Training and validation accuracy

Loss curves

Confusion matrix

Predicted labels for test images

Notes
The dataset is for learning purposes only.

Since the dataset was collected from the internet, there may be biases and it should not be used for any real-world identification system.
