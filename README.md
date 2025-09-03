
### Abstract
Lung cancer is a deadly disease with a high death rate among affected individuals. An early and accurate diagnosis is critical to saving lives. This project presents a novel technique called 


Cancer Cell Detection using Hybrid Neural Network (CCDC-HNN) for the early and precise diagnosis of lung cancer from CT scan images. The goal is to overcome the limitations of conventional methods, which are often time-consuming and lack accuracy. Our approach uses deep neural networks to extract features from CT scans and makes it possible to distinguish between benign and malignant tumors.


---

### Methodology
The system employs a Hybrid Neural Network that combines Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) algorithms for cancer cell detection. The process is as follows:


Dataset: The system is trained using the Lung Image Database Consortium and Image Database Resource Initiative (LIDC-IDRI) dataset.



Segmentation: The UNET algorithm is used to accurately segment cancer cells and identify tumor boundaries.


Classification: The proposed CCDC-HNN algorithm classifies the segmented cells based on their features.


Enhanced Accuracy: An advanced 3D-convolution neural network (3D-CNN) is also used in this study to increase diagnosis accuracy.

---

### Key Findings and Results
The proposed hybrid deep learning approach for early lung cancer detection is feasible and provides a high degree of accuracy. The empirical results show that the improved model provides:


Accuracy: 95% 


Selectivity (SP): 90% 


Sensitivities (SE): 87%
---

### How to Run the Project

To run this project, follow these steps:

1.  **Install Python:** Visit the official Python website to download and install Python 3.7.0.
2.  **Install Libraries:** Use `Cmd` to install all the required libraries.
3.  **Upload Dataset:** Upload the LIDC-IDRI dataset to the application.
4.  **Process Dataset:** The application will read, resize, and normalize the images.
5.  **Split Data:** Split the dataset into 80% for training and 20% for testing.
6.  **Run Algorithm:** Run the Hybrid CCDC-HNN algorithm to train the model on the training images.
7.  **Test and Classify:** The trained model will be applied to the test images to calculate prediction accuracy. You can upload and test new images, which will then be classified as either Benign or Malignant.

---

### Authors

* Moksud Alam Mallik
* Mohammed Dawood Khan 
* Muazuddin Syed
* Mohd Shoeb Taj 
* Nurul Fariza Zulkurnain

---

### References

* R.L. Siegel, et al., "Cancer statistics," *Cancer J. Clin.* (2022).
* F. Ciompi, et al., "Towards automatic pulmonary nodule management in lung cancer screening with deep learning," *Sci. [cite_start]Rep.* (2017).
* S. Bhatia, et al., "Lung cancer detection: a deep learning approach," in *Soft Comp. for Prob. Solving* (2019).