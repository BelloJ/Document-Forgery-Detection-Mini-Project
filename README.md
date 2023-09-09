# Image Forgery Detection Project
In this project we employ Machine learning methods to tell if an image has been manipulated or not.
## Introduction

In the digital age, images play a pivotal role in various sectors, from journalism to identity verification. However, with the rise of advanced image manipulation tools, the authenticity of these images can be compromised, leading to misinformation and other challenges. This repository focuses on detecting such tampered images using two distinct approaches:

1. **Document Forgery Detection using SIFT**:
   - A passive image forensics method based on the Scale-Invariant Feature Transform (SIFT) algorithm and homography estimation.
   - Requires a reference image for comparison.
   
2. **Image Forensics using Deep Learning**:
   - Utilizes a Convolutional Neural Network (CNN) for image forgery detection.
   - Requires training on a labeled dataset.

## Dataset

For the best results, it is recommended to use the dataset organized in the following shared link:
[Dataset Link](https://drive.google.com/drive/folders/1zu3Xm8snnVvNYjuy4entjtDXcLSF4BN6?usp=drive_link)

The organization of the dataset is structured to enhance the model's capacity.

## Installation and Usage

1. Clone the repository.
2. Navigate to the project directory.
3. Install necessary libraries and dependencies as indicated in the notebooks.
4. Run the Jupyter notebooks:
   - `Document_Forgery_Detection_Mini_Project.ipynb` for the SIFT-based approach.
   - `Image_Forensics_using_Deep_Learning.ipynb` for the CNN-based approach.

## Key Points

- **SIFT-based Approach**:
  - Uses key point matching and homography estimation.
  - Highlights manipulated regions in an image.
  - Particularly useful when a reference image is available.
  
- **CNN-based Approach**:
  - Data preprocessing, augmentation, and normalization are crucial.
  - The model is trained and evaluated on a split dataset.
  - Achieved a test accuracy of about 82.5%.
  - Prediction speed is less than 0.1 seconds per image.

## Future Recommendations

1. Fine-tune hyperparameters for better generalization.
2. Explore advanced CNN architectures or transfer learning techniques.
3. Collect more labeled data to enhance model robustness.
4. Investigate ensemble methods and model interpretability techniques.

## Conclusion

This project showcases the potential of both traditional image processing techniques and deep learning in the realm of image forensics. While each approach has its own set of advantages and limitations, combining them could pave the way for a robust image forgery detection system.

## Feedback and Contributions

Feedback and contributions to this project are welcome. Please ensure to follow the contribution guidelines outlined in the repository.

