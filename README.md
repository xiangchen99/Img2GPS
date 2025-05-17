# Img2GPS Project

This project determines the location of the camera, based on the image that is inputted around Penn Engineer's campus. Neural network model was trained on self collected and self-cleaned data.

# Facts about the project

 - 1000+ self-collected images around campus (dataset and model link : https://huggingface.co/datasets/xiangc21/5190projecttrain/tree/main)
 - EXIF geographic data was collected from the images as training labels
 - 70-30 train-test split
 - Image preprocessing was done to improve generalization and lower overfitting (ex. rotations and resizing)
 - Model was done with transfer learning from ResNet-50 + additional dropout and normalization layers

