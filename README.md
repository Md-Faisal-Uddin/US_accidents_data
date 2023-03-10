# US_accidents_data
Data for US_accidents_data was obtained from Kaggel.com.

# HeartViT
A stethoscope's sound from heart is analyzed to diagnose a variety of diseases  caused by cardiovascular disease such as heart attack, heart failure, stroke, arrhythmia,
heart valve complications etc.The goal of this study is to use artificial intelligence algorithms to diagnose heart failure by classifying heart sounds.We use MFCC to convert heart 
sounds to images and to recognize images using the latest Google’s research called Vision Transformer(ViT).The primary process of this research is to identify and classify data 
related to heart sounds, which are classified into four general groups from S1 to S4.The sounds S1 and S2 are considered to be normal heart sounds.S3 and S4 are abnormal heart sounds 
(heart murmurs), each indicating a different type of heart disease.

Dataset Name: The CirCor DigiScope Phonocardiogram Dataset

The dataset would be used in this study is from the PhysioNet and PASCAL challenge open access data, which was carefully collected by  physician.
A total number of 5272 heart sound recordings were collected from the main four auscultation locations of 1568 subjects, aged between 0 and 21 years.
 
The dataset contains four data file types (one for each subject):
  For each subject, a wave recording file (binary.wav format) containing heart sound data is created.
  A header file (text.hea format) that describes the .wav file in standard WFDB format.
  A segmentation data file (text.tsv format) for each auscultation location, containing segmentation information about the start and end points of the fundamental heart sounds S1 and S2.
  A subject description text file (text.txt format) for each subject, with the file name corresponding to the subject ID. Demographic data such as weight, height, 
  sex, age group and pregnancy status as well as a detailed description of murmur events(abnormal sounds) are provided in this file.
  
The file training_data.csv contains the overall information for all the records of the training set in the PhysioNet Challenge 2022.

The PCG sounds was collected on the body surface:
  PV corresponds to the Pulmonary Valve point.
  TV corresponds to the Tricuspid Valve point.
  AV corresponds to the Aortic Valve point.
  MV corresponds to the Mitral Valve point.

EXPLORATORY DATA ANALYSIS

Used librosa library to load the way audio files.
Visualized sound waves in time scale.
Visualized spectrogram in frequency scale.
Visualized MFCCs in Quefrequency scale.
Visualized MFCCs with first and second derivative.
Plotted the violin plot to visualize the frequency of heartbeats.
Split the dataset into train, validation and test.
