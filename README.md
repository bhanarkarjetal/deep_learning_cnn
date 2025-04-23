# Deep learning final project:

**Aim:** 
The goal is to build a vision pipeline that can read still images of hand pose signs for the digits 0 – 9 and classify them correctly.
This involves:
1.	Loading & structuring the raw data (NumPy arrays supplied by Kaggle). 
2.	Explored the distribution and quality of the images.
3.	Pre processing (normalization, augmentation, reshaping).
4.	Evaluation & error analysis to understand where and why misclassifications occur.

**Dataset:**
The dataset is taken from Kaggle which consists of images for digits in sign language. It consists of 2062 images of size 64x64 and a label dataset of digits 0 to 9 in .npy format
•	x.shape = (2062, 64, 64)
•	y.shape = (2062, 10)

**Data Cleaning and Exploration**
1. Plotted first and last sample to sanity check label alignment.
2. Generate count-plot for label distribution in entire dataset
3. Plotted first and last sample to sanity check label alignment.
4. Generated one sample image of each label.
5. Visualized intra class variation: 10 random images for a single digit.
![alt text](https://github.com/bhanarkarjetal/deep_learning_cnn/blob/main/sample_single_label_images.png)

