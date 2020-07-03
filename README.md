# SA-Diagnet: Self-attention-based network for diagnosing histopathological images
This repository contains the source code of our work for classifying histopathological images using hollistic attention network. Breifly, we introduce an attention-based network to classify breast biopsy images. We streamline the histopathological image classification pipeline and show how to learn representations from gigapixel size images end-to-end. Our network extends the bag-of-words approach and uses self-attention to encode global information, allowing it to learn representations from clinically relevant tissue structures without any explicit supervision.

## Dependencies

Our source code requires:
* OpenSlide (for reading whole slide images)
* PyTorch (for deep learning)
* Other python libraries like scikit, opencv.

**Note:** We have tested our code in Python3 only. If you are using Python2, please make appropriate changes.

### Install OpenSlide
You can install OpenSlide using below commands:
```
sudo apt-get install openslide-tools
sudo apt-get install python-openslide
pip install openslide-python
 
```

We have tested our code only on linux environments. If you are facing issues installing OpenSlide, please check here:
```
https://openslide.org/
```

## Install PyTorch
Please see below webpage for installing PyTorch. We have tested our code with PyTorch 1.0+.

``` 
https://pytorch.org/
```

## Install other dependencies
Other dependencies can be installed by running the below command:
```
pip install -r requirements.txt 
```

## Training and Evaluation
See scripts `training_script.sh` and `eval_script.sh` for training and evaluation related examples


## Issues
Thanks for your interest in our work. For any issues, please raise a request.  