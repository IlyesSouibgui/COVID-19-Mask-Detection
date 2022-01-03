# COVID-19-Mask-Detector

In this work, we create a face mask detector (using Keras/TensorFlow and OpenCV), we trained a two-class model of people wearing masks and people not wearing masks.

We fine-tuned MobileNetV2 on our mask/no mask dataset and obtained a classifier that is ~99% accurate.

Once the face mask detector is trained, we can then move on to loading the model, performing face detection, and then classifying each face as with_mask or without_mask in real-time video.
