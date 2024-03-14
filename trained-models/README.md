# This document contains a record of all the models trained during the project. 


| Architecture                                                  | Training time     | Accuracy | Confusion matrix                                             | Batch size | learning rate | momentum | Gamma (scheduler) | Step size(scheduler) |
|---------------------------------------------------------------|-------------------|----------|--------------------------------------------------------------|------------|---------------|----------|-------------------|----------------------|
| ResNet 18                                                     | 18 minutes        | 93.0%    | ![](confusion-matrices/resnet_18_93_acc.png)                 | 16         | 0.001         | 0.9      | 0.1               | 10                   |
| ResNet 34                                                     | 34 minutes        | 93.6%    | ![](confusion-matrices/resnet_34_93_acc.png)                 | 16         | 0.001         | 0.9      | 0.1               | 8                    |
| EfficientNet V2 (small)                                       | 42 minutes        | 90.5%    | ![](confusion-matrices/efficientnet_v2_s_91_acc.png)         | 16         | 0.001         | 0.9      | 0.1               | 8                    |
| ResNet 34 (with improved background removal)                  | 28 minutes        | 93.4     | ![](confusion-matrices/resnet_34_whitebg_93_acc.png)         | 16         | 0.001         | 0.9      | 0.1               | 8                    |
| ResNet 18 (with improved background removal)                  | 22 minutes        | 91.9%    | ![](confusion-matrices/resnet_18_whitebg_92_acc.png)         | 16         | 0.001         | 0.9      | 0.1               | 10                   |
| ResnNet 34 (improved background, smaller batches)             | 29 minutes        | 94.1%    | ![](confusion-matrices/resnet_34_whitebg_94_acc_8_batch.png) | 8          | 0.001         | 0.9      | 0.1               | 10                   |
| ResnNet 34 (improved background, even smaller batches)        | 31 minutes        | 93.7%    | ![](confusion-matrices/resnet_34_whitebg_93_acc_4_batch.png) | 4          | 0.001         | 0.9      | 0.1               | 10                   |
| Swin transformer (base, all but last layer frozen, 40 epochs) | 1 hour 50 minutes | 85.4%    | ![](confusion-matrices/swin_b_85_acc_4_batch.png)            | 4          | 0.001         | 0.9      | 0.1               | 10                   |


## Note: weights files not tracked but available on request