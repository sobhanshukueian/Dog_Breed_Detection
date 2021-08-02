# Dog_Breed_Detection
This project implements Dog Breed Detection using Transfer Learning in Python and Tensorflow

# Introduction 
Transfer or inductive learning is a supervised learning technique that reuses parts of a previously trained model on a new network tasked for a different but similar problem. 
A pre-trained model is a saved network that was previously trained on a large dataset, typically on a large-scale image-classification task. You either use the pretrained model as is or use transfer learning to customize this model to a given task.
You can use Tensorflow hub which is a repository of pre-trained models, in this project we use one of that models (imagenet/mobilenet_v2_130_224/classification/4) then train it with our dog breed dataset.

# DataSet
Dog breed identification dataset is composed of 120 classes and 10222 RGB images of dog breed.First of all, we need to prepare our labels and convert them to an array of booleans then we reach data preprocessing in this section first split our data to train and validation sets then turn them into batches, and finally convert our images to tensors 

# Some Samples
![download (4)](https://user-images.githubusercontent.com/47561760/127821042-fd533048-3e75-418f-b998-5b273efce673.png)






