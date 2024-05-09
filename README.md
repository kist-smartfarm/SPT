# SPT
## Overview

This repository contains the image data used in the study **"Development of a Deep-Learning Phenotyping Tool for Analyzing Image-Based Strawberry Phenotypes,"** designated as **"SPT."**

The dataset comprises high-quality images of key phenotypic traits (crown diameter, petiole length, plant height, flower, leaf, and fruit size), which were utilized for training, validation, and testing of the two SPT versions. Additionally, it includes a validation dataset consisting of 70 sample  images per phenotype with their corresponding quantitative measurements obtained via conventional methods. These real quantitative data were measured the same day as  the image sampling to serve as  reference and were used to calibrate and evaluate the phenotyping tool's accuracy.

---


## Dataset
### Download
* Download Link: [Google Drive](https://drive.google.com/drive/folders/0ACRvm56q9nQoUk9PVA)

### Contents
- `images_trainingresults_and_weights/`: Training datasets along with model results and weight files.
- `validation_data_v1andv2_70images/`: Validation datasets with 70 images per phenotype, accompanied by real quantitative measurements from conventional methods, used for spatial image calibration and model accuracy assessment.
    
### Detailed Folder Structure 
```
- train_data/
  - version1/: Includes subfolders for each trait (crown, flower, fruit, leaf, petiole, plant height).
  - version2/: Includes advanced phenotyping images and specific trait enhancements.
- train_results/: Contains output from training sessions.

- weights/: Stores model weights for further analysis and deployment.
Validation Data
  - CD/: Crown diameter images.
  - flower/: Flower images.
  - fruit/: Fruit images.
  - leaf/: Leaf images.
  - PH_PL/: Petiole height and plant length images.
```

## Usage
This dataset is intended for use by researchers and developers focused on advancing phenotyping technologies through image analysis and deep learning. The structured approach to data collection and validation ensures that users can effectively train and test phenotyping models, potentially extending to other crops beyond strawberries.

## Contributions
Contributions to the dataset, such as additional phenotypic data, improvements to data processing scripts, or new tools for analysis, are welcomed. Contributors are encouraged to submit pull requests or contact the dataset maintainers directly 
