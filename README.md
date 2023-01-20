# Drone-Image-Classification-using-CNN-Imagenet-models-
This project is a deep learning image classification model that utilizes Imagenet's pre-trained models to classify a dataset of images. The dataset used in this project can be found at this <a href="https://drive.google.com/drive/folders/1zglFJPmfcbVIsIg4SwchuR2fLWCZvqjP?usp=sharing"> Link. </a> <br>
Sample images of this dataset <br><br>
![Picture](https://user-images.githubusercontent.com/68246393/157185204-87534206-1da4-4a67-bb45-5a9e74c9c2d5.png) <br><br>
The dataset contains 5 different categories of images, and the model has been finetuned to fit these categories using the ResNet152V2 model. The model achieved a training accuracy of 96.96% and a validation accuracy of 87.86%.

In the Resnet.ipynb file, you will find the complete training code for the model. Once the model has been trained, you can use the prediction.ipynb file to predict images using the saved pretrained model. The output of the program will be the predicted category for each image.

Please note that the dataset used in this project is provided for demonstration purposes only and is not intended for commercial use.<br>
Output of program <br><br>
![Picture12](https://user-images.githubusercontent.com/68246393/157185712-a8b89f4d-2936-4210-843a-c455b753e76a.png) <br>
<div align="center">
    <a href="./">
        <img src="https://user-images.githubusercontent.com/68246393/157185712-a8b89f4d-2936-4210-843a-c455b753e76a.png" width="59%"/>
    </a>
</div>
## Getting Started 

1. Clone the repository <br>
``` shell
git clone https://github.com/ShubhamSongire/Drone-Image-Classification-using-CNN-Imagenet-models-
```

2. Install the required dependencies
``` shell
pip install -r requirements.txt
```

3. Run the Resnet.ipynb file to train the model

4. Run the prediction.ipynb file to predict images using the trained model

## File Structure
├── Resnet.ipynb  <br>
├── Inception V2.ipynb<br>
├── prediction.ipynb <br>
├── requirements.txt <br>
└── dataset/ <br>
    ├── train/ <br>
    │   ├── rocket / <br>
    │   ├── fighter_jet /<br>
    │   ├── helicopter /<br>
    │   ├── passenger_plane /<br>
    │   └── drone /<br>
    ├── val/<br>
    │   ├── rocket / <br>
    │   ├── fighter_jet /<br>
    │   ├── helicopter /<br>
    │   ├── passenger_plane /<br>
    │   └── drone /<br>
    
## Built With
Keras - The deep learning framework used <br>
Imagenet - Pre-trained models used <br>

## Authors - [ShubhamSongire](https://github.com/ShubhamSongire) <br>

## Acknowledgments
Imagenet for providing the pre-trained models used in this project<br>
Dataset for providing the dataset used in this project
