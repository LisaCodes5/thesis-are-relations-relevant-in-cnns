# Are Relations Relevant in CNNs? A Study Based on a Facial Dataset

Here is all my code and all results for my Bachelor thesis.
Although both, fully connected CNNs and FCNs are Convolutionial Neural Networks and therefore "CNNs", "CNN" here referes to the fully connected CNNs.

## Preparations
It contains the "canvassed" images, the feature labels and the original pictures (A part of the FASSEG Dataset [1])
The code in here is the one used to generate the images in "picasso_dataset". Although masks were generated, they weren't used and are therefore omitted.

## picasso_dataset
In here are the images used to train and test the CNNs and FCNs, generated in Preparations.

## CNN
In here is the code for all training and testing regarding the CNNs. For every Jupyter notebook I created a PDF containing code+results, because sometimes I had a weird issue, where for no reasons the result was gone and only the code was still there.

## FCN
In here is the code for all training and testing regarding the FCNs. For every Jupyter notebook I created a PDF containing code+results, because sometimes I had a weird issue, where for no reasons the result was gone and only the code was still there.

## Known issues
A mistake made its way into the training testing code: The loss is displayed as percentage, please ignore that.
Although I've written "baseline" dataset in my thesis, the code refers to "basis" data as this was the previous title.

## Code
The code for generating the images is the one used in [2] only altered slightly.
The code for training and testing the CNNs and FCNs is inspired by or partly from [3],[4] and [5]

## References
[1] Khalil Khan, Massimo Mauro, Riccardo Leonardi, "Multi-class semantic segmentation of faces", IEEE International Conference on Image Processing (ICIP), 2015

[2] Johannes Rabold, Gesina Schwalbe, Ute Schmid, "Expressive explanations of dnns by combining concept analysis with ILP", Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics), 2020

[3] https://deeplizard.com/learn/playlist/PLZbbT5o_s2xrwRnXk_yCPtnqqo4_u2YGL 

[4] https://towardsdatascience.com/implementing-a-fully-convolutional-network-fcn-in-tensorflow-2-3c46fb61de3b

[5] Joachim Steinwender, Roland Schwaiger, "Neuronale Netze programmieren mit Python", Rheinwerk Verlag, 2020
