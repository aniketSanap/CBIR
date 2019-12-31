# CBIR
A simple Content Based Image Retrieval method using pretrained resnet and densenet. The pretrained models are trained on the Imagenet dataset and taken from `torchvision.models`. <br><br>The dataset used to retrieve similar images can be found [here](https://drive.google.com/file/d/0B4KI-B-t3wTjbElMTS1DVldQUnc/view). <br>It is a jewellery dataset with four classes:
<br><b>1. </b>Bracelet<br>
<b>2. </b>Ring<br>
<b>3. </b>Earring<br>
<b>4. </b>Necklace<br><br>
Each class contains about 300 images each. The similar images returned do not take the class of the image into account which makes this an unsupervised approach.<br>
Find my blog post on this project [here](https://aniketsanap.github.io/Content-Based-Image-Retrieval/)
