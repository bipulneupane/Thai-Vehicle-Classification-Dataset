# Thai-Vehicle-Classification-Dataset
This is a vehicle classification dataset that includes the training samples of Thai vehicles. The dataset is prepared with support from the road maintenance unit under the Department of Rural Roads (DRR) of Thailand. The dataset is prepared by sampling image frames from 6.3 TB of surveillance videos, that are taken from 23 cameras for 3 continuous days from 25th to 27th June of 2020. The image frames are also selected such that the dataset includes vehicle samples at different times in a day and different locations to vary the environment settings in the dataset.

The labels are created using a labelling tool (https://github.com/tzutalin/labelImg). Seven classes of vehicles including car, bus, taxi, bike, pickup, truck, and trailer are manually annotated in YOLO (txt) format. As the sample of buses was not enough, we added 4431 samples of buses from an open dataset provided by the authors in the paper:

Song, H., Liang, H., Li, H. et al. Vision-based vehicle detection and counting system using deep learning in highway scenes. Eur. Transp. Res. Rev. 11, 51 (2019). https://doi.org/10.1186/s12544-019-0390-4

The number of samples per class are:
1. Car      10478
2. Bus      540+4431
3. Taxi     1605
4. Bike     2572
5. Pickup   6056
6. Truck    2656
7. Trailer  1179
Total:      29474

![alt text](samples.jpg?raw=true)

Out of these total samples, 80%, 15%, and 5% were taken as train, validation, and test dataset respectively. The folders are set up accordingly, each of them having both images and labels. The dataset is ready to be trained on YOLO models. The terms and conditions of using the dataset are to acknowledge and cite the following paper:

Neupane B, Horanont T, Aryal J. Real-Time Vehicle Classification and Tracking Using a Transfer Learning-Improved Deep Learning Network. Sensors. 2022; 22(10):3813. https://doi.org/10.3390/s22103813 

[Link to the paper](https://www.mdpi.com/1424-8220/22/10/3813)

[Link to the dataset](https://drive.google.com/file/d/1v8a8IzCK-l7c89cuT9ChozlEqEsxjymP/view?usp=drive_link)

Apologies that the link to the dataset was not working for some (unknown) period of time because of server failure. The link to the dataset is working again from 1 October 2023.
