# Predicting COVID-19 Status from Cough Recordings using the COUGHVID Dataset

Using machine learning to predict COVID-19 status (healthy/ symptomatic (not diagnosed)/ COVID-19 (diagnosed)) from cough recordings.

Dataset link:  
https://zenodo.org/record/4498364#.YOwXX-gzZEZ

Source code:  
[Source code files](https://c4science.ch/diffusion/10770/)  
Orlandic, L., Teijeiro, T. & Atienza, D. The COUGHVID crowdsourcing dataset, a corpus for the study of large-scale cough analysis algorithms. *Sci Data* 8, 156 (2021). https://doi.org/10.1038/s41597-021-00937-4  
- Convert files: A quick function to automatically convert all of the compressed .webm and .ogg files in the COUGHVID dataset to the more usable .wav format. Note: you must have FFMPEG installed for this to work.
- DSP: This file contains all digital signal processing functions, including filtering the recordings and classifying between cough and non-cough sounds.
- Features: This file contains all of the functions used for the computation of audio signal features commonly used in cough classification.
- Segmentation: This file contains a function for segmenting a recording into individual cough signals, and additional code to compute the SNR of the recording.

## 1. Data Pre-Processing
1. Convert the .webm and .ogg files in the dataset to .wav files as recommended.
2. Read the *metadata_compiled.csv* file from the dataset.
3. 



## 2. Exploratory Analysis: Clustering




## 3. Supervised Model Training
### 3.1. SVM
### 3.2. XGBoost





## 4. Results

