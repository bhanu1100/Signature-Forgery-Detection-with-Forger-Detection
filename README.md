# Signature-Forgery-Detection-with-Forger-Detection-Using-CNN
## Introduction
A signature can be defined as a unique mark which is a handwritten representation an individual creates in order to authenticate any written records. When an individual signs a document it means that the individual is giving their consent, approval and agreement after studying the whole document when he/she is mentally sound.

Now a days signatures are loosing their authenticity due to the rise of forgery. Signature forgery is a process that involves the unauthorized imitation of an individual's signature in order to deceive others into believing it is genuine.

To check if a signature is forged or real they perform a manual comparision check between all the previous original signatures and the one to be checked. The manual check consumes a lot of time and there are less specialists in this field. In order to overcome this we can use deep learning model namely CNN which on providing data extracts the features from the signature and compares and provides results. Here deep learning is used because it learns itself by looking at the features and the data input is given in the form of image of the signature.
## Project Description
As the title suggests this project is about signature forgery detection along with an add-on of who might have done the forgery. Here a Convolution neural network is used to find if the input signature image is forged or real, but since CNN alone is unable to give good accuracy we used the technique of "Transfer learning". It involves taking a pre-trained model and adapting it to a new, related task. 

After detecting if the signature is forged or real we perform an additional task which is finding out the forger. In order to this also we have used the same technique of CNN with transfer learning.

## Software and Hardware Requirements: 
1. Programming language: Python
2. Environment: Google colab
3. Machine learning libraries: tensorflow, sklearn 
4. Data manipulation libraries: numpy
5. Data visualization libraries: matplotlib
6. Dataset (Description and link given below)
7. Hardware accelerator: CPU (Google colab)
8. Runtime type: Python 3 (Google colab)

## Dataset
The dataset used here is a new one prepared from scratch by referring to previously existing ones. The link to the datasets used are :
1. https://drive.google.com/drive/folders/1pyfxvBr-ESRezjLlSLwBUZUVlI43OjxQ?usp=sharing
2. https://drive.google.com/drive/folders/1-VaD7tTSoCPnl4Nq3wqailZbmn0RFq7y?usp=sharing



