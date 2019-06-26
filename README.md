# Bats-EEG

Bats' EEG data was collected at Prof Yossi Yovel lab to distinguish between four states:
1. Asleep imobile - ASI
2. Asleep mobile - ASM
3. Awake imobile - AWI
4. Awake mobile - AWM

Unfortunately, the data distribution is very sparse with varying samples for each class (see the histogram in the code). 

The data has about 1100 samples from different bats and the classifier has to predict the labels of unseen samples.
I have decided to transform the EEG data from voltage over time to the frequency domain by creating a spectrogram for each sample and 
train the network with the spectrogram data.

The code for pre-processing, the model and results is available but the data does not.
