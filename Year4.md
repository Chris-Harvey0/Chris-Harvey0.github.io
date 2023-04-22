# Year 4 Projects
## CSC8101 Engineering for AI
### Overview
This project was split into two parts; an Azure Databricks component and a Neo4j component. Both of these parts involved a dataset of taxi trips which we needed to perform certain operations on in order to make some findings from the data.
### Reflection
I had not used Azure Databricks or Neo4j previously so this project allowed me to gain experience with a couple of new tools. The Azure Databricks part of this project allowed me to gain a better understanding of what operations scale well across large datasets. Through the use of Neo4j I have increased my knowledge of graph databases and the advantages and disadvantages they have over relational databases.
### [CSC8101 Project Link](https://github.com/Chris-Harvey0/CSC8101-Engineering-for-AI)

## CSC8106 System Evaluation
### Overview
For this project we were provided with a set of research papers that had each used the modelling language PEPA to model something. The main goal of this project was to replicate the results of the chosen research paper and then to modify the model in order to make further findings. From the available papers I chose a paper that had used PEPA to model patient flow through a hospital. The modification I decided to make was to model patient flow through a Covid ward in a hospital. For this I researched real statistics and used these to inform the development of the modified model.

I decided to create two separate models for this project because the two elements I wanted to model were on very different time scales. The first element was the patient admittance to the Covid ward which would be modelled over a matter of hours. The second element was the patient recovery in the Covid ward which would be modelled over weeks so separate models were required.
### Reflection
This project allowed me to gain experience in performance evaluation using modelling which was not something I had used before. I was very pleased with the two models I created for this project and the modification of the original model that they were based on. This was reflected by the mark of 85/100 which I received for this project.
### [CSC8106 Project Link](https://github.com/Chris-Harvey0/CSC8106-System-Evaluation)

## CSC8110 Cloud Computing
### Overview
The main goal of this project was to deply a Docker-based application hosting environment, as well as programming and deploying cloud infrastructure using Terraform.
### Reflection
This project gave me experience in cloud computing which is an area of computing I had not made a project in before. It allowed me to build on my knowledge of Docker which I had used previously in my [Internet of Things project](https://github.com/Chris-Harvey0/CSC8112-Internet-of-Things). I had not used Azure Kubernetes Services or Terraform previously and found these tools took some getting used to. The main issue I encountered was with giving Terraform the correct permissions to create clusters on Azure. I explored the possible options that could be used and the differences between system assigned and user assigned managed identities. I decided that system assigned would be the simpler solution and implemented this. In future projects I would like to make more use of cloud as this was a relatively simple introduction to cloud computing.
### [CSC8110 Project Link](https://github.com/Chris-Harvey0/CSC8110-Cloud-Computing)

## CSC8111 Machine Learning
### Overview
This project involved picking two datasets from the available four. The task was then to develop machine learning pipelines for the picked datasets and to compare results. I picked the image dataset CIFARTile, and the text dataset of Tweets to airline companies.
### Reflection
In this project I developed machine learning models for two different datasets. The model for the Tweets dataset managed to obtain relatively good results of 78%. However, for the image dataset 53% was the maximum accuracy obtained. I was still very happy with this accuracy as it beat the average accuracy from the machine learning competition it was used for. For future work I would aim to improve this accuracy by using various image augmentation techniques to improve accuracy further.
### [CSC8111 Project Link](https://github.com/Chris-Harvey0/CSC8111-Machine-Learning)

## CSC8112 Internet of Things
### Overview
This project makes use of data from Newcastle Universities Urban Observatory. The main goal of this project was to develop a data pipeline from an edge device (sensor) to the cloud.

Edge Device 1 --> EMQX --> Edge Device 2 --> RabbitMQ --> Cloud
### Reflection
This project allowed me to gain a better understanding of how IoT devices work. Through the development of an IoT pipeline for this project I used two different popular message queueing methods. I managed to implement both of these well and didn't have any message losses in the finished program. For future work I would attempt to test this pipeline further to find out how robust it really is. This would allow me to assess whether it would be capable of coping with a real-world workload.
### [CSC8112 Project Link](https://github.com/Chris-Harvey0/CSC8112-Internet-of-Things)
