# IRCAD-Liver-Segmentation

This repository contains a deep learning–based liver segmentation project using CT scans from the IRCAD dataset. The work focuses on automatic liver segmentation, a critical task in medical image analysis with applications in clinical diagnosis, surgical planning, and treatment monitoring. The project was originally developed as a Kaggle Notebook and later structured for reproducibility and presentation on GitHub.

The implementation is inspired by the research paper *“A Deep Learning Approach for Liver and Tumor Segmentation in CT Images Using ResUNet”* published in **Bioengineering (2022)**. The paper proposes a hybrid ResUNet architecture that combines residual connections with the U-Net encoder–decoder framework to improve segmentation accuracy. This repository follows the same architectural principles and adapts them for liver segmentation on the IRCAD dataset.

The project includes data preprocessing, model training, evaluation, and visualization of predicted liver masks over CT slices. Model performance is evaluated using standard segmentation metrics such as Dice Coefficient and Intersection over Union (IoU). The notebook also contains qualitative visual results to demonstrate segmentation performance.

The original Kaggle notebook used to build this project is available at:
https://www.kaggle.com/code/aashiagarwal97/ircad-liver-segmentation

Due to licensing restrictions, the IRCAD dataset is not included in this repository. To reproduce the results, the dataset must be obtained from the official IRCAD source and placed locally, with dataset paths updated accordingly inside the notebook. This repository is intended strictly for research and educational purposes.

If you use or build upon this work, please cite the original research paper:
Rahman H., Bukht T.F.N., Imran A., Tariq J., Tu S., Alzahrani A. (2022). *A Deep Learning Approach for Liver and Tumor Segmentation in CT Images Using ResUNet*. Bioengineering, 9(8), 368. https://doi.org/10.3390/bioengineering9080368

This project is released under the MIT License.
