# vnet-mri-segmentation-prostate

All rights reserved to Akaash Mohan Saxena for the code.

Here's VNet implementation of MRI image segmentation of prostate gland. A DICE Score of 0.94 is achieved through the implementation. The data is collected from https://liuquande.github.io/SAML/ which is publicly available. The data is first differentiated into images and masks. Then the data is normalized, standardized and converted into 3D volumes. Post this data augmentation, is VNet implementation. The training is handled by pytorch lightning, and Cross Entropy loss function is used as a metric. Finally, the training can be visualised by putting in your own WandB key. The results are provided in the end.
