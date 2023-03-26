# DS4002_Project2_TeamNBC
Title: MI2-Project2
Group Name: Team NBC
Members: Mianchen (Bruce) Cao, Nathan Patton, Camden Miller
Leader: Mianchen (Bruce) Cao
Course: DS 4002
Date: March 16th, 2023

Hypothesis
There are distinct differences among different species of butterflies and moths, and based on different features of the species, we can determine which species a certain butterfly or moth is by using a computer program. 

Research Question
Can we use a machine learning model to predict the species of butterflies and moths using computer visualization and image classification?

Modeling Approach
We need to test our hypothesis by trying to classify different species of butterflies and moths based on our image inputs. One popular model to do this is called CNN (Convolutional Neural Network) model. This model is a class of neural networks that specializes in processing data that has a grid-like topology, such as an image [1]. Our input dataset is a dataset found on Kaggle containing 100 species of butterflies and moths, and we will choose 25 common and distinctive species to build our program using CNN model [2]. We will divide our set into training, testing, and validation groups to perform the prediction.

Executive Summary
This document outlines the plan to create a computer visualization program based on CNN model that can recognize pictures of butterflies and moths and categorize them into different species. The established data set is detailed below focusing mainly on selecting butterfly and moth species that have distinct features. The analysis plan is provided with initial plans to use a CNN model. 

Data Set Establishment Details
Established Data Set:
After establishing a hypothesis and a research question that we think has solid motivation and value behind it, we searched for datasets that included pictures of different species of butterflies and moths. We found a Kaggle dataset named “Butterfly & Moths Image Classification 100 species” published by Gerry 4 months ago [2]. The dataset is accessible via the link in the reference section. The dataset is a collection of pictures of different species of butterflies and moths. The creator has divided the collection into a training set, a testing set, and a validation set, and each set contains 100 species of butterflies and moths. All images are 224 x 224 x 3 in jpg format. The training set contains most of the images, 12,639 images, and the other two sets consist of 500 images each. The 500 images in the test set and the validation set are partitioned into 100 subdirectories with 5 images per species. We agree that 100 species might exceed our hardware’s computational power, we decided to select 25 species that have distinct features for our project. Therefore, we will also trim the training set to make it fit our project, but we will still use 5 images for each species for testing and validation purposes. Since the purpose of this project is to build a computer visualization program and categorize insects and our biological knowledge of determining if a certain species is a moth or a butterfly is insufficient, we will just refer to all of them as butterflies in our project. Since all the data we really need is just images, we won’t add additional information to our dataset. The CNN model will first have a 4D sensor (number of images, width, height, RGB channel), and there is no specific characteristic to be measured, so our hypothesis has nothing to be refined. We will still just stick to the general features of the butterflies. Please see below for the data dictionary and a snapshot of the images. 
