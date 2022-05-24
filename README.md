# PHCNN
Convolutional Neural Network for Semantic Segmentation

The project is divided to 2 parts: labeling catheter and guidewire separately.
In the file "model_label_1_v5.ipynb" you can see the model for the catheter,
and in the file "model_label_2_v16.ipynb" you can see the model for the guidewire.

The outputs are shown at the very bottom of the notebooks. You can see that there is a noise
in the output images, it is due to the small number of epochs. When this model is run on a
larger amount of epochs (25-100), the noise goes away.
