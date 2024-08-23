# Breast Cancer Segmentation With Advance Attention U-Net

<p align="center">
</p>
<img src="https://www.yourhealth.net.au/wp-content/uploads/2017/09/pink-ribbon-for-breast-cancer-awareness.jpg" width="1000" height="550">
<p>Breast cancer is the most common cancer diagnosed in women, accounting for more than 1 in 10 new cancer diagnoses each year. It is the second most common cause of death from cancer among women in the world. In this project, I have developed the attention U-Net segmentation model that accurately segments the breast cancer-infected region from the breast ultrasound images. This model will significantly reduce radiologist time and fasten the process of breast cancer identification. </p>
<h2>Libraries Used</h2>
<ul>
  <li>Tensorflow</li>
  <li>Numpy</li>
  <li>Pandas </li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
  <li>Sklearn</li>
</ul>
<h2>Data Visualization</h2>
<p align="center"> 
<img src="https://github.com/NavinBondade/Breast-Cancer-Segmentation-With-Attention-UNet/blob/main/Graphs/Dataset%20Visualization.png?raw=true" width="750" height="500">
</p>
<p align="center"> 
<img src="https://github.com/NavinBondade/Breast-Cancer-Segmentation-With-Attention-UNet/blob/main/Graphs/Dataset%20Visualization%202.png?raw=true" width="750" height="500">
</p>
<h2>Methodology</h2>
<p>Attention U-Net network borrowed the idea of an attention mechanism from NLP and used it in skip connections. It gave the skip connections an extra idea of which region to focus on while segmenting the given object.The model has been trained for 20 epochs with binary crossentropy as loss function and adam as the optimizer.</p>
<p align="center"> 
<img src="https://github.com/NavinBondade/Breast-Cancer-Segmentation-With-Attention-UNet/blob/main/Graphs/model.png?raw=true">
</p>
<h2>Model Training</h2>   
<h4>Model Loss:</h4>   
<p align="center"> 
<img src="https://github.com/NavinBondade/Breast-Cancer-Segmentation-With-Attention-UNet/blob/main/Graphs/Loss.png?raw=true" width="700" height="400">
</p>
<h4>Model Accuracy:</h4>  
<p align="center"> 
<img src="https://github.com/NavinBondade/Breast-Cancer-Segmentation-With-Attention-UNet/blob/main/Graphs/Accuracy.png?raw=true" width="700" height="400">
</p>
<h4>Model IOU:</h4>  
<p align="center"> 
<img src="https://github.com/NavinBondade/Breast-Cancer-Segmentation-With-Attention-UNet/blob/main/Graphs/IOU.png?raw=true" width="700" height="400">
</p>
<h2>Model Prediction</h2>
<p align="center">
<img src="https://github.com/NavinBondade/Breast-Cancer-Segmentation-With-Attention-UNet/blob/main/Graphs/output.png?raw=true" width="800" height="1200">
</p>
<h2>Conclusion</h2>  
<p>In this project, I have created Attention U-Net model for correctly segmenting breast cancer from ultrasound images.</p>  


