# Image-Style-Transfer-and-Image-Classification-Using-Part-of-the-VGG19-Model-Architecture

This is my individual programming assignment 2 of COMP4211 Machine Learning in HKUST.

This programming assignment involves image style transfer, image augmentation and image classification.

The link to the Google Drive that contains all the necessary training dataset, testing dataset, image for performing style transfer, image for image classification and the pre-trained weights of VGG19 model: https://drive.google.com/drive/folders/1_5LoxbmWDKPKi91Z_HmQn4TFoTtXnxQM?usp=sharing

You should see the following things:

* pa2.pdf: the instruction for this programming assignment
* report.pdf: the report for this programming assignment
* code.ipynb: the Jupyter Notebook of this programming assignment
* code.zip: a zip file contains the Jupyter Notebook
* code: a folder contains the extracted content from the code.zip file
* COMP4211_PA2_CLASSIFICATION: a folder that contains the augmented images (derived-files) and the tsv file that contains the filename of the augmented images (derived-data.tsv)
* COMP4211_dataset: a folder that contains all the necessary training dataset, testing dataset, images for performing style transfer, images for image classification and the pre-trained weights of VGG19 model
* saved.h5: a file that contains the weights of the model for image style transfer
* classify.h5: a file that contains the weights of the model for image classification (before adding augmented images as part of the training dataset)
* classify-augmentation.h5: a file that contains the weights of the model for image classification (after adding augmented images as part of the training dataset)

## How to run?

1. Download and put all the files to the same folder in Google Colaboratory
2. Adjust the file paths inside the Jupyter Notebook if necessary
3. Run all the codes
