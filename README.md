# PLANT-DISEASE-DETECTION-WITH-KERAS


## ABSTRACT

Diseases are natural events that can have significant impacts on plants, reducing productivity, quality, and quantity of products. The leaf is the most important component of the plant to inspect for plant diseases. For the purpose of avoiding agricultural losses, accurate leaf disease detection and classification are essential. Different plant leaves transmit various illnesses.
Visual monitoring is a difficult and time-consuming method for detecting plant diseases.

## Proposed Method

The proposed system aims to develop a software solution to identify and classify plant leaf diseases with high accuracy and clarity. The identification of different types of plant species was examined. Various steps of image processing needed to apply on the video frames before it can identify the diseased plant. In this module the detection model detects the type of plant disease. Before training all the images are preprocessed. Images are extracted from video frames  This image is then passed onto the model then classifies the type of disease Another key contribution of the proposed system includes most of the real-world challenges of the plant illness diseases detection and classification .The dataset collection and experimentation on these datasets are other major benefits of the proposed work.


## Flow Chart
![a](https://user-images.githubusercontent.com/53647653/205476372-2d5510fb-eefe-40c2-9bab-6af55e71e1de.png)


## METHODOLOGY

### MODULE DESCRIPTION:

* Image acquisition : In this we can take an image of the leaf directly or from the open source platform & uploading it will analyze the image.

* Image pre-processing : It analyzes the image that has been uploaded completely & provides the information about the image whether it is affected or not. 

* Convolutional neural network : CNN is one of the subdomains of machine learning which also performs deep learning algorithms. It helps in the classification and detection of disease of a plant; actually CNN is done by filtering image pixels .

* Feature extraction : In this it will extract the disease information (Corn common rust,potato early blight,tomato bacterial spot) from the data collection & provides more information about the disease and also suggest the suitable pesticides for curing the crop from the disease.

* Classification : In this we get the complete percentage of the disease affected to the crop and also it provides the suitable pesticides for the disease that occur to the crop.

### Steps :

* Data Collection and Loading:
The data set that is required for this project is imported from the kaggel website. 
This contains 3 classes of 300 images each
Using collab load all the data into tensorflow.

 * Data Visualization: 
Use Matplotlib for data visualization

![a](https://user-images.githubusercontent.com/53647653/205476488-0249af45-ff3a-4b14-bd44-0e7a21578d76.png)

* Data Preprocessing:
The entire set of data is normalized before being split.

* Split the dataset 
Use sklearn and split the dataset -> 80% for training and 20% for testing.

* Build and train model

Use tensorflow in building a sequential model 

Train our model on 10 epochs and a batch size of 128.

![a](https://user-images.githubusercontent.com/53647653/205477028-3fb6e212-b30b-45cb-baa7-350b9a98bf8f.png)


* EPOCH: 

Epoch is once all images are processed one time individually  forward and backward to the network, then that is one epoch.
During each epoch we can see how the model is performing by viewing the training and validation accuracy.



* Plot training history

![a](https://user-images.githubusercontent.com/53647653/205476823-ddec72b4-4275-4b62-ab2e-0e4914ecee08.png)

* Load Model into script
* Load model into script 
* Using  streamlit host a local server where user can upload a video of plants to be tested

## IMPLEMENTATION 

* RUN SCRIPT IN CMD USING FOLLOWING COMMAND
  streamlit run filename.py 
 
![a](https://user-images.githubusercontent.com/53647653/205476868-b4af93e7-acf4-451b-af91-67beef37fdd8.png)

*  OUTPUT OF LOCAL SERVER 

![a](https://user-images.githubusercontent.com/53647653/205476898-c47f2790-c709-44ef-9138-8392f9acaf75.png)


## RESULT AND DISCUSSION

![a](https://user-images.githubusercontent.com/53647653/205476916-52e0d864-a0d3-4dfd-a0f9-ebe4552c8387.png)
* From the video uploaded from the user images are extracted and that plant image  disease  is  predicted. 
* Frames are generated from video using opencv.

![a](https://user-images.githubusercontent.com/53647653/205476943-00354857-5733-4a5a-b1ea-ac97ec0c3a3b.png)

* 11 frames are generated from one video uploaded by user

## CONCLUSION:

* Human life is completely dependent on nature and plants. Therefore, there must be special ways to save plants from diseases. This project focuses on diagnostic plant leaf diseases; The primary goal is to detect the type of disease.

* With this farmers can get good yield which impacts economic development by contributing to the overall U.S. gross domestic product (GDP), directly and indirectly. 

* Farmers can be rescued from huge losses.

* It impacts the agriculture sector and trading sector in our country.

## FUTURE SCOPE:

* In Future other crop diseases can be trained.

* Mobile Application can be developed and made available free on the Google play store.

* Pesticides can be suggested according to disease type.

* Can monitor the whole farm using drone or camera according to availability. 

![a](https://user-images.githubusercontent.com/53647653/205476994-57f3ca39-30b7-462e-9afa-359c703c659f.png)
