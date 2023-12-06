# automatic-license-plate-recognition
CNN-based Text Recognition for Automatic License Plate Recognition (ALPR).

Access the cascade classifier file through the following link: https://www.kaggle.com/datasets/sarthakvajpayee/ai-indian-license-plate-recognition-data?select=car.jpg

Within this repository, you'll discover a program designed to identify characters on car license plates. Leveraging a pre-trained cascade classifier file (indian_license_plate.xml), specifically tailored for detecting Indian license plates, the code detects the regions associated with license plates. Subsequently, certain functions are applied to further segment the images, isolating individual characters onto separate images.

The Convolutional Neural Network (CNN) model accepts inputs of size 28x28 pixels across all three color channels, featuring five CNN layers and two Artificial Neural Network (ANN) layers. Trained on a diverse dataset encompassing various numbers and letters, the CNN is employed to recognize characters on the previously segmented images. This facilitates the identification of numbers or letters displayed on car license plates.
