# DivyaAnuvadak(ISL to text conversion)


Minor Project- Convert hand gesture(ISL) into equivalent text using Python, OpenCv, Tensorflow. 

## Abstract
Speech and hearing impairment people rely on sign language to express themselves, which most of the people find hard to understand. Because 
of this, even if they are capable, they lack opportunities. Thus, we came up with the idea of ‘DivyaAnuvadak’ which takes hand gesture as 
input and translate it to equivalent text.

This would further help both our community and our university to educate specially-abled girls.
We are trying to widen Apaji’s vision to educate every girl (specially-abled) that 
would ultimately help these 'Shantas' to shine too.

## Requirements

Python 

Jupyter Notebook/VS Code

Tensorflow 

Open CV 

## Steps of building this project

1.	First step is image collection for dataset.
2.	Then Labeling of images using LabelImg tool of python. 
3.	Next step is to split these images into training and testing data.
4.	Then a model is created for training and for that firstly we setup all the paths.
5.	Then a label map is created where each label will contain a unique id. After this, TF records is created using Tensorflow API.
6. Next step is to Download Tensorflow pertained models from tensorflow model.
7.	Then we Copy the model config to training folder and Update this config file for transfer learning.
8.	Finally we train the model.
9.	After training we can load the model from checkpoint and detect the gestures in real time.

## Real Time Detection

![object detection 15-02-2023 23_54_41](https://github.com/AyushiRajput1/DivyaAnuvadak/assets/104836701/1413ba58-90de-4093-8bba-290da2cca7c2)

![1688038737865](https://github.com/AyushiRajput1/DivyaAnuvadak/assets/104836701/88fb8565-06bc-440d-a2a6-2b917d7e0eb4)

![object detection 15-02-2023 23_54_35](https://github.com/AyushiRajput1/DivyaAnuvadak/assets/104836701/21967365-ddf7-47e2-b31e-22cdcfd1d1aa)
