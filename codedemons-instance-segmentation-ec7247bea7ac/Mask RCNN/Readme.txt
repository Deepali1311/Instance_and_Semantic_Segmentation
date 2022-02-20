The above file contains the implentation of mask rcnn for instance segmentations on Indian Driving Dataset.
The dataset can be downloaded from the following link https://idd.insaan.iiit.ac.in/accounts/login/?next=/dataset/download/
The annaotations in the dataset is a json file for each image containig the image details and mask coordinates. In the code , the class anno() of contains the implementation of data preparation.The mask coordinates are exxtracted from the json for each image and are used to generate the bounding boxes for the masks
The Data Pre-processing must be done because all the images in the datasets are not of same resolution( scaling, resizing, etc. of the images)
The backbone CNN model used here is Resnet50 integrated with FPN

