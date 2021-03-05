# DESCIT
## Image Caption Generation
The project uses Convolution Neural Network(CNN) and Long Short Term Memory(LSTM) technique of Recurrent Neural Network(RNN) for predicting the captions for the image provided by the user through the Web App designed using Flask

### Dataset Used:- 
**Flickr8k Image Dataset (https://drive.google.com/drive/u/3/folders/1VNtUKzFWg0TFB5W3FkBOHlzX4qmmR2HA)
**Flickr8k Text Dataset (https://drive.google.com/drive/u/3/folders/1RGq8vhCVxH5TKeA7IaACjy0IXDZz8jTf)

### Construction Process:
1) We prepared a feature map of 1500 images (out of 8k){because of hardware limitation} using the ResNet50 model of Tensorflow and saved it in a feature.pickle file.
2) Flickr8k text dataset contains 5 captions for every 8092(8k) images in it. We have prepared a dictionary of all the captions with image as key and caption as value.
3) Once every image feature is attached with the corresponding keyword from the caption, we trained or LSTM model to predict the caption.

## How to install and use:
1) Clone the repo and open in Editor and change the paths
2) Run the predict.py file
3) Run flaskk.py file
4) A web app will start at localhost
5) Go to upload page and provide the image whose caption you want. Done, the model will provide you with the predicted caption.

## Structure:
<img src="https://github.com/m-s-n/DESCIT/blob/main/modelStructure.png" width="1000" heigth="100" alt="Structure of Prediction Model">

#### Versions:
1.Numpy 1.18.5
2.Pandas - 1.1.4
3.Tensorflow - 2.3.1
4.Keras - 2.4.3
5.Python - 3.7.6

## Screenshots:
<img src="https://github.com/m-s-n/DESCIT/blob/main/Results/Result12.PNG" width="300" heigth="275" alt="Race car driving on wet road with lights ON">
<img src="https://github.com/m-s-n/DESCIT/blob/main/Results/Result14.PNG" width="300" heigth="275" alt="Boy running barefoot in a parking lot">
<img src="https://github.com/m-s-n/DESCIT/blob/main/Results/Result15.PNG" width="300" heigth="275" alt="Women waering straw hat">
<img src="https://github.com/m-s-n/DESCIT/blob/main/Results/Result16.PNG" width="300" heigth="275" alt="man wearing backpack standing in a field">
<img src="https://github.com/m-s-n/DESCIT/blob/main/Results/Result18.PNG" width="300" heigth="275" alt="women kissing man in a subway">
<img src="https://github.com/m-s-n/DESCIT/blob/main/Results/Result2.PNG" width="300" heigth="275" alt="two dogs running across grassy area">
<img src="https://github.com/m-s-n/DESCIT/blob/main/Results/Result22.PNG" width="300" heigth="275" alt="three young boys making faces">
<img src="https://github.com/m-s-n/DESCIT/blob/main/Results/Result23.PNG" width="300" heigth="275" alt="a boy in red jacket does a handstand">
<img src="https://github.com/m-s-n/DESCIT/blob/main/Results/Result27.PNG" width="300" heigth="275" alt="a young girl painting a picture">

#### For more:
About any issue or construction of model or anything. Mail Mayank Singh(msn2106@gmail.com)
