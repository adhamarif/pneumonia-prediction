# pneumonia-prediction
Train a model by using deep learning and transfer learning on x-ray images to predict pneumonia disease.

Full code and documentation in the Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/19f_v84DhTCiHWBT8Hpn7Ao7d-OfvWnbf?usp=sharing)

## Results

* Both model shows high accuracy and low loss value after 10 epochs.

*CNN model*

![CNN-loss](https://github.com/adhamarif/pneumonia-prediction/assets/92054450/4bdc4c6a-0db6-464e-9dd4-634268a715f7)

*Pretrained model*

![TL-loss](https://github.com/adhamarif/pneumonia-prediction/assets/92054450/f786241f-92ed-4ee3-b05f-f050d34b226f)

* Both model have same AUC-ROC value (0.99) which shows it have higher True Positive rate and lower False Positive rate. Both models perform well to predict pneumonia.

*CNN model*

![ROC-CNN](https://github.com/adhamarif/pneumonia-prediction/assets/92054450/9f350e3e-c1a3-4a23-9a58-fada62277404)

*Pretrained model*

![ROC-TL](https://github.com/adhamarif/pneumonia-prediction/assets/92054450/68640e51-a209-4340-a578-7c32c243ea87)

