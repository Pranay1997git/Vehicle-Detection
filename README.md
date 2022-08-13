# Vehicle-Detection

This project can detect vehicles ,mainly among bike ,car ,ski jet,truck,plane because i have used this in training the model . And the gave me around 94.2%  accuracy in predicting as can be seen in snap from web app below




![webapp_prediction](https://user-images.githubusercontent.com/109203404/184489722-87df8a29-0539-4bae-b1b0-a5e6b720270c.png)




I have scraped the whole dataset using Selenium .Resized the images using opencv before training .Splitted the data into train,valid,test using splitfolders library.

Then Augmented the data because the data for training was less using Augmentor .

After that , Annotated the data using labelimg.

Then trained the model using Tensorflow 1.x
