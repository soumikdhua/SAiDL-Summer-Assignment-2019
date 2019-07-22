# UCF-11 Video Classification with CNN (ResNeXt-101)
This repository contains a jupyter notebook which contains code for video classification task using [UCF-11 Dataset](https://www.crcv.ucf.edu/data/UCF_YouTube_Action.php), also known as YouTube Action Dataset. 
I have used PyTorch for this video classification task and did all of my work on [Google Colab](https://colab.research.google.com/).

## Dataset
[UCF-11 Dataset](https://www.crcv.ucf.edu/data/UCF_YouTube_Action.php) has total 1601 videos from 11 action categories:basketball shooting, biking/cycling, diving, golf swinging, horse back riding, soccer juggling, swinging, tennis swinging, trampoline jumping, volleyball spiking, and walking with a dog.
## Model
I have used a model of ImageNet pretrained ResNeXt-101 for this task and finetuned the fully connected layer of the model as per the dataset requirements.

