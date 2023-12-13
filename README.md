# Analysis of Circular Containment Areas for Fruit Detection in Smart Agriculture

This project contains code for master thesis entitled "Analysis of Circular Containment Areas for Fruit Detection in Smart Agriculture". The intention of the paper is to verify the effectiveness of using circular frames in detection and to compare the relatively new concept with traditional rectangular containment areas, which are widely used. Dataset used in thesis consist of images with apples and annotations.

This repository contains the code and Jupyter notebooks used in the implementation and analysis of my thesis project. The code is organized into several folders, and you can use the provided req.txt file to set up the necessary dependencies.




## Repository Structure 

- **datasets_not_splited**: This folder contains raw datasets splited into several subfolders of two kind. First set of folders contains images, second annotations. 

    Subfolders images and annotations_circle contains data before augmentation process. 

    Subfolders images_aug and annotations_circle_aug contains data after first process of augmentation.

    Subfolders images_aug2 and annotations_circle_aug2 contains data after second process of augmentation.

- **datasets_splited**: This folder contains dataset splited into train, test and validations set.

    Subfolder dataset contains data splited into subsets for data afoter first augmentation.

    Subfolder dataset_3 contains data splited into subsets for data afoter second augmentation.

- **sets_for_dataset_splits**: This folder contains .txt files with name of files from dataset. They are used to split data into subsets.

- **other_models**: This folder contains jupiter notebooks with models for tests and two notebooks with final model before finetuning.

- **calculate_mAP_circular**: Script to calculate mAP for circular bboxes.

- **calculate_mAP_rectangular**: Script to calculate mAP for rectangular bboxes.

- **data_augmentation**: Script to perform data augmentation.

- **split_data_to_sets**: Script to perform data split into subsets.

- **circ_det_three_iterations**: Script that contains first, second and third gen models described in thesis.

- **final_model_circular**: Script with final model for circular bboxes.

- **final_model_rectangular**: Script with final model for rectangular bboxes.


