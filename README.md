The project constisted in analyzing the "Segmenter: Transformer for Semantic Segmentation" paper and fine-tuning the tiny version of the model on Cityscapes.
In particular, 2 different fine-tunings were made, one using the linear decoder, and the other using the Mask decoder introduced in the paper. Both the fine-tuning configuration for the 2 model were the same.
After that, an ablation study on the 2 models' accuracies (mIoU) was conducted.

The 2 models can be found at https://huggingface.co/NicolasCola7/Segmenter-Tiny-16x16-patches
