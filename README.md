# Potato-Leaf-Disease-Dataset


This model predicts potato diseases.This model prediction accuracy is 99.67%(test data) && 98% accuracy for the validation data.

# Dataset
## Data preprocessing
The data_augmentation model uses for dataset preprocessing.
* Flip (horizontal)
* Roation (0.2)
* Zoom (0.2)
* Height (0.2)
* Width (0.2)
* Rescaling (0-255)-(0-1)

## Images
![screenshot](https://github.com/HSAkash/Potato-Leaf-Disease-Dataset/raw/main/related_images/original.png)

## After augmetation
![augmetation_image](https://github.com/HSAkash/Potato-Leaf-Disease-Dataset/raw/main/related_images/augmented_image.png)

## CNN model
CNN model is used to train the network.<br>
Layer parameters:<br>
* Input size (224,224,3)
* Conv2D with 60 filters
* MaxPool2D (pool_size=2)
* Conv2D with 60 filters
* MaxPool2D (pool_size=2)
* Conv2D with 60 filters
* MaxPool2D (pool_size=2)
* GlobalAveragePooling2D
* Output

1.Conv2D with 60 filters (output)

# Requirements
* matplotlib==3.5.2
* numpy==1.23.1
* Pillow==9.2.0
* scikit-learn==1.1.1
* scipy==1.8.1
* tensorflow==2.9.1


# Demo
Here is how to run the potato disease program using the following command line.<br>
```bash
python potato.py
```

# Directories
<pre>
│  potato.py
│
├─env
├─Potato
|   ├─Train
|   ├─Test
|   ├─Valid
|
</pre>
