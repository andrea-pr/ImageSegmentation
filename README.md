# READ ME

This project aims to predict the pixels that correspond to roofs from satellite pictures. The data set contains 30 satellite pictures of houses and 25 corresponding labels which indicate the roofs. <br /> For the segmentation model a UNet with ResNet50 as Encoder and pretrained ImageNet weights was used. <br /> As loss function the dice loss was applied. 