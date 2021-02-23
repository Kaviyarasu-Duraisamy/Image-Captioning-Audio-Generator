**Image Caption and Audio Generator**

Automatically describing the content of an image is a fundamental problem in artificial intelligence that connects computer vision and natural language processing. Being able to automatically describe the content of an image using well-formed English phrases is a very challenging task, but it could have a major impact, for example by helping visually impaired people to better understand the problem.

The project is intended to identify objects and inform people through audio and text messages. It recognizes image and converts to audio using GTTS and converts to text using LSTM. Initially, the input image is converted to a grayscale image that is processed through the Convolution Neural Network (CNN) to correctly identify the objects. Objects in the image are correctly identified using OpenCV, which is then converted to audio and text messages. The proposed method for blind people is designed to expand to people with vision loss in order to achieve their full potential.

**Conclusion**

We have implemented a CNN-RNN model by building an image caption generator. Some key points to note are that our model depends on the data, so, it cannot predict the words that are out of its vocabulary. We used a small dataset consisting of 8091 images. 

The model has been successfully trained to generate the captions as expected for the images. The caption generation has constantly been improved by fine tuning the model with different hyper parameter. Higher BLEU score indicates that the generated captions are very similar to those of the actual caption present on the images. 

In future, train on datasets larger than 100,000 images which can produce better accuracy models.
