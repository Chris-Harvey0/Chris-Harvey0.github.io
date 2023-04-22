# Year 3 Projects
## CSC3032 Major Project in Computer Science
### Overview
For this project I collaborated with researchers from Newcastle University and the Diego Portales University in Chile to develop a machine learning solution to assist their research The problem was that creating the large number of images needed was too slow. To solve this problem a Generative Adversarial Network (GAN) was developed to generate the images. For this I first created the training data needed to train the GAN. Next, I created the GAN, which required extensive research into relevant literature and research papers before I was able to develop a model that produced acceptable results. To improve on this research was conducted into multiple different GAN architectures which led me to choose a Deep Convolutional Generative Adversarial Network (DCGAN) as the improved solution. The DCGAN was able to produce results which were indistinguishable from the training data.
### Reflection
Overall this project was a success because a GAN was produced that can generate images similar in quality to the training images. The generated images were of a still relatively low resolution of 72x72 so future work could look at generating higher resolution images. This would likely require more than the 10,000 training images that I used for training and would require more time to train the models. Alternative GAN architectures could also be the topic of a future project. Of the alternatives I outlined in the final report I think the most promising would be to make use of NVIDIA's StyleGAN for transfer learning. StyleGAN is capable of generating high-quality high-resolution images so a transfer learning approach may allow for the same results but for this dataset.

This project allowed me to increase my knowledge of machine learning specifically with image generation as well as data science methods that were needed to process the large amount of training data.
### [CSC3032 Project Link](https://github.com/Chris-Harvey0/CSC3032-Major-Project-in-Computer-Science)

## CSC3831 Predictive Analytics, Computer Vision, Machine Learning
### Overview
This project involved completing three separate tasks involving the AddNIST and NIST datasets. The AddNIST dataset is based on the widely used NIST dataset which includes thousands of images of hand-written numbers. One AddNIST image includes three images from the NIST dataset with each image being in one of the red, green or blue colour channels. These images are layered on top of each other and the end goal of tasks two and three is to calculate the total of the numbers in each image added up minus one.
### Reflection
This was my first machine learning project, it allowed me to develop skills from using Google Colab and Keras. It also allowed me to gain knowledge of different machine learning techniques, including transfer learning and image normalisation techniques.
### [CSC3831 Project Link](https://github.com/Chris-Harvey0/CSC3831-Predictive-Analytics-Computer-Vision-Machine-Learning)


## CSC3833 Data Visualization and Visual Analytics
### Overview
This project involved using Python to visualise the data from three different datasets. The first of these datasets was the house price dataset which included categorical data. The next of these datasets was the broadband dataset which included numerical data. The final of these datasets was the financial dataset which included time series data. Plotting each of these datasets provided its own unique challenges.

In order to visualise the data the useful data first needed to be selected from the datasets. Outliers were then removed from this selected data. This data could then be plotted using matplotlib and a line of best fit was added to each graph. This required a significant amount of tweaking for each of the graphs to visualise the data in the best way possible.
### Reflection
This project allowed me to build on my visualisation and data processing skills. This allowed me to gain experience processing and visualising various data types.
### [CSC3833 Project Link](https://github.com/Chris-Harvey0/CSC3833-Data-Visualization-and-Visual-Analytics)
