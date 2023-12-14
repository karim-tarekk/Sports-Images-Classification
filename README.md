# Sports-Image-Classification-CNN
<h1>Overview</h1>
<p>In today’s world of internet, a massive amount of data is getting generated every day and content-based classification of images is becoming an essential aspect for efficient retrieval of images and have attracted application in several fields and one of such field is sports. Building a model that is able to classify different sports activities into different categories could be useful for automated sports analysis tasks.</p>
<p>Images should be classified to what sport do they belong to using two known CNN Architectures</p>
<br>
<h1>DataSet</h1>
<h3>The Complete Dataset can be downloaded from here <a href="https://drive.google.com/file/d/1s07aL-7nvhO8ESJy_uTCZJMF5lw5LAGK/view" target="_blank">DOWNLOAD</a></h3>
<h4>This folder consists of two main subfolders:</h4>
<p>Train : contains 1681 images. The label is in the image name. Image format is a mix between png and jpg</p>
<p>Test: 688 images without labels all jpg</p>
<br>
<h1>Output File Format</h1>
<p>The Output file should be a .csv file which contains two columns: image_name,label. The image_name is the imagename.jpg, the label is the predicted class and should be one of the following values: 0,1,2,3,4,5</p>
<p>Where</p>
<p>Basketball --> 0</p>
<p>Football--> 1</p>
<p>Rowing--> 2</p>
<p>Swimming--> 3</p>
<p>Tennis--> 4</p>
<p>Yoga--> 5</p>

<p>The output file should contain exactly 688 lines (for the 688 images in the test set). The image names don't have to be in a particular order but each image in the test set must have exactly one row in your submission file. The file should contain a header and have the following format:</p>
<p>image_name,label</p>
<p>0.jpg,4</p>
<p>1.jpg,0</p>
<br>
<h1>Implemented Architectures</h1>
<h3>AlexNet Architecture</h3>
<img src="alexnet.png" alt="AlexNet Architecture" width="500" height="600">
<br>
<h3>VGG16 Architecture</h3>
<img src="https://datagen.tech/wp-content/uploads/2022/11/image2-1.png" alt="VGG16 Architecture" width="500" height="600">
