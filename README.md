# Cat-vs-Dog-Classification

## Context
The Dogs vs. Cats dataset is a standard computer vision dataset that involves classifying photos as either containing a dog or cat.
This dataset is provided as a subset of photos from a much larger dataset of 3 million manually annotated photos.
The dataset was developed as a partnership between Petfinder.com and Microsoft.

## Cat and dog classification using CNN
Convolutional Neural Network (CNN) is an algorithm taking an image as input then assigning weights and biases to all the aspects of an image and thus differentiates one from the other. Neural networks can be trained by using batches of images, each of them having a label to identify the real nature of the image (cat or dog here). A batch can contain few tenths to hundreds of images. For each and every image, the network prediction is compared with the corresponding existing label, and the distance between network prediction and the truth is evaluated for the whole batch. Then, the network parameters are modified to minimize the distance and thus the prediction capability of the network is increased. The training process continues for every batch similarly.

## Model Training and Plotting

Training Loss and Validation loss Graph
![image](https://user-images.githubusercontent.com/92180055/191440563-d3f1f7c4-8f96-4f10-bff7-770c04b19abf.png)

## Predictions

![image](https://user-images.githubusercontent.com/92180055/191441659-0cf86be9-361a-4a33-bc94-bc359df53c8b.png)

![image](https://user-images.githubusercontent.com/92180055/191441870-fccd6eba-65b9-4fee-8fd3-e26b73650ddd.png)
