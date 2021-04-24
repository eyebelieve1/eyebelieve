# Read Me 

Team: Eye Believe 

Project: Eye Spy a Disease 

Authors: Vanessa Cruz, Parker Kotlarz, Cristina Williams 

Course: BME 3053C Computer Applications for BME 

Term: Spring 2021 

J. Crayton Pruitt Family Department of Biomedical Engineering 

University of Florida 

Email: kotlarz.parker@ufl.edu 

April 11, 2021 

*Action Items Denote Modifiable User Input*

 

# How to Operate the Code 

## Creating the the Trained Network 

Step 1: Establish the pretrained network Alexnet in MATLAB. 

Step 2: Modify layers 23-25 to change Alexnet from general image classifcation to specifically recognizing eye diseases. 

Step 3: Load the image data (Eye_Images_Finalized.zip) with their correct label. Make sure to unzip the files before you try and use them. Image must be converted to 227x227 for Alexnet. 

Step 4: Split the images into training and testing sets (optimal 0.7 or 0.8) 

	Action Item: Decide upon split value to separate training and testing set 

Step 5: Train the network on the training set (optimal epochs: 12-15, optimal batch: 4-6) 

	Action Item: Decide upon epochs to establish how long the network will train 

	Action Item: Decide upon batch size to establish how large to training batches are 

Step 6: Test the newly trained network on the testing set. 

Step 7: Analyze accuracy of the network using a confusion matrix. 

## Individual Image Classification 

Step 1: Load the image 

	Action Item: Load the individual image file into the imread function 

Step 2: Resize the image to 227 x 227 

Step 3: Use the trained network to classify the image 

## Link to Youtube Tutorial
[![Tutorial](http://img.youtube.com/vi/jVHB41cclGo/0.jpg)](http://www.youtube.com/watch?v=jVHB41cclGo)
