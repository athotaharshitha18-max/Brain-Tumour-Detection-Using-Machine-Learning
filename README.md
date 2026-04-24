# Brain-Tumour-Detection-Using-Machine-Learning

Dataset Description:
Due to size limitations, the dataset is not included in this repository. Below is a detailed description of the dataset used in this project.

Dataset Overview:
The dataset consists of brain MRI images used for binary classification of brain tumors. It contains a total of 5,266 images, collected from publicly available medical imaging sources.

Dataset Structure:
The dataset is organized into three main categories:
Glioma
Meningioma
Pituitary Tumor

These categories represent different types of brain tumors. For the purpose of this project, the dataset was further simplified into a binary classification problem:
Positive (Tumor Present): 3,266 images (~62%)
Negative (No Tumor): 2,000 images (~38%)

Class Distribution:
The dataset has a moderate class imbalance with a ratio of approximately 1.63:1 (Tumor : Non-Tumor). To handle this, class weights were applied during model training.

Image Characteristics:
Imaging Type: MRI (Magnetic Resonance Imaging)
Orientations: Axial, Sagittal, and Coronal
Format: Grayscale (converted during preprocessing)
Original images vary in size and quality


