# TransferLearning_persianMNIST
We used sweep method of wandb to find best hyperparameters. We trained network on `persianMNIST` dataset. We used framework pytorch==1.8.2.

## Dataset
persianMNIST image dataset includes a training set of 960 samples and a test set of 240 samples. Each sample is resized to 64*64 pixels on a RGB associated with a tag of 10 classes. Please download dataset from [here](https://drive.google.com/drive/folders/1--LGkYnr8Biq9iD0B445YZNC7MOq7Fds?usp=sharing)

## Train
To train the model please run the file:
```
Train.py
```
## Training metrics
Show results on wandb [here](https://wandb.ai/zahra_zarrabi/pytorch-sweeps-demo?workspace=user-zahra_zarrabi)

## Test
To test the model please run the file:
```
Test.py
```

## Pretrained model
Please download the weights from [here](https://drive.google.com/file/d/1B1DDj_kBDgbfuvhedNRhGnFWABESboK-/view?usp=sharing) 

## Inference
to test the trained model, please run the following file:
```
python Inference.py --img_path data/2.jpeg --model_path model_mnist.pth --device GPU
```
