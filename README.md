<h1>🧠 Brain Tumor Detection Using Deep Learning</h1>

<h2>Description</h2>
This project uses deep learning and image processing techniques to detect brain tumors from MRI scans. It involves preprocessing, segmentation, and classification using Convolutional Neural Networks (CNNs) and traditional machine learning models. The goal is to support early detection and diagnosis of brain tumors, improving clinical decision-making.
<br />

<h2>Languages and Utilities Used</h2>

- <b>Python</b>  
- <b>TensorFlow / Keras</b>  
- <b>OpenCV</b>  
- <b>Scikit-learn</b>  

<h2>Environments Used</h2>

- <b>Jupyter Notebook / Google Colab</b>  
- <b>Python 3.x</b>  
- <b>Windows/Linux OS</b>  

<h2>Workflow:</h2>

<p align="center">
Step 1: Input MRI Brain Image <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Input Image"/>
<br /><br />
Step 2: Preprocessing using Bilateral Filter for noise reduction <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Preprocessing"/>
<br /><br />
Step 3: Image Enhancement and Thresholding for better feature visibility <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Thresholding"/>
<br /><br />
Step 4: Tumor Region Segmentation with CNN <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Segmentation"/>
<br /><br />
Step 5: Classification using ML Models (KNN, RF, Naive Bayes, MLP, Logistic Regression) <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Classification"/>
<br /><br />
Step 6: Final Output - Tumor Detection with Classified Label <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Final Result"/>
</p>

<h2>Key Features</h2>

- Adaptive Bilateral Filtering for high-accuracy noise removal  
- Binary thresholding to enhance tumor boundaries  
- CNN for deep feature extraction and region segmentation  
- Traditional classifiers compared for validation  
- Potential for integration into diagnostic systems  

<h2>Future Scope</h2>

- Classifying tumor types (benign vs malignant)  
- Processing 3D MRI image data  
- Deploying as a real-time diagnostic tool  
