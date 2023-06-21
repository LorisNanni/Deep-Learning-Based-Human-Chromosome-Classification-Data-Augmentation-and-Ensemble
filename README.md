# Deep-Learning-Based-Human-Chromosome-Classification-Data-Augmentation-and-Ensemble
Deep Learning-Based Human Chromosome Classification: Data Augmentation and Ensemble

In the function ExampleDataAugmentation.m you can find example for both data augmentation and straightening,

very important: 

The function straightening() handles whether the background is white or black,

if the color is not uniform (or it uniform but no white or black) it is necessary to segment first to extract the chromosome,"


Moreover, in ExampleDataAugmentation.m, we show how to train the ResNet50, for more details on how to use ResNet50 in matlab you can read:

mathworks.com/help/deeplearning/ug/train-deep-learning-network-to-classify-new-images.html

For SWIN we have used https://timm.fast.ai/
