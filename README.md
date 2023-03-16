# Convolutional-Neural-Networks 
Neural networks (NN) can be introduced to bias via the environment and data on which
the network was trained or the network constraints (like parameters). White noise
analysis (i.e. the subject of this paper) protocols investigates the inherent biases that
exist within a single neuron level and the network level.
The overall goal is to train two simple NNs on MNIST and Fashion-MNIST datasets,
calculate average noise maps for each class in the datasets, determine what the model
classifies each noise map, and use the noise maps themselves as the classifier.

Currently working on a view of the activation layers within each NN for each class that perhaps will give a peak into how
the NN sees the data as it passes through the network.


Paper: https://arxiv.org/pdf/1912.12106.pdf
Paper Repo: https://github.com/aliborji/WhiteNoiseAnalysis


Q1&2 -- CNN_Models_withTraining.ipynb

Q3:

My model called "Net" trained on MNIST and Fashion-MNIST
Net_model_MNIST.ipynb
Net_Fashion_MNIST.ipynb

Model from the paper trained on MNIST and Fashion-MNIST
Model_with_MNIST.ipynb
Model_Fashion_MNIST.ipynb

Q5 Results overview:

[CNN Presentation.pptx](https://github.com/phycem/White-Noise-Analysis-of-Convolutional-Neural-Networks--MNIST--Fashion-MNIST/files/10986376/CNN.Presentation.pptx)

![image](https://user-images.githubusercontent.com/51805023/225508337-fcb39345-b828-4733-bed9-72755130a8ed.png)

![image](https://user-images.githubusercontent.com/51805023/225508197-4396bf18-8d57-464e-b30a-906a87144406.png)
![image](https://user-images.githubusercontent.com/51805023/225508366-c6ea89a8-2c92-4ed0-9753-57aea3ef73a7.png)
![image](https://user-images.githubusercontent.com/51805023/225508384-497c0ad1-c3e9-4901-b14c-5e6a6d0c87e9.png)
![image](https://user-images.githubusercontent.com/51805023/225508414-561e9dcc-79b2-4d5d-a0f7-cf69fd2a45a7.png)
![image](https://user-images.githubusercontent.com/51805023/225508434-3b4516cc-68f3-43c5-a4d6-59452c343221.png)

![image](https://user-images.githubusercontent.com/51805023/225508459-327b24b4-3cf1-486e-a7e6-eb9e23298b20.png)
