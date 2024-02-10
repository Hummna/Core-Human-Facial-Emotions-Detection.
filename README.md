# Human Emotions Detection
<!DOCTYPE html>
<html>

<head>
 
</head>
<body>

  <h1>About</h1>

  <p>Emotion recognition is a crucial task in computer vision, aiming to identify human emotions from facial expressions. This project explores different deep learning models  with various pre-trained architectures to achieve accurate emotion recognition. The models are trained on a dataset containing images of facial expressions categorized into different emotions. </p>

  <h2 id="installation">Installation</h2>

  <p>To run the project, install the required dependencies. Use the following command:</p>

  <pre><code>pip install -r requirements.txt</code></pre>

  <h2 id="usage">Usage</h2>

  <p>Each model can be used for emotion recognition using the following commands:</p>

  <!-- Repeat the following pattern for each model -->
  <h3>MobileNetV2 Model</h3>

  <pre><code>python evaluate_model.py --model mobilenetv2 --image_path test_image.jpg</code></pre>

  <!-- Repeat the above pattern for the other 7 models -->

  <h2 id="models">Models</h2>

  <!-- Model 1: MobileNetV2 -->
  <h3>1. MobileNetV2</h3>

  <ul>
    <li>Pre-trained Architecture: MobileNetV2</li>
    <li>Modification: Additional dense layers for emotion classification.</li>
  </ul>

  <!-- Model 2: VGG16 -->
  <h3>2. VGG16</h3>

  <ul>
    <li>Pre-trained Architecture: VGG16</li>
    <li>Modification: Flatten layer and dense layers for emotion classification.</li>
  </ul>

  <!-- Repeat this pattern for each of the other 6 models -->

  <!-- Include details for models 3 to 8 -->
  <!-- ...

  <!-- Model 3: InceptionV3 -->
  <h3>3. InceptionV3</h3>

  <ul>
    <li>Pre-trained Architecture: InceptionV3</li>
    <li>Modification: GlobalAveragePooling2D and dense layers for emotion classification.</li>
  </ul>

  <!-- Model 4: DenseNet201 -->
  <h3>4. DenseNet201</h3>

  <ul>
    <li>Pre-trained Architecture: DenseNet201</li>
    <li>Modification: GlobalAveragePooling2D and dense layers for emotion classification.</li>
  </ul>

  <!-- Model 5: DenseNet169 -->
  <h3>5. DenseNet169</h3>

  <ul>
    <li>Pre-trained Architecture: DenseNet169</li>
    <li>Modification: GlobalAveragePooling2D and dense layers for emotion classification.</li>
  </ul>

  <!-- Model 6: VGG19 -->
  <h3>6. VGG19</h3>

  <ul>
    <li>Pre-trained Architecture: VGG19</li>
    <li>Modification: Flatten layer and dense layers for emotion classification.</li>
  </ul>

  <!-- Model 7: ResNet152 -->
  <h3>7. ResNet152</h3>

  <ul>
    <li>Pre-trained Architecture: ResNet152</li>
    <li>Modification: GlobalAveragePooling2D and dense layers for emotion classification.</li>
  </ul>

  <!-- Model 8: ResNet101 -->
  <h3>8. ResNet101</h3>

  <ul>
    <li>Pre-trained Architecture: ResNet101</li>
    <li>Modification: GlobalAveragePooling2D and dense layers for emotion classification.</li>
  </ul>

  <!-- ... -->

  <h2 id="data-preprocessing">Data Preprocessing</h2>

  <p>The dataset is located at <code>/content/drive/MyDrive/Colab Notebooks/train</code>. Images are loaded and preprocessed using OpenCV, and paths for each emotion category are defined.</p>

  <h2 id="training">Training</h2>

  <p>Models are trained using the ImageDataGenerator for data augmentation. Learning rate scheduling is applied during training for optimization.</p>

  <h2 id="results">Results</h2>

  <p>The project includes visualizations for training and validation loss/accuracy over epochs. Specific results for each model can be found in the respective sections.</p>

  <h2 id="contact-information">Contact Information</h2>
  <p>For questions or collaboration, please contact: 
   <a href="malikhamna107@gmail.com">gmail</a>
   <a href="https://www.linkedin.com/in/hamnamalik107/">Linkedin</a>
  </p>

</body>

</html>
