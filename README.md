# Project Code and Executables

## Dataset Access
Access the audio dataset [here](https://github.com/sstober/openmiir/tree/master/audio).<br>
For EEG data, access it [here](https://academictorrents.com/details/c18c04a9f18ff7d133421012978c4a92f57f6b9c).

## This repository contains a collection of Executables files organized as follows:

**Classification**: This folder contains files for dataset preprocessing, model training, and testing for classification tasks.<br>

`Preprocessing-14-ar+ep.ipynb`: Code for various feature extraction techniques necessary for classification.<br>
`P14-ica.fif`: Preprocessed data file.<br>
`Classification-14-ar+ep.ipynb`: Model training using SVM for classification and subsequent testing.<br>


**Reconstruction**: This folder contains files for dataset preprocessing, model training, and testing for reconstruction tasks.

`VLAAI_Training.ipynb`: Code for training the Vlaai Model.<br>
`VLAAI_Training-K-fold.ipynb`: Model training using k-fold cross-validation for consistency.<br>
`Similarity_Encoding.ipynb`: Feature extraction via similarity constraint encoding in the time domain.<br>
`RAW_ICA_JSON.ipynb`: Data preparation for subsequent time and frequency domain feature extraction.<br>
`Pwelch_and_Plotting.ipynb`: Feature extraction using pwelch method in the frequency domain with data visualization.<br>
`Preprocessing_stimuli_icassp.ipynb`: Baseline Code for generating stimulus envelope, used as a reference.<br>
`OpenMIIR_Regression_Vlaai_predictions.ipynb`: Baseline implementation for domain understanding.<br>
`Models_without_SCE.ipynb`: Model training without additional feature extraction techniques.<br>
`Models_with_Pwelch_OgEEG.ipynb`: Feature extraction from EEG data using pwelch method for time-frequency conversion.<br>
`Models_with_Pwelch_OgAudio.ipynb`: Feature extraction from stimuli using pwelch method for time-frequency conversion.<br>
`Envelope_generation_stimuli.ipynb`: Code for generating envelope from stimuli, used as ground truth.<br>
`Correlation.ipynb`: Testing code to find Pearson correlation.<br>
