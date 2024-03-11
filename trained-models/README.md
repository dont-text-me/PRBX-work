# This document contains a record of all the models trained during the project

| Architecture            | Training time | Accuracy | Confusion matrix                                     | learning rate | momentum | Gamma (scheduler) | Step size(scheduler) |
|-------------------------|---------------|----------|------------------------------------------------------|---------------|----------|-------------------|----------------------|
| ResNet 18               | 18 minutes    | 93.0%    | ![](confusion-matrices/resnet_18_93_acc.png)         | 0.001         | 0.9      | 0.1               | 10                   |
| ResNet 34               | 34 minutes    | 93.6%    | ![](confusion-matrices/resnet_34_93_acc.png)         | 0.001         | 0.9      | 0.1               | 8                    |
| EfficientNet V2 (small) | 42 minutes    | 90.5%    | ![](confusion-matrices/efficientnet_v2_s_91_acc.png) | 0.001         | 0.9      | 0.1               | 8                    |
| Swin transformer (tiny) |               |          |                                                      |               |          |                   |                      |