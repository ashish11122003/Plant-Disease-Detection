# Plant Disease Detection
<h1>Overview</h1>
<p>This project aims to detect various plant diseases using deep learning. The detection model is based on Convolutional Neural Network (CNN) architecture, specifically utilizing the VGG16 model with transfer learning.</p>
<h1>Dataset</h1>
<a href="https://www.kaggle.com/datasets/poornimasingh/plant-village">Click Here</a>
<h1>Tools and Technologies</h1>
<ul>
<li>VGG16: A widely used CNN architecture designed for ImageNet, used here for feature extraction.</li>
<li>Transfer Learning: Technique involving a pre-trained neural network (VGG16) and adapting it for Plant disease detection.</li>
<li>Keras and TensorFlow: Deep learning libraries used for model development and training.</li>
</ul>
<h1>Model Architecture</h1>
<p>The model architecture involves taking the pre-trained VGG16 model, modifying the top layers for the pneumonia detection task, and freezing the pre-trained layers to leverage transfer learning.</p>