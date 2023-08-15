# DeepLearningHarvardOnline
Final project for CSCI-89 Deep Learning

Happywhale is a project set up to use crowd-sourcing for identifying images taken of whales and dolphins, known collectively as cetaceans. People are asked to upload photos of cetaceans they have taken on their travels or excursions and then upload them. This information is then used by the organization in conservation projects to track cetaceans around the globe and understand their survival and population metrics.
This project was originally a Kaggle competition to help them build a recognition model with images of whales, often showing just their back or fin in the image. The concept is similar to facial recognition in that it aims to identify specific cetaceans from these images to understand where they have traveled to.
The original dataset is 51103 images of 15587 individual cetaceans and the size total is about 60GB. I found an additional dataset which was formed from the original by resizing and gray-scaling the images which cut the size down to 2GB. My aim of the project was to see how well I could predict individual whales on this smaller dataset, assuming that we would lose some accuracy from the larger original
  1
images. Additionally, I built a model to classify the species from the same data, of which there are 30 species of whale and dolphin in the dataset.
The gray-scale dataset contains the same number of images and individual cetaceans. I used this dataset to attempt a solution for this problem.
I used a MacBook Air (M1, 2020) with 8GB of RAM for the data exploration and training of the species models and a Kaggle notebook with GPU P100 for training the individual model.
