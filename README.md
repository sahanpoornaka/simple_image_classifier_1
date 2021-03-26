[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
# Image Classification with Deep Neural Networks

This challenge is to encourage you to study popular deep learning networks in image classification.  

## Objectives

To study:
1. Creating a custom dataset using Bing searches
1. Transfer Learning
1. Using Keras Pre-trained Models  
1. Using the TensorFlow Hub
1. Using the TensorBoard

## Branch
This only has the main branch.
Please watch this page to receive updates and corrections.

## License
This code is hosted in a private repository to regulate access. 
You can share your code under MIT license.

## Completion Award
AUD 400 will be awarded as an appreciation to the trainee who completes this module first.

## Terms & Conditions:
1. Only DataDisca trainees who are not currently under a paid contract can participate
1. Steps given in this document should be followed 
1. There is only one price.  The first person to complete wins.
1. The winner is supposed to invoice DataDisca with the ABN to receive price money. Otherwise, supermarket gift cards will be emailed.
1. Keep your Git repository up to date with your latest work.
1. All intermediate and final work should be kept opensource under MIT license. 
Failure to keep the codes open violates the purpose of the study. 
1. Your code should be bug free and follow PEP8 standard
1. You can use either Jupyter notebook/labs or Python code in an IDE.
1. Computing resources are provided as available. 
1. Expiry datetime:  Github commits should be made before 2021-06-24 23:59:59.
1. The decision of the Director of DataDisca is final.       
  
      
## Instructions
Use the following steps to complete the challenge. There will be an interview after each step.

#### Step 1

Create a dataset with the following Bing Searches to download the following images from Bing.
1. "norwegian male"
1. "norwegian female"
1. "indian male"
1. "indian female"

Please note the following:
1. The searches should only contain the above terms. 
1. Apart from removing inappropriate content, the images cannot be chosen to produce better results.  
1. You can download adequate number of images. An example code is given below. 
      ````python
    from bing_image_downloader import downloader
    query_string = "norwegian male"
    downloader.download(query_string, limit=10000,  output_dir='dataset'
                        , adult_filter_off=True, force_replace=False, timeout=60)
    ````
1. DataDisca will have to inspect the dataset while assisting you.
1. DO NOT share downloaded images with your open source work. 
Bing searches are subjected to terms and conditions, and copyright laws.  
1. After training and demonstrating, delete the datasets.

#### Step 2

1. Develop a neural network classifier to identify the four classes defined by country and the gender combinations.
1. Your experiments must cover the following unless there is a performance barrier.
    1. Keras models: at least VGG16, ResNet50, InceptionV3 and Xception (https://keras.io/api/applications/).
    1. At least two models downloaded from the TensorFlow Hub (https://tfhub.dev/).
    1. With a balanced dataset the accuracy target for each model in this step is 70%.  
1. All models should be visualised using the TensorBoard (https://www.tensorflow.org/tensorboard).
1. Discuss your code and procedure with DataDisca.

### Step 3

1. Tune any Keras/Tensorflow based model till you receive 90% accuracy with a balanced dataset.
1. DataDisca will test your model against a few previously unseen datasets.
1. Publish your code, TendorBoard and results on GitHub.
1. Delete the datasets.    
  

## General Conditions

1. Code should follow PEP8 Standard
1. Host your code on your GitHub in a public or private repository as you prefer. 
- If it is a public repository, send the link for us to evaluate.
- If it is a private repository, share (view only) with our GitHub usernames [DataDisca](https://github.com/DataDisca) and/or [mbtl-datadisca](https://github.com/mbtl-datadisca).

	Send us a notification to start the evaluation.
	We evaluate your code for your technical progress.

## Sponsor
DataDisca Pty Ltd, Melbourne, Australia

[https://www.datadisca.com](https://www.datadisca.com)
