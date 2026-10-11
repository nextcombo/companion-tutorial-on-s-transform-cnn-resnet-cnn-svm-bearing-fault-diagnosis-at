# Companion tutorial on S-transform - CNN, ResNet, CNN-SVM, bearing fault diagnosis at Case Western Reserve University and Jiangnan University using MATLAB code

In the previous issues, two articles on time-frequency transformation combined with machine learning for fault diagnosis were introduced, as follows:
Nanny-level tutorial on Continuous Wavelet Transform - CNN, ResNet, CNN-SVM, CNN-BiGRU, CNN-LSTM fault diagnosis, MATLAB code
Nanjing University of Science and Technology Bearing Data Diagnosis - Comprehensive Course on Continuous Wavelet Transform - CNN, ResNet, CNN-SVM, MATLAB Code
This issue introduces another method for bearing diagnosis based on S-transformation-CNN, ResNet, CNN-SVM, and CNN-LSTM. The validation is conducted using two major datasets from Case Western Reserve University and Jiangnan University.
Content Summary
In response to the challenges of traditional methods in mechanical fault diagnosis, such as difficulties in feature extraction and complex classifier training, this paper proposes a rolling bearing fault diagnosis method based on S transform and convolutional neural network (CNN).
Firstly, the original data of bearings is transformed into time-frequency graph through S transformation. Then, fault classification is conducted by CNN/ResNet/CNN-SVM/CNN-LSTM/CNN-BiGRU.
Regarding S transformation
S transform improves the short-time Fourier transform and continuous wavelet transform's drawbacks while inheriting their advantages. It employs a Gaussian window function (with width inversely proportional to frequency) to avoid the deficiencies of window selection and fixed window width. Its time-frequency representation directly links the phase spectrum of each frequency component with the original signal, making it suitable for the processing of non-stationary signals.
ST-CNN, ST-CNN-SVM, ST-ResNet, ST-CNNBiGRU, ST-CNNLSTM.  
The process is as follows.
① Process the bearing data of Case Western Reserve University and Jiangnan University.
② Utilize S transformation to convert the bearing dataset into a time-frequency diagram, extracting both frequency domain and time domain information, thereby providing more detailed features for subsequent fault diagnosis.
③ To facilitate the training of the model and considering the memory capacity of the computer, the time-frequency diagram is resized to 64×64×3 dimensions, and the extracted feature data are saved.
④ Construct separate models: CNN, ResNet, CNNBiGRU, CNNLSTM, CNNSVM. Feed the feature data into the models and use 70% of the data as the training set and 30% as the test set to train and test the models.

## Images

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
