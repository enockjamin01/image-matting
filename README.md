
# Image matting

Image Matting is a project that's inspired by Apple's Photo Subject copy feature in their iPhones. This is an Image segmentation model built on top of a U-Net architecture,
the primary purpose of the model is to predict the main subject in the image segment and using the segmented image given by the model, the original image is compared to the segmented image, and the subject in the original image is removed.

This model is trained with around 950 images for 300 epochs with a batch of 32

## Input shape:
(128,128,3)

## Modules to install
```bash
python3 -m pip install TensorFlow

pip install opencv-python

pip install matplotlib

pip install numpy
```

## Note
Make sure to change all the directory names to ur directory path in the code

## Model working

### Original image
![Original image](https://github.com/enockjamin01/image-matting/blob/main/plots/original.png)

### Segmented image
![Segmented image](https://github.com/enockjamin01/image-matting/blob/main/plots/segmented.png)

### Region image
![Region image](https://github.com/enockjamin01/image-matting/blob/main/plots/region.png)

## Model loss and accuracy

### Accuracy
![Accuracy](https://github.com/enockjamin01/image-matting/blob/main/plots/accuracy.png)

### Loss
![Loss](https://github.com/enockjamin01/image-matting/blob/main/plots/loss.png)



