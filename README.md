# Brain Tumor Detection and Segementation

## About
This project presents an AI-based system for the automated detection and segmentation of brain tumors from MRI images. The objective is to assist medical professionals by improving diagnostic accuracy and reducing analysis time. The dataset is preprocessed using grayscale conversion, normalization, and noise reduction techniques. The model was trained with multiple classifiers that includes Random Forest, SVC, Decision Tree and XGBoost and the best performing model which was SVC, is chosen to train the dataset. The system comprises two major components: a classification model to detect the presence of a tumor, and a U-Net-based Convolutional Neural Network (CNN) for segmenting the tumor region from MRI scans. The U-Net architecture accurately highlights tumor boundaries for further analysis. The project offers a reliable and efficient solution for early diagnosis and medical research support.

## Output
### Home page
In this page, we have to upload the relevant MRI image.

<img width="1920" height="864" alt="home" src="https://github.com/user-attachments/assets/0b844b6d-5e5a-4586-a54f-ebaaed03152e" />

### No Tumor
If there is no Tumor detected, the following output will be shown.

<img width="1920" height="758" alt="no_tumor" src="https://github.com/user-attachments/assets/926df5af-50ce-49e2-855e-3e14501dca68" />

### Tumor
If Tumor detected, the infected part will be detected and the system will highlight it. Finally, the infected part will be segmented as shown below.

<img width="1920" height="634" alt="tumor" src="https://github.com/user-attachments/assets/77dd3210-efe7-4794-870f-01952b02cba7" />
