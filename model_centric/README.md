# Model-Centric
- In this folder, we will be adding the code for all the methods from **Model-Centric Approach** that we will be trying.

## File Descriptions
- `vgg16_model.ipynb` -- This file stores the code of the VGG16 Model. It's a pre-trained model and considerable fine-tuning has been done, and has an **test accuracy of 0.7992,** **weighted F1-score of 0.7984**  and a **log-loss of 1.682** on the test dataset.
- `mobilenet_model.ipynb` -- This file stores the code of the MobileNet Model. It's a pre-trained model and considerable fine-tuning has been done, and has an **test accuracy of 0.8668,** **weighted F1-score of 0.8667** and a **log-loss of 1.005** on the test dataset.
- `xception_model.ipynb` -- This file stores the code of the MobileNet Model. It's a pre-trained model and considerable fine-tuning has been done, and has an **test accuracy of 0.8957,** **weighted F1-score of 0.8957** and a **log-loss of 0.8017** on the test dataset.
- `hybrid_ensembling.ipynb` -- This `.ipynb` notebook consists of code for the hybridization (ensembling) of the different fine-tuned models that we have considered in this study. In this, we have tried 2 different approaches, first, we have tried relative weighting of the predictions from the different models, and second, we have tried majority vote of the predicted class labels. Out of the 2 approaches, relative weighting of the predictions gave the best test set **accuracy of 0.905** with a **log-loss of 0.4107** on the test dataset.
