# 17th Century American Spanish Notary Dataset

This repository contains a dataset of images from 17th century American Spanish notary documents. The dataset is organized into one directory: `images`. And a JSON file `Labeled Data` which is in JSON formate. The `images`, directory contains the actual images of the documents and the annotations for the images, and the JSON file contians all information related to the images with the contents and classes which is annotated and extracted using the labelImg software.

## Dataset Structure

- `images/`: Contains the scanned images and the xml files of 17th century American Spanish notary documents.
- `Labeled Data`: This JSON file contians all information related to the images with the contents and classes.

## Viewing Annotations

To view the annotations, you can use the labelImg software. Follow these steps to load the dataset and view the annotations:

1. Download and install [LabelImg](https://github.com/HumanSignal/labelImg).
2. Clone this repository to your local machine.
3. The main page of LabelImg will look like the image shown below. At the beginning, you have to set the directory where your images and XML files are saved. After that, you need to set the directory where changes will be saved. To view the annotations in the LabelImg software, make sure that the scanned images and their corresponding XML files are in the same directory, as organized in the images directory. The annotations will look like the image below. The bounding boxes with the green circles in the corners represent the labeling or annotation process we performed.

<img width="959" alt="Notary" src="labelimg.png">



## Sample of Rollos
Below are some sample images from rollos 40 and 38:

<img width="565" alt="rollo" src="336920977-9f40fdcc-f8ed-443b-afda-866aec771730.png">


<img width="568" alt="Rolloss" src="336921934-30880d76-b0f1-4743-8b2f-6ac0dfe22182.png">

