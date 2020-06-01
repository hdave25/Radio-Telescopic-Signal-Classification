# Radio-Telescopic Signal Classification

The dataset consists of spectrogram images of different Radio-Telescopic Signals simulated by SETI (Search for Extra Terrestrial Intelligence) Institute. The dataset has 7 classes of radio signals and can be downloaded from [here](https://www.kaggle.com/tentotheminus9/seti-data, "SETI Radio Signal Data"). 

For classification, Transfer Learning was used to train ResNet50 model on this dataset. I have also built a custom deep CNN network and it gave near about performance. The dataset contains 7000 images (1000 images per class). It was split as 5600 images for training, 700 images for validation and 700 images for testing.
