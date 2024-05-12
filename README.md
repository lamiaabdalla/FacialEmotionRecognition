# FacialEmotionRecognition
Overview
The ultimate goal of this project is to help with the early identification and monitoring of mood disorders like anxiety and depression by developing a real-time facial expression detection system that is specifically designed for applications in mental health monitoring. The system uses deep learning techniques to identify and categorise facial expressions corresponding to various emotional states.
Objectives:
•	Develop a facial expression identification system that can recognise and classify facial expressions in real time.
•	Use state-of-the-art deep learning techniques, such as graph convolutional networks, transfer learning, and attention mechanisms, to improve the precision and effectiveness of emotion recognition.
•	Utilising benchmark datasets, assess the system's accuracy, efficiency, and durability and compare its results to those of other methods.
•	Examine possible uses for real-time facial expression recognition in the surveillance of mental health.
Code Overview:
•	Using TensorFlow/Keras and Python, the given code creates a real-time face expression recognition system. Here is a quick rundown of the essential elements:
•	Data Preparation: Seven facial expression classes' worth of photos are taken from the FER2013 dataset.
•	Model Architecture: Convolutional layers, max-pooling layers, and fully connected layers make up a convolutional neural network (CNN), which is used to recognise emotions.
•	Training: Using data augmentation and training/validation split methods, the model is trained on the preprocessed dataset.
•	Real-time Inference: Video frames from a camera are captured using OpenCV, and the trained model predicts emotions in real-time.
•	Visualisation: Matplotlib is used to visualise the training history (accuracy/loss).
Data:
Its FER2013 data set with 28709 images belonging to 7 classes in train folder and 7178 images belonging to 7 classes for test.
Usage
•	Download the FER 2013 dataset from Keggle.
•	Upload the notebook to google colab and upload the dataset folder to the drive
mount the drive to colab environment.
•	Keep the dataset and the notebook file in the same directory
•	Run the notebook.

