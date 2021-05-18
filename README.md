# hair-seg
Image segmentation is one of the key problems in machine learning and computer vision. Many real-life applications require high quality and efficient hair segmentation approaches, i.e., human identification and beautification. In assignment 3, we will build deep learning models for Hair Segmentation.

# Examples

## Training Data
* Our training data is a mask of the original of the input with the hair detailed as the white pixels as denoted below. As you may have noticed, even facial hair are classified as hair as they should be. So this added complexity may help with things like facial recognition because the model can recognize the similar face structure minus the facial hair. Though of course more details would need to be extracted for that to work.

![Training Data](https://github.com/ptonydb/hair-seg/blob/main/image_hairmask.jpg?raw=true)

## Data Augmentation and Detail Extraction
* A variety of methods was used to emulate a larger data set as shown in the example below.
![Data Augmented Implementation](https://github.com/ptonydb/hair-seg/blob/main/image_hair_skin_mask.jpg?raw=true)

## Validation Results
![Validation Results](https://github.com/ptonydb/hair-seg/blob/main/examples-segmentation.png?raw=true)
