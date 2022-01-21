# ASL-Recognition

Sign language recognition has been a popular challenge in the computer vision space. The aim of this project is to recognize and translate sign language using machine learning.

## Software Reqs

- Python
- Tensorflow
- Keras
- OpenCV
- Cuda (to run the code locally)

## Model

I first created a model from scratch and used MNIST sign language database to train it. You can find the model [here.](https://github.com/Saphilous/Machine-Learning-Models/blob/main/Exercise_4_Multi_class_classifier_Question-FINAL.ipynb)
After tuning the hyperparameters to the optimal values, the validation accuracy noted from the model is around 98-99%.
However, the model was unable to perform well with a live video feed because the images were extremely compressed. I also observed overfitting after a point.

After that model, I decided to create another one, this time with transfer learning.
In this model, I used the VGG16 model and modified it to work with my data.As you can observe, the validation accuracy is pretty good and the model is working well with video feed as well.

Then, save the model as instructed in the notebook and run the model checker notebook. You will observe that the model is indeed able to translate sign language accurately.
