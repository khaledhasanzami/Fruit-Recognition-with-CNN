# Fruit Recognition with Convolutional neural network (CNN)

## Data

**Dataset:** 
 - The dataset used in the project is named [Fruits-360](https://github.com/Horea94/Fruit-Images-Dataset) which is about 405 MB.
 - The dataset is downloaed from [Fruit-Images-Dataset](https://github.com/Horea94/Fruit-Images-Dataset) [Accessed:9, August, 2019].

**Dataset properties:** 
 - Total number of images: 55,199.
 - Training set size: 41322 images (one fruit per image).
 - Test set size: 13877 images (one fruit per image).
 - Multi-fruits set size: 45 images (more than one fruit (or fruit class) per image)
 - Number of classes: 81 (fruits).
 - Image size: 100x100 pixels.
 - Filename format: image_index_100.jpg (e.g. 32_100.jpg) or r_image_index_100.jpg (e.g. r_32_100.jpg) or r2_image_index_100.jpg or r3_image_index_100.jpg. "r" stands for rotated fruit. "r2" means that the fruit was rotated around the 3rd axis. "100" comes from image size (100x100 pixels).
 - Different varieties of the same fruit (apple for instance) are stored as belonging to different classes.

**File type:** 
 - The dataset contains images in jpg format. 
 - Folders Training and Test contain images for training and testing purposes.
 - Folder test-multiple_fruits contains images with multiple fruits. Some of them are partially covered by other fruits. This is an excelent test for real-world detection.
## Files
There are 5 types of files in the repository:
 - Fruit_checked.ipynb is the full version of the code used for this analysis
 - readme.md explains the repository
 - Figure directory containes all the figure produced in the analysis
 - Fruits-360.zip is the dataset used in the project
 - Fruit_model_weight.h5 is the developed model

 **Re-creating the project:**
  - In order to perform the analysis step by step please go for the Fruit_checked.ipynb file.
  - The same analysis can be done in many other ways yet reach the same results. This one is the easiest of the forms possible in my knowledge.
