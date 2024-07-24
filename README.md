In this project demonstrates a basic facial recognition system using Python, OpenCV, NumPy, PIL, and TensorFlow. The system includes data generation, preprocessing, and model training for recognizing faces from webcam input

Code Explanation :
The generate_dataset function captures images from the webcam, detects faces using Haar cascades, crops the faces, and saves them in the specified directories.

The load_data function loads images from the directories, and the process_data function prepares them for model training.

The get_model function defines a simple neural network using TensorFlow.  Then the model is trained using the preprocessed data.
