# PyTorch COVID-19 detection
![PyTorch_COVID-19_detection](assets/gradcam.png)

Detect COVID-19 from Chest X-Ray Images.

# Notebook

There are two notebooks in *notebooks* folder. One is for training, another for showing the GradCAM. 

Implemented COVID-Net architecture. See the paper for more details:

[COVID-Net: A Tailored Deep Convolutional Neural Network Design for Detection of COVID-19 Cases from Chest Radiography Images](https://arxiv.org/abs/2003.09871)

As the dataset is not balanced yet, focal loss was implemented. See the paper for more details:

[Focal Loss for Dense Object Detection](https://arxiv.org/abs/1708.02002)

# Dataset
These are the links that I've accumulated the dataset

- [ieee covid dataset](https://github.com/ieee8023/covid-chestxray-dataset)
- [Kaggle Pneumonia Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
