# Predictive Brain Cancer Detection and Treatment Using Machine Learning and Artificial Intelligence

## Abstract:
Through the combination of Big Data and the computer science discipline of machine learning, significant insights may be gained. Machine learning may now be utilized to anticipate nearly any result based on any capability thanks to developing technology. By analyzing underlying patterns in the data, machine learning creates an appropriate model. Every day, medical sciences must overcome new obstacles, such as patients' lack of knowledge about the ailments they are suffering from, the need for more advanced therapies, the development of new pharmaceuticals, and other issues. Through the simple input of current medical reports like Brain MRIs, this project will assist patients in identifying cancer and directing them to proceed with the appropriate therapies.

**Dataset Used: https://www.kaggle.com/datasets/abhranta/brain-tumor-detection-mri**

### The Project contains the following files:
- **Brain_Cancer_Detection.ipynb:**
  This model detects Cancer (if present) in the Brain MRI image and sends it ahead to the Treatment Model (If Positive)
  Input: MRI Image
  Output: Detection Result - Positive OR Negative
- **Brain_Cancer_Treatment.ipynb:**
  If MRI has been detected as positive through the Detection Model, it classifies the image in 3 Severities - Mild, Moderate and Severe.
  Input: Positive Tumor MRI image
  Output: Severity Prediction & Potential treatment pathways - Mild, Moderate, or Severe.
- **BrainCancerTreatmentUI.ipynb:**
  This code uses Python's "streamlit" library to integrate the two data models and present the UI on a web browser.

### To Run this Project:
- Run Detection and Treatment Models individually through the dataset to generate models **bestmodel.h5**.
- Upload these models to the UI file and access the streamlit link at the end of the output preview to run the modules together and upload MRI image.
- The Detection result from the Uploaded MRI image will show up.
- If Positive, a "Proceed to Treatment" button will be displayed.
- Once clicked, it will display Severity and plans for Treatment as per Severity detected.

### Project Demo: https://i.imgur.com/lMuw4Kz.mp4

  
