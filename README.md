# harvey-image-segmentation

The project aims to solve a remote sensing problem using recent deep learning techniques. The main objective is to segment images acquired be a small UAV (sUAV) at the area on Houston, Texas. These images were acquired in order to assess the damages on residential and public properties after Hurricane Harvey. In total, there are 25 categories to segment that are provided below.

0: Background
1: Property Roof
2: Secondary Structure
3: Swimming Pool
4: Vehicle
5: Grass
6: Trees / Shrubs
7: Solar Panels
8: Chimney
9: Street Light
10: Window
11: Satellite Antenna
12: Garbage Bins
13: Trampoline
14: Road/Highway
15: Under Construction / In Progress Status
16: Power Lines & Cables
17: Water Tank / Oil Tank
18: Parking Area - Commercial
19: Sports Complex / Arena
20: Industrial Site
21: Dense Vegetation / Forest
22: Water Body
23: Flooded
24: Boat


The task is to design and implement a deep learning model in order to perform the automatic segmentation of such images. The model can be trained using the train images which contain pixel-wise annotations. Using the trained model, a prediction on the test images should be performed.

I used UNet model to perform semantic pixel wise image segmentation. While not the only possibility for Deep Learning Semantic Segmentation, a U-Net was selected as they are known to be good at image detection and segmentation problems, and train relatively quickly. I was able to achieve a best accuracy of 67\% on the test data using the trained model. One of the predictions made by the model can be seen below:

![prediction](code/6456_prediction)