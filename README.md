# #Problem Statement:

Can you differentiate a weed from a crop plant in an agricultural field? The ability to do so effectively
can mean better crop yields and better stewardship of the environment. Food is an essential necessity of
human life and requires its continuous supply and production to cater the needs of the growing
population through sustainable agriculture. This can be achieved with the application of emerging
technologies in the sector to maximize production across a vegetation. Technology can aid/improve
agriculture in several ways through pre-planning and post-harvest by the use of deep learning
techniques through image processing to determine the soil nutrient composition, right amount, right
time, right place application of farm input resources like fertilizers, herbicides, water, weed detection,
early detection of pest and diseases etc.

In this project, we trained a Convolutional Neural Network (CNN) Model using the Keras deep
learning library. We prepared and obrained our datasets from Hare Krishna Farms, Noida and
PlantVillage, a research and development unit of Penn State University, US for weed
classification and disease identification respectively.

In particular, our datasets consists of 1108 images for weed plants and tomato crop for first
dataset and 20,654 images of 15 separate classes namely 'Pepper_bell_Bacterial_spot' ,
'Pepper__bell___healthy', 'Potato_Early_blight' 'Potato_Late_blight' , 'Potato_healthy',
'Tomato_Bacterial_spot', 'Tomato_Early_blight' , 'Tomato_Late_blight', 'Tomato_Leaf_Mold' ,
'Tomato_Septoria_leaf_spot', 'Tomato_Spider_mites_Two_spotted_spider_mite' ,
'Tomato__Target_Spot', 'Tomato_healthy', 'Tomato_Tomato_Yellow_Leaf_Curl_Virus' ,
'Tomato_Tomato_mosaic_virus', for disease data-set.

Using our Convolutional Neural Network and Keras, we were able to obtain 97.81 and 98.82%
accuracy, which is quite respectable given the limited size of our first dataset and the number of
classess in our disease dataset respectively.
