# Signature-Forgery-Detection-with-Forger-Detection-Using-CNN
## Introduction
A signature can be defined as a unique mark which is a handwritten representation an individual creates in order to authenticate any written records. When an individual signs a document it means that the individual is giving their consent, approval and agreement after studying the whole document when he/she is mentally sound.

Now a days signatures are loosing their authenticity due to the rise of forgery. Signature forgery is a process that involves the unauthorized imitation of an individual's signature in order to deceive others into believing it is genuine.

To check if a signature is forged or real they perform a manual comparision check between all the previous original signatures and the one to be checked. The manual check consumes a lot of time and there are less specialists in this field. In order to overcome this we can use deep learning model namely CNN which on providing data extracts the features from the signature and compares and provides results. Here deep learning is used because it learns itself by looking at the features and the data input is given in the form of image of the signature.
## Project Description
As the title suggests this project is about signature forgery detection along with an add-on of who might have done the forgery. Here a Convolution neural network is used to find if the input signature image is forged or real, but since CNN alone is unable to give good accuracy we used the technique of "Transfer learning". It involves taking a pre-trained model and adapting it to a new, related task. 

After detecting if the signature is forged or real we perform an additional task which is finding out the forger. In order to this we have used the technique of CNN.

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
The dataset used here is a new one prepared from scratch by referring to previously existing ones.The dataset contains signatures of 10 different users. The link to the datasets used are :
1. https://drive.google.com/drive/folders/1pyfxvBr-ESRezjLlSLwBUZUVlI43OjxQ?usp=sharing
2. https://drive.google.com/drive/folders/1-VaD7tTSoCPnl4Nq3wqailZbmn0RFq7y?usp=sharing

All the users were asked to sign their original signature 10 times on one side of an A4 sheet and try to forge the other 9 users signatures on the other side. After colleting the signatures from all users the sheets were scanned and each signature is cropped and stored.
For first CNN model we haev two classes namely forge and real so the data is arranged into these two folders.
For second CNN model we have 10 classes i.e 10 users so we arrange only the forged signatures into 10 folders.  

## Installation Steps
The project is doen in a Google Colab notebook using python there are not many installatio steps since Colab provides a cloud-based environment with pre-installed libraries. 
1. To open the project in colab:
https://colab.research.google.com/drive/1FmDhuHPIf1CeDA1noWcdx-ycox0YYYOo?usp=sharing
2. To access the datasets use the above links.
3. To mount the Google Drive(where the datasets are stored) use:<br>
from google.colab import drive<br>
drive.mount('/content/drive')<br>
5. New datasets can be given to the model but the class names should match in the dataset and code.

## Project roadmap
1. Importing the libraries
2. Setting the path to the dataset
3. Preprocessing, extracting images and dividing into test, train and validation
4. CNN model to identify if forged or real
5. Transfer learning and prediction accuracy calculation
6. Trail on an image
7. For next process i.e identifying the forger we follow the same steps but for 10 classes
8. Additionally we plot the accuracy graph for visualization

## Project Status
The original goal of the project has been achieved but there are further improvements to be added and there can be further extension of this project like considering the age factor while checking for forgery. So it can be said that it is in development state.

## Support Information
For support or any issue while running the model try asking on Stackoverflow.

## Acknowledgements
Special thanks to my professor Dr. Arka Prokash Mazumdar who guided me through this whole project by helping me build the dataset from scratch and by taking regular sessions for improving the model.

I would like to express my gratitude to the following project and resources that have greatly influenced or contributed to this work:<br>
https://medium.com/swlh/signet-detecting-signature-similarity-using-machine-learning-deep-learning-is-this-the-end-of-1a6bdc76b04b<br>
https://github.com/aaditkapoor/SigNet

Thanks to all the prior work that helped me improve my knowledge in this area, below are the IEEE research papers link:<br>
https://ieeexplore.ieee.org/abstract/document/6195358/citations#citations   (2012)<br>
https://www.ijarst.in/public/uploads/paper/877041684826373.pdf  (CNN vs SVM)<br>
https://www.sciencedirect.com/science/article/pii/S1877050920305731 (2020)<br>
https://ieeexplore.ieee.org/abstract/document/6981091 (2014) recent advances<br>
https://ieeexplore.ieee.org/abstract/document/10298632 (2023)<br>
https://ieeexplore.ieee.org/abstract/document/9087524 (extension)<br>









