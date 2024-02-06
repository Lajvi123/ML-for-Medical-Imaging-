## COVID 19 detection from XRAY using Machine Learning
![Project Image](https://media.licdn.com/dms/image/C4D12AQEskcOH6Uldng/article-cover_image-shrink_423_752/0/1531990007400?e=1702512000&v=beta&t=i_NniTE-OA-KXrRgazElhtQ8Ku6qHGtLQkQ9I3Z2r-0)
## INTRODUCTION
This project presents a comprehensive framework employing Machine Learning techniques on chest X-ray images, aiming to facilitate early detection of respiratory diseases. The primary focus involves the application of Convolutional Neural Networks (CNN) and supervised learning classification methods for chest X-ray image recognition.
## INSTALL
This project requires Python and the following Python libraries installed:
* [PyTorch](https://pytorch.org/)
* [Pandas](https://pandas.pydata.org/)
* [torchvision](https://pypi.org/project/torchvision/)
* [Seaborn](https://seaborn.pydata.org/)
* [matplotlib](https://matplotlib.org/)
* [Keras](https://keras.io/)
* [Scikit-learn](https://scikit-learn.org/stable/install.html)
## DATASETS
* The dataset utilized in this project is sourced from Kaggle and can be found [here](https://www.kaggle.com/datasets/prashant268/chest-xray-covid19-pneumonia/data).
* It includes X-ray images of the chest, with training and testing datasets, each containing three subdirectories: ['covid', 'viral pneumonia', 'normal'].

## PROPOSED METHODOLOGY 
The project is divided into following stages: 
* Data Acquisition from online resources. 
* Divide the whole dataset into training and testing datasets.
* Data Augmentation on datasets.
* Prepare DataLoader to simplifies the process of loading batches of data during training and evaluation.
* Use PyTorch's torchvision library to load the ResNet 18.
* Hypertune the ResNet 18 model and evaluate the model on dataset.
## CODE
Code is available [here]{
