# Computer-Vision-and-Natural-Language-Processing
Computer Vision (CV) is a field in artificial intelligence that focuses on the ability of computers to visually interpret and understand information from images and videos. 

Natural Language Processing (NLP) is a branch of artificial intelligence that deals with the interaction between computers and human language (natural language). 

Case 1 Digital Image Processing

This project aims to replicate the camera lighting technology from Apple and Samsung using the max pooling technique to overcome low lighting conditions, and compare it with the Contrast Limited Adaptive Histogram Equalisation (CLAHE) approach.
CLAHE is a better approach in maintaining the visual quality and natural contrast of the image. Meanwhile, max pooling provides an effective solution for dramatic low lighting but potentially sacrifices details in some parts of the image. Using a combination of these two approaches can be an ideal solution in situations that require both high exposure and clear visual details.

Dataset : data_case_01.zip (file is above)

Case 2 Transfer Learning with Pre-trained CNN

Transfer Learning is very effective in overcoming the problem of training models with limited time. The use of pre-trained DenseNet models (and other models such as ResNet or ViT) allows the development of good models even in a short period of time, thanks to the ability of the models to utilise features learnt from large datasets such as ImageNet. By freezing some layers of the model, we can reduce the training time and still get very good accuracy, so this project successfully provides a fast and efficient solution for handwritten numeral classification on the MNIST dataset.
The results of this experiment show that freezing most of the layers can speed up the training, while still maintaining good accuracy. Leaving some layers trained gives the model the opportunity to optimise for more specialised features of the MNIST data.
Overall, transfer learning provides significant results in saving training time and improving model accuracy for digit classification using various advanced models such as DenseNet, ResNet, and ViT.

Case 3 Real-time Object Detection

Testing the accuracy of the YOLOv5 object detection model on three given YouTube videos. This project involves testing YOLOv5's ability to detect objects in real-time on videos with various conditions, such as changing lighting and dynamic backgrounds.
Overall, YOLOv5 is an efficient and effective object detection model, suitable for real-time applications, YOLOv5 shows excellent performance in detecting objects in video with a high degree of accuracy, so YOLOv5 is suitable for use in systems that require fast object detection in live video, but with some limitations in detecting very small or obstructed objects in video.

Case 4 Natural Language Processing - Text Classification

The main objective is to classify tweets on platform X that are related to disasters, i.e. whether the given text is a report of an emergency event. The BERT (Bidirectional Encoder Representations for Transformers) model is used to solve this problem with fine-tuning techniques.
The BERT model proved effective in handling the tweet classification task by relying on deep context understanding, which is essential for analysing texts with informal language. With fine-tuning, BERT is able to provide high accuracy in the classification of disaster-related tweets, which makes it very useful in real-time applications for disaster surveillance.

Dataset : https://docs.google.com/spreadsheets/d/1WUhiPwp36gAHK26Q9XUqzCWwdc-z9QHTPUpoZDFIFoI/edit?usp=sharing (test.csv),
          https://docs.google.com/spreadsheets/d/1X3-1Jx8QSElRKW7fYLIATef1D8C8WCJTDm01EZGGr-k/edit?usp=sharing (train.csv)
