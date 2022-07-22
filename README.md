# Description
A Flask Web application that recognizes your face whilst wearing a face mask.
<br/>

![Facial Recognition System Demo - smallest](https://user-images.githubusercontent.com/48753857/180050889-8c039d52-b8ec-4e16-9cd3-47f2f81cc2c6.gif)


# Details
This was the **FINAL YEAR PROJECT** and a group effort.
<br/>
<br/>
We trained an InceptionResNet Model using a Triplet Loss Function to recognize masked faces.

# Installation
pip install facenet-pytorch
<br/>
<br/>
pip install opencv-python
<br/>
<br/>
Download the Model and place it in a folder called *Models* in the root directory.
<br/>
<br/>
Pretrained model : https://drive.google.com/file/d/1qCw_JT4VYK-23NnCuT-s1TAY8FZRiRsN/view?usp=sharing

# Usage
You can register with your name and face (uncovered).
<br/>
<br/>
You can then login using your masked or normal face.

# Datasets
Train Dataset: VGGFace2.
<br/>
<br/>
Test & Validation Datasets: Labeled Faces in The Wild (LFW).

# Methodology
1) We applied the MaskTheFace module to turn our normal face datasets into masked face datasets.

![image](https://user-images.githubusercontent.com/48753857/180434889-248c9c8e-4766-43a0-8f99-6de17fe97a26.png)

2) We resized all of our images to the Size of 224*224

3) We then trained our model using the masked VGGFace2 dataset.

4) Finallly, we tested our model using the masked LFW dataset. 

# Credits
Olivier Moindrot, Stanford university, Triplet Loss: https://omoindrot.github.io/triplet-loss
<br/>
<br/>
timesler, University of Melbourne, Inception ResNet: https://github.com/timesler/facenet-pytorch
<br/>
<br/>
timesler, University of Melbourne,MTCNN: https://github.com/timesler/facenet-pytorch
<br/>
<br/>
Visual Geometry Group, University of Oxford, VGGFace2: https://github.com/ox-vgg/vgg_face2
<br/>
<br/>
Gary B. Huang, University of Massachusetts, LFW: http://vis-www.cs.umass.edu/lfw/
<br/>
<br/>
Aqeel Anwar, Georgia Institute of Technology, MaskTheFace: https://github.com/aqeelanwar/MaskTheFace
