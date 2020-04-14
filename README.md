# MobileUNET

We describe a new UNET DNN architecture MobileUNET, which has less computation amounts than the original UNET[1].<br> 

MobileUNET cuts down computation amounts by replacing standard convolution layers to DW/PW convolution layers and inverted residuals, as mentioned in MobileNetV2[2].<br>


## Architecture
We replace conv3x3 blocks in original UNET to PWconv-DWconv-PWconv block, and modified the channel numbers.

original UNET:



## References:

[1] Ronneberger O, Fischer P, Brox T. U-net: Convolutional networks for biomedical image segmentation[C]//International Conference on Medical image computing and computer-assisted intervention. Springer, Cham, 2015: 234-241.<br>

[2] Sandler M, Howard A, Zhu M, et al. Mobilenetv2: Inverted residuals and linear bottlenecks[C]//Proceedings of the IEEE conference on computer vision and pattern recognition. 2018: 4510-4520.<br>
