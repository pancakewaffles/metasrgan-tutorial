# metasrgan-tutorial
Repo for Meta-SRGAN tutorial. Contains some example images and pre-trained models.

Take a look at Tutorial_Super_Resolution.ipynb which provides a walkthrough of Super-Resolution in general, and Meta-SRGAN. Specifically it walks you through using Meta-SRGAN.

Take a look at Tutorial_Super_Resolution_full.ipynb if you would like to see the full pipeline for training Meta-SRGAN. It contains additional stuff like training EDSR and also some primer on Bicubic Interpolation but Part III: Meta-SRGAN walks you through training both the discriminator and the generator, at least the way I did it. It describes the loss functions I used, and also the training loop (e.g. grabbing data from the data loader, processing it into a batch, putting the input matrix into the Weight Prediction Network etc).

The Tutorial_Super_Resolution_full.ipynb is self-contained. It walks you through the code for data loaders, batch processor, visualisation tools, etc. It is divided into three parts, Part I: Traditional Interpolation like Bicubic Interpolation, Part II: EDSR, and Part III: Meta-SRGAN. Part II and Part III includes the training code for training their respective networks (EDSR and Meta-SRGAN).


