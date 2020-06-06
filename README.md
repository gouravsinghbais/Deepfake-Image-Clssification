# Deepfake-Image-Classification
Identifying the GANs generated image. 

### Dependencies and Installation Guide
Programming Language:

- Python 3.6

**Libraries needed to Run this project:**

- tensorlow-1.13.0
- opencv-python
- keras-2.3.0
- matplotlib 
- os
- mtcnn
- pillow 

**Required model architecture and weights files:**

you can download the weights and model architecture file from here:
https://drive.google.com/open?id=1KujeIcVzoRWHgBlO-BzpClxhujUbeDmV

**Dataset:**

**Dataset for training the model are available here:**
https://drive.google.com/file/d/1smby8vBB0g8bNtUsQ10OdjF-4FK9k_GS/view

**Instructions to train the model:**

- Dataset which is provided in the link is already preprocessed and it contains images which has only faces i.e. MTCNN is already applied.
- You need to download the dataset and just run the model training section since face detection part is already done.
- give the path of folders into the ImageDataGenerator and run the model it will start training.  

**Insutuctions to test the model:**

- You will to download the model.json and model.h5 file and will have to give the path of these files in the testing of the notebook.
- Then choose the image on which you want to make the prediction give that imaeg path in the testing section and predictions will be generated. 

**References:**

- https://www.researchgate.net/publication/327905310_Forensics_Face_Detection_From_GANs_Using_Convolutional_Neural_Network?enrichId=rgreq-fa3b4b45646d1695236abfc1b3a44062-XXX&enrichSource=Y292ZXJQYWdlOzMyNzkwNTMxMDtBUzo2NzUzNzI5NjYzNTkwNTZAMTUzODAzMjg3MTc5MA==&el=1_x_3&_esc=publicationCoverPdf

## You can read my blog on Fake Face Classification:
https://medium.com/analytics-vidhya/fake-face-image-classification-5a4151db9b8d
