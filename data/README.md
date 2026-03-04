# Skin Lesion Classification
Diane Lenhoff – ITAI 1378 Midterm Project

##Tier Selection
Tier 1 – A basic image classification project using transfer learning.

##Problem Statement
Skin cancer screening can take time, and access to specialists may not always be available. A computer vision model could help analyze images of skin lesions and classify them as benign or malignant to support early screening.

##Solution Overview
This project will build a computer vision model that takes an image of a skin lesion and predicts whether it appears benign or malignant. The goal is to demonstrate how machine learning can assist with image-based classification problems.

##Technical Approach
The project will use an image classification approach. A pretrained model will be used with transfer learning so the model can adapt to the skin lesion dataset without needing to train from scratch.

##Dataset Plan
The dataset will come from a public skin lesion dataset available on Kaggle. The dataset will contain images labeled as benign or malignant. Images will be resized, normalized, and split into training and testing sets before training the model.

##Metrics
The main goal will be to reach an accuracy of at least 85%. Additional evaluation will look at how well the model identifies malignant cases using precision and recall.

##Week Plan
Day 1: Get the dataset and set up the environment → Dataset ready Day 2:Train or fine-tune the model → Model working Day 3: Test the model and improve results → Good accuracy Day 4: Evaluate results and make improvements → Improved performance Day 5: Final testing and documentation → Project complete Day 6: Final review and submit project → Project submitted

##Resources Needed
The project will use Google Colab for computing resources and PyTorch for building and training the model. Additional libraries such as torchvision will be used for data handling and evaluation. The estimated cost of the project is $0.

##Risks & Mitigation
If one class has significantly more images than the other, additional image variations can be created to balance the dataset. If accuracy is too low, a slightly stronger pretrained model may be tested. If time becomes limited, the dataset size may be reduced to keep the project manageable.

##AI Usage Log
ChatGPT was used to verify terminology and get a plain language explanation of technical concepts when neededDataset information will be added here.
