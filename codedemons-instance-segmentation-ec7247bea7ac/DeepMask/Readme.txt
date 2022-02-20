The above file contains the implentation of Deepmask for instance segmentations on Coco dataset.
The dataset can be downloaded from the following link http://cocodataset.org/#download
Download the dataset and zip it and move them to a folder named coco , such that your directory structure looks like /coco/images/ -containing the images and 
/coco/annotations/instances_{year}.json -containing the annotations.

The class data() contains the implementation of data preparaton ie. reading the annotations from the json file and geneating masks for the images
The backbone CNN model used here is VGG16 

