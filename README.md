# Galaxy-Morphology
In this project We predicted different morphological shapes of galaxy based on the data of Galaxy-Zoo-2
<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="Screenshot 2023-09-07 014022.png" width="180">
    <br>
    <div style="color: orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;">
    </div>
</center>

## Basic 
* Used Convolutional Neural Networks(CNN) on the dataset to predict the shape of the galaxy
* Parameters for the classifying different types of galaxies was based on the reaserch paper: **Machine and Deep Learning applied to galaxy morphology - A
comparative study**
* Trained our own CNN model on the data set to get predictions as well as employed pretrained models 
* Pretrained models such as InceptionV3, ResNet50 and Xception were used on which we trained our data using Artificial Neural Network
* Different types of classification features were used classify more types of galaxies such as Lenticular, Elliptical and Spiral

 ## Results
  * The self trained model boasts an accuracy of 95.7%
  * Pretraiend Models Have Accuracy over 93% respectively <!--Har model ka alag alag daalna?-->

## Predtion By Self-Trained Model
* Loss due to inception in 10 epochs with 400 iteration with batch size 32 = 0.11
* Accuracy by inception in 10 epochs with 400 iteration with batch size 32 = 95.78%
## Prediction By InceptionV3
* Loss due to inception in 10 epochs with 400 iteration with batch size 32 = 0.15
<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="InceptionV3\Loss.png" width="180">
    <br>
    <div style="color: orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;">
    </div>
</center>


* Accuracy by inception in 10 epochs with 400 iteration with batch size 32 = 94.25%
<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);" 
    src="InceptionV3\AccIn.png" width="180">
    <br>
    <div style="color: orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;">
    </div>
</center>
## Predtion By 
