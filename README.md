# AutoVOCAnnotator
## Background of Development
My goal was to develop a dog breed classification model that reflects the most popular dog breeds in South Korea. This model is designed to identify a dog's breed solely from its image.

To implement this model, I referenced Kaggle's Dog Breeds Classifier code and utilized the Stanford Dogs Dataset. However, I encountered a significant issue—the dataset did not adequately represent the most popular dog breeds in South Korea.

To address this, I collected additional images of Korean-favored dog breeds that were missing from the Stanford Dogs Dataset. However, manually annotating such a large volume of images proved to be highly inefficient. To overcome this challenge, I developed an automated annotation tool to streamline the process.

I hope this tool contributes to improving your model's performance and helps you manage your project timelines more efficiently.
## Features
1. Parse Pascal VOC XML - Extract bounding box coordinates and class labels from XML files
2. Convert Annotations - Format annotations for CNN-based deep learning models
3. Automate Data Processing - Batch process multiple XML files for annotation generation
4. Easily Extendable - Convert annotation data to other formats if needed

## Data
The additional collected breed (Bichon Frise) was obtained by crawling images from Google.
I followed the folder and file naming conventions, as well as the overall directory structure, of the Stanford Dogs Dataset. 
http://vision.stanford.edu/aditya86/ImageNetDogs/

## Code
I developed the annotation automation code, and later, I referenced Kaggle's Dog Breeds Classifier code to preprocess and save the images based on the annotations.
https://www.kaggle.com/code/hengzheng/dog-breeds-classifier/notebook

## Achievement
Optimizing data setup efficiency by developing an automated annotation tool
Improving the dog breed classification model to better align with the domestic environment by integrating popular breeds in South Korea
