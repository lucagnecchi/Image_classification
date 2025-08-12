# Breast Cancer Classification

## Project Goal
This project aims to develop a computer-aided detection system for breast cancer using histopathological images. The goal is to classify tumors as either benign or one of four types of malignant tumors: ductal carcinoma, lobular carcinoma, mucinous carcinoma, and papillary carcinoma. Early detection is crucial for improving outcomes, and this system can assist in that process.

## Dataset
The dataset used for this study is the Breast Cancer Histopathological Database (BreaKHis), which contains approximately 8,000 microscopic images of breast tumor tissue. These images were collected using different magnifying factors (40X, 100X, 200X, and 400X) and are 700x460 pixels in PNG format. The dataset includes 2,480 benign and 5,429 malignant samples collected using the surgical (open) biopsy (SOB) method.

## Data Manipulation and Visualization
The initial data manipulation involved organizing the images from their original folder structure into categories corresponding to the tumor types. Benign tumor images were grouped together to address class imbalance among the benign subcategories.

Visualizations were created to show the distribution of images across the different categories, highlighting the imbalance, particularly the overrepresentation of ductal carcinoma.

To mitigate the class imbalance, a subset of images from the 'ductal carcinoma' category was randomly sampled and moved to a separate folder.

The dataset was then split into training and testing sets, with 80% of the images allocated for training and 20% for testing. The split was performed by randomly sampling images from each category and moving them to a 'Test' folder.

The final distribution of images in the training set was visualized to confirm the effects of the sampling and splitting procedures.

## Model Implementation
For the model implementation, please refer to the following notebooks:
- **AlexNet**
- **GoogLeNet**
