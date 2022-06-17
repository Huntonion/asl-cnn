### project for the Context Aware Security Analytics in Computer Vision class @unisa

 This project is aimed at training a convolutional Neural Network in order to classify the american sign language fingerspelling. The pictures used on this project were downloaded on kaggle.com. The dataset consists of 87000 pictures for the training set but just a mere 29 pictures for the test set, therefore some pictures were taken personally to be used in the test set, specifically, 3 picture for each class were taken. An accuracy of 99.9% was achieved both during training and validation. The model was trained on a Macbook Air with apple silicon (M1) processor.
 
 ### How to run
 
```
git clone https://github.com/Huntonion/CASA-2021-2022
```
download the dataset from https://www.kaggle.com/datasets/grassknoted/asl-alphabet and extract the archive into the ```CASA-2021-2022``` folder.
then run:
```
pip install -r requirements.txt
jupyter lab model.ipynb
```
if you are interested in knowing more about this project, please consider reading the [paper](https://github.com/Huntonion/CASA-2021-2022/blob/main/paper.pdf) produced.
