# waffle macaron classification

## 0. requirements

    graphviz 2.38  
    jupyter 1.0.0  
    keras 2.2.4
    matplotlib 3.3.4  
    notebook 6.3.0  
    numpy 1.20.1  
    opencv-python 4.5.2.52  
    pandas 1.2.4  
    python-graphviz 0.16  
    python 3.9.4  
    scikit-learn 0.24.1  
    anaconda 3

## 1. data collection

    21 class 음식 images 1000장 data collection (kaggle)
   
    waffle, macaron 2 class selection
   
## 2. data analysis & preprocessing

    다양한 형태의 image data, size, byte 다름
   
    color 3channel, gray scale

    image size resize (50 x 50)
   
    data split - train data, test data
   
    image flatten
   
    histogram
    
## 3. datasets

    train - 800 images, 2 classes
    
    test - 200 images, 2 classes

## 4. model selection & training

    sgd classifier
   
    svm (poly, rbf(radial basis function)(gaussian), sigmoid)

    decision tree classifier

    multi layer perceptron
   
    validation, voting, adam, precision, recall
