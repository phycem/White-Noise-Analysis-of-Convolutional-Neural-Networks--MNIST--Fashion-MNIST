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

![image](https://user-images.githubusercontent.com/51805023/225509820-8ea6d93f-159d-4750-8558-19da57c93f08.png)

![image](https://user-images.githubusercontent.com/51805023/225509315-0e080391-aeda-491b-a31b-3a290f324def.png)

![image](https://user-images.githubusercontent.com/51805023/225509391-acd691e6-febd-42fd-89fc-56ac9063e3de.png)

![image](https://user-images.githubusercontent.com/51805023/225509449-cf41ba9e-ee59-4865-a76e-fc03ec0821c8.png)

![image](https://user-images.githubusercontent.com/51805023/225509561-9cbd5c30-3cf7-4963-8de7-2382c65c5728.png)

![image](https://user-images.githubusercontent.com/51805023/225509651-1da91393-f34d-4127-91f1-f20a8b24af36.png)

