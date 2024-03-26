# Plant Disease Detection
<h1>Overview</h1>
<p>This project aims to detect various plant diseases using deep learning. The detection model is based on Convolutional Neural Network (CNN) architecture, specifically utilizing the VGG16 model with transfer learning.</p>
<h1>Dataset</h1>
<a href="https://www.kaggle.com/datasets/poornimasingh/plant-village">Click Here</a>
<h1>Tools and Technologies</h1>
<ul>
<li><b>VGG16:</b> A widely used CNN architecture designed for ImageNet, used here for feature extraction.</li>
<li><b>Transfer Learning:</b> Technique involving a pre-trained neural network (VGG16) and adapting it for Plant disease detection.</li>
<li><b>Keras and TensorFlow:</b> Deep learning libraries used for model development and training.</li>
</ul>
<h1>Model Architecture</h1>
<p>The model architecture involves taking the pre-trained VGG16 model, modifying the top layers for the pneumonia detection task, and freezing the pre-trained layers to leverage transfer learning.</p>
<h1>Implementation Steps</h1>
<ul>
<li><b>Download the dataset</b></li>
<li><b>Model Development:</b> Use the provided Python script plantdisease.ipynb for creating and training the plant disease detection model. Adjust hyperparameters, such as epochs and batch size, based on your requirements.</li>
<li><b>Model Evaluation</b></li>
<li><b>Save and Load Model:</b> The trained model is saved as plantmodelvgg16.h5 for future use, allowing you to load the model without retraining.</li>
</ul>