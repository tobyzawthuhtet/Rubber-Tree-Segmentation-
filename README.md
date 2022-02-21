# Rubber Tree Segmentaion Project


</br>

# Problem statment
Abundant amount of deforestations are being occured in all corner of the world regardless of region politics,economy and standard of living. Numerous efforts have been put into montioring forest cover from time to time and Rubber trees were amongst one of the factor contributing to deforestation.

Here is an attempt to identify where the rubber trees may lies in satellite imagery and segment it.

This project aims to help beginners in both Geospatial technology and deep learning to understand and work out a particular segmentation project on their own.

Humbly published this repo in pursuits of trying our utmost to be a great lift for Myanmar Geoinformatic and Machine learning society. Since both contributors were still at their grittiest learning phase, sincere apologies are delivered if any mistakes or inconveiences are encountered.


## Utils
- image_utils.py (used for image preprocessing and postprocessing)

## For those who would like to use our model, please go through 
- notebook/Unet_model_for_rubber_segmentation.ipynb 

## Weights
- Pretrained weights can be seen under weights folder

## Sample Predictions
 <img src="/Inference%20Resutlts/1.Inference.jpg" width="550" height="200" hspace="50"> 
 
 <img src="/Inference%20Resutlts/1.Predict.png" width="550" height="200" hspace="50"> 
 
## Datasets

Datasets used in our training process can be found under this folder. Labelme annotation is used to produce binary mask file.

<p>Bianry mask images can be exported from labelme json format using the following syntax: </p> <br> 

> <code> labelme_json_to_dataset Dawei_rubber.json -o Labelme_Output_data </code>
