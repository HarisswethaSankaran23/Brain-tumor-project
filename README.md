<h1>🧠 Brain Tumor Detection Using Deep Learning</h1>

<h2>Description</h2>
This project aims to identify and segment brain tumors in MRI images using a combination of preprocessing, thresholding, and deep learning models. It includes multiple segmentation approaches such as CNN, FCM, and K-Means clustering.
<br />

<h2>Languages and Utilities Used</h2>

- <b>Python</b>  
- <b>TensorFlow / Keras</b>  
- <b>OpenCV</b>  
- <b>Scikit-learn</b>  

<h2>Environments Used</h2>

- <b>Jupyter Notebook</b>  
- <b>Google Colab</b>  
- <b>Windows/Linux</b>  

<h2>Project Walk-through:</h2>

<h3>Stage 1: Skull Stripping</h3>
<p align="center">
<img src="7a75a8d4-2e0d-487b-a3c9-4d2fae06cc9f.png" height="80%" width="80%" alt="Skull Stripping"/>
</p>

<h3>Segmentation Using FCM</h3>
<p align="center">
<img src="dd964f9d-471a-4ed4-88b6-20355ef26292.png" height="80%" width="80%" alt="Segmentation FCM"/>
</p>

<h3>Segmentation Using K-Means Clustering</h3>
<p align="center">
<img src="f789b3cc-2f0f-40db-9acc-3e7041da9025.png" height="80%" width="80%" alt="Segmentation KMeans"/>
</p>

<h3>Performance Comparison Table</h3>
<p align="center">
<img src="0a6c558b-1d22-4b52-9414-227218afc9a8.png" height="80%" width="80%" alt="Performance Table"/>
</p>

<h2>Features</h2>

- Skull stripping, image thresholding, and enhancement  
- CNN-based tumor region extraction  
- Fuzzy C-Means and K-Means clustering comparisons  
- Performance metrics with accuracy comparisons  

<h2>Future Scope</h2>

- Extend to multi-class tumor classification  
- Use 3D MRI volumes for better precision  
- Deploy the model as a web-based diagnostic tool

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
