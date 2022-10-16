# car-brand-detector
Final project for Data Science bootcamp organized by Sages

**Important:**

To run this project it is necessary to download dataset from Stanford University page - https://ai.stanford.edu/~jkrause/cars/car_dataset.html.

After downloading tar file of all images (section Download -> Update), please unpack all images and store them in *dataset_original/car_ims* so the directory looks as follows:


<div style="padding-left: 30px;">
    
    - dataset_original/
        -car_ims/
            *all images should be stored here*
        - cars_annos.mat
</div>

*cars_annos.mat* file is already provided in this repository.

Please use Python 3.9 or higher version. Install libaries from requirements.txt

## Quick overview

The project goal is to classify a brand of car based on its image. To build a model, the transfer learning method will be used. Pretrained models that are taken into consideration in this project are as follows:
* ResNet50
* InceptionV3
* MobileNetV2
* VGG19

Moreover, some necessary changes will be applied to top layers of pretrained models to match the requirements of specific dataset. Later on, fine-tuning will be used, to improve models that have the most potential.

Example of prediction on a sample

![image](https://user-images.githubusercontent.com/89789708/196061066-1b164caf-85d3-4e8b-a534-3e7da6b76f51.png)

