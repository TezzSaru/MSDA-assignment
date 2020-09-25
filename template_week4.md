# Instructions for Assignment 3 submission 

- Please copy the contents of this markdown as the starting template of your assingment. 
- The resulting file from this programming assingment must be submitted to the private repo you submitted for my review during assignment one. 
- The name of the file has to follow  naming convention:  *lastname*_week4.ipynb
- There are four sections of this assignments required to receive full credit. 
- Please see that the expected file is a Jupyter notebook which contains Python code and markdown, just like shown in class and in my recap video from week 2. 


# Section 1) Fetch of the Kaggle Cats vs Dogs dataset (5%)

(This section shows the commands used to fetch the dataset successfuly with no errors.)

# Section 2) Coding of the convolutional neural network from scratch following the code example from keras.io (https://keras.io/examples/vision/image_classification_from_scratch/) (30%)

(This section shows the source code of your CNN and training)

# Section 3) Calculation of the accuracy of the model with 25 epochs and then 50 epochs (15%)

(This section shows the accuracy of your model after 25 and 50 epochs. Show the calculation of the accuracy individually for each. You can create a function of the code and take in as a parameter the number of epochs in each run or you can just copy the whole code over twice if you can't produce a function)

# Section 4) Code an option that prompts the user for an image online (user to write the full URL of an image) (20%)

(This section when executed by you (or me) should prompt for the URL of an image online of a dog or a cat, download that image and store it locally. Show from the Jupyter notebok the file in your hard drive. Hint!  look for magic commands on Jupyter notebook or just the sys Python library for this) 
If you can't successfuly write this function but provide the images locally, then I will take 5% grading of this section only. Full function implementation is expected to earn the 20% points. 


# Section 5) Run your predictor model in the image from the URL submitted by the user and provide the best classification of whether the image is a dog or a cat. (30%)

(This section requires you to show your predictor running in the image pointed to from the last step. I expect then to point to a URL in step 4, that your code downloads the image, and in step 5 to execute your classifier against that image)
If your code works flawless in determining a dog or a cat, then I will grant 30%
If everything executes but the classification is not correct and you don't provide code to correct the input image, then I will only grant 15% 
If everything executes but the classification is not correct with my image but it shows in your Jupyter notebook that it worked with a couple of images you downloaded then I will only grant 20%
If your classification errors out, I will not troubleshoot your code, I expect things to run without errors regardless of the classification. If your code errors out here, I will grant no points

