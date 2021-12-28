# SimCLR Exam project
David Bro Ludvigsen, Rasmus Steen Mikkelsen, Victor Tolsager Olesen

DTU Compute, Department of Mathematics and Computer Science

This repository contains the poster and code for the course 02456 Deep Learning

## Reproduction

* Run pretraining for the desired model (simclr_rexnet.ipynb, simclr_resnet34.ipynb or simclr_resnet50.ipynb)
* Perform finetuning on the model architecture which has been pretrained (Either rexnet_finetune.ipynb or resnet_finetune.ipynb)
* To visualize misclassifications run misclassifications.ipynb
* Visualization of performance can be aquired by running visualization.ipynb, although it requires Weights and Biases as data has been logged and exported. (With the exception of finetuning performance, which is logged to a local file while finetuning)
