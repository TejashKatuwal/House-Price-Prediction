# House-Price-Prediction
# Importing the Dataset
First import necessary libraries like panda and numpy. Then download the train.csv file in the repo and upload it to your drive and import it to your colab notebook using the code shown below and display using pandas.
![importing](https://github.com/TejashKatuwal/House-Price-Prediction/assets/118622724/58f3cb48-cf7c-424f-b6a5-4be2436ec16c)

# Data Pre Processing
Whenever we get the dataset the first thing we do is check for  null values as shown in the figure. After that we remove all the unnecessary columns to reduce the size of datset and make our work easier.
![processing-1](https://github.com/TejashKatuwal/House-Price-Prediction/assets/118622724/8e82af71-f16f-4b6b-8678-2a25be7aacbc)

Now we check what percent of datas are null values. Here we check the null values using seaborn.
![processing-2](https://github.com/TejashKatuwal/House-Price-Prediction/assets/118622724/46ba2059-1b0a-4d7d-9717-a54aef0d2667)

If the null values percentage is relatively low we fill the null values using either median or mean. We check for outliers to decide either to use median or mean.If there are outliers we fill using median or else we use mean values.
![processing-3](https://github.com/TejashKatuwal/House-Price-Prediction/assets/118622724/e1942846-e5c3-4b01-b691-dcf387d67962)

Now if certain columns has string as indicators we need to convert them into integers, here we use label encoder to do so as shown in the code.
![processing-4](https://github.com/TejashKatuwal/House-Price-Prediction/assets/118622724/628acaac-5e21-4776-830b-40b69c386084)

Now we split the data in two sets x_train and y_train as shown in the figure.
![processing-5](https://github.com/TejashKatuwal/House-Price-Prediction/assets/118622724/cfff2e3d-5e43-4541-9c36-2dfe6d2576ec)

Now repeat the same steps for test dataset.
# Model Generation
Now we import linear regression and define the model as linear regression and predict the house price and save it in a excel sheet as shown in the figure below.
![output-1](https://github.com/TejashKatuwal/House-Price-Prediction/assets/118622724/560c0c7d-7769-4c55-8155-bc0f587b690a)
![output-2](https://github.com/TejashKatuwal/House-Price-Prediction/assets/118622724/ce5b3353-ab75-4380-be0e-098b26d02f92)






