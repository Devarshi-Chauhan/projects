Before looking into a complicated and computationally expensive model such as a CNN for the
classification of normal and abnormal heartbeats, first a simple 2 layer feed forward network will
be used to establish a model to use as a benchmark. This is to make sure that any further
complexity delivers additional value.
The baseline for the classifier of normal and abnormal heartbeats would be an accuracy of
about 60%. This because the Physionet Cardiology Challenge 2016 provided a baseline score
of 71%

The feature extractions methods involved are:

● MFCC: representation of the short-term power spectrum of a sound
● Mel-frequency cepstral coefficients: Coefficients that collectively make up an
mel-frequency cepstrum
● Chromagram of a short-time Fourier transform: Projects into bins representing the 12
distinct semitones of the musical octave
● Octave-based spectral contrast: Distribution of sound energy over octave frequencies
● Tonnetz: Estimates tonal centroids features

Since the datasets provided have labeled data and are imbalanced other measurement besides
accuracy are necessary. Therefore the other metrics to be used to evaluate the performance of
the the model are: precision, recall and f1 score.
