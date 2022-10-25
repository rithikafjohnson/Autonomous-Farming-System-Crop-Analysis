The code is in the .ipynb file.

In the driver code, path1 contains the path to the Rice Disease dataset.

In the function "segmentation", there are 3 different segmentation algorithms implemented, which can be chosen with the "mode" arguement in the function call.

mode=0: Gray scale image
mode=1: Thresholding
mode=2: Felzenszwalb Segmentation
mode=3: SLIC Segmentation

The classifier can be trained using the "svc" function which takes a list of grayscale images and a list of their respective labels. The model is then saved after training.

The included model is the one that gives the highest accuracy (73%). The images used to train this model were not segmented (mode=0). 