# Analysis of time series data
## Introduction
Before looking into a complicated and computationally expensive model such as a CNN for the classification of normal and abnormal heartbeats, first a simple 2 layer feed forward network will be used to establish a model to use as a benchmark. This is to make sure that any further complexity delivers additional value.
The baseline for the classifier of normal and abnormal heartbeats would be an accuracy of about 60%. This because the Physionet Cardiology Challenge 2016 provided a baseline score of 71%.

The feature extractions methods involved are:

<li> MFCC: representation of the short-term power spectrum of a sound.</li>
<li> Mel-frequency cepstral coefficients: Coefficients that collectively make up an mel-frequency cepstrum.</li>
<li> Chromagram of a short-time Fourier transform: Projects into bins representing the 12 distinct semitones of the musical octave.</li>
<li> Octave-based spectral contrast: Distribution of sound energy over octave frequencies.</li>
<li> Tonnetz: Estimates tonal centroids features.</li>

Since the datasets provided have labeled data and are imbalanced other measurement besides accuracy are necessary. Therefore the other metrics to be used to evaluate the performance of the the model are: precision, recall and f1 score.

## Requirements
<li>Keras==2.1.5</li>
<li>librosa==0.5.1</li>
<li>matplotlib==2.2.2</li>
<li>numpy==1.14.2</li>
<li>pandas==0.22.0</li>
<li>scikit-learn==0.19.1</li>
<li>scipy==1.0.1</li>
<li>tensorflow==1.7.0</li>
<li>h5py==2.7.1</li>
<li>html5lib==0.9999999</li>
<li>ipykernel==4.8.2</li>
<li>ipython==5.5.0</li>
<li>joblib==0.11</li>
<li>jsonschema==2.6.0</li>
<li>jupyter==1.0.0</li>
<li>jupyter-client==5.2.3</li>
<li>jupyter-console==5.2.0</li>
<li>jupyter-core==4.4.0</li>
