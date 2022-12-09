# Emoji_Based_HumanReactions

This Project detects the human reaction by using the CNN model and create  emoji Happy,Sad,Netural and Fearful

#**Dataset Used:**

https://www.kaggle.com/datasets/msambare/fer2013


Dataset from https://www.kaggle.com/datasets/msambare/fer2013 contains the data with data Image Properties: 48 x 48 pixels (2304 bytes) labels: 0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral The training set consists of 28,709 examples. The public test set consists of 3,589 examples. The training set consists of 28,709 examples and the public test set consists of 3,589 examples.

#**Why FER-2013 DataSet**

Fer2013 is a challenging dataset. The images are not aligned and some of them are uncorrectly labeled as we can see from the following images. Moreover, some samples do not contain faces.

![image](https://user-images.githubusercontent.com/120184924/206710424-133df609-4322-4b52-8071-33efc6b7cec3.png)
![image](https://user-images.githubusercontent.com/120184924/206710536-f4b1bb13-24e6-4324-b851-de5dada62f4e.png)

This makes the classification harder because the model have to generalize well and be robust to incorrect data. The best accuracy results obtained on this dataset, as far as I know, is 93.6% described in this paper: [Facial Expression Recognition using Convolutional Neural Networks: State of the Art, Pramerdorfer & al. 2016]


#**Libraries Used:**

1.Pandas
2.Numpy
3.CV2
4.datetime
5.Tensorflow
6.Tkinter
7.OS
8.Seaborn
9.Matplotlib

#**Steps Used For Deployment**


1.Created the Deep Learning model using Tensorflow, Keras.
2.Created sam.py and the developed Webapp using Tkinter.
3.When the program is executed it opens the webcam and detects the human face and gives the output as emoji

#**Results**

![WhatsApp Image 2022-12-07 at 9 14 12 PM](https://user-images.githubusercontent.com/120184924/206709998-829f5f1a-63b6-4647-b0c0-1cbb5843bd67.jpeg)
![WhatsApp Image 2022-12-07 at 9 11 37 PM](https://user-images.githubusercontent.com/120184924/206710004-e7ce38e6-74a4-4796-bf1a-475a492c10d0.jpeg)
![WhatsApp Image 2022-12-07 at 9 08 05 PM](https://user-images.githubusercontent.com/120184924/206710008-e0e0c3f9-5936-417e-97d3-b5e43293390f.jpeg)
![WhatsApp Image 2022-12-07 at 9 07 03 PM](https://user-images.githubusercontent.com/120184924/206710011-dd4e461f-53bb-41cf-a408-9a29c3e1de89.jpeg)



