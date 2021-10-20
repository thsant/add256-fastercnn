# Training Faster R-CNN on ADD256 (Embrapa Apples by Drones Detection Dataset)

This code is a supplementary material for the paper _A methodology for detection and location of fruits 
in apples orchards from aerial images_, written by Thiago Santos and Luciano Gebler and presented at 
[SBIAgro 2021](https://eventos.unipampa.edu.br/sbiagro/) (the XIII Congresso Brasileiro de Agroinformática). 
This work presents a methodology for automated fruit counting employing aerial-images, including
algorithms based on multiple view geometry to perform fruits tracking.

The present code details just the _apple's detection part_, as presented on Section 2.1.1 in the paper. 
We have employed a **Faster R-CNN network** with a **ResNet-50 backbone**, using tochvision 0.10.0 (model),
PyTorch Lightning (training) and Albumentations (augmentations).

