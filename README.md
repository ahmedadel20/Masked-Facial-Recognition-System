# Description
A Flask Web application that recognizes your face when you're wearing a face mask.
<br/>

![Facial Recognition System Demo - smallest](https://user-images.githubusercontent.com/48753857/180050889-8c039d52-b8ec-4e16-9cd3-47f2f81cc2c6.gif)


# Details
This was the **FINAL YEAR PROJECT** and a group effort.
<br/>
<br/>
We trained an InceptionResNet using a Triplet Loss Function to recognize masked faces.

# Installation
pip install facenet-pytorch
<br/>
<br/>
pip install opencv-python
<br/>
<br/>
Download the Model and place it in a folder called Models in the root directory.
<br/>
<br/>
model : https://drive.google.com/file/d/1qCw_JT4VYK-23NnCuT-s1TAY8FZRiRsN/view?usp=sharing

# Usage
You can register with your name and face (uncovered).
<br/>
<br/>
You can then login using your masked or normal face.

# Credits
Olivier Moindrot, Triplet Loss, https://omoindrot.github.io/triplet-loss
<br/>
<br/>
timesler, Inception ResNet, https://github.com/timesler/facenet-pytorch
<br/>
<br/>
timesler, MTCNN, https://github.com/timesler/facenet-pytorch
