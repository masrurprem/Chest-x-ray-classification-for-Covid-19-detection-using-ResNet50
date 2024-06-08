# Chest-x-ray-classification-for-Covid-19-detection-using-ResNet50
in this project, A pretrained Resnet50 model has been employed for chest x-ray image classification for detecting Covid-19. The dataset was downloaded from kaggle having 21,000 chest x-ray images and corresponding masks. Of them, 1800 images were taken randomly of 3 classes: covid, normal, and viral pneumonia. Each class contains 500 images for training and 100 images for testing per class. 


## Model performance
The model was trained for 25 epochs yielding training accuracy of 70% and validation accuracy of 62% (since only 1500 were used during training). The testing accuracy on 300 images was 49%. This is very low but can be highly improved by introducing more data and leveraging advanced computer vision and tuning techniques. 
