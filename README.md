# Neural Connectivity Synchronization App

## Problem Definition.
Evaluation, Visualization and Prediction of neural connectivity and synchronization patterns in functional brain regions.

## What and Why
Problem Definition: Physicians would rather spend valuable time evaluating the patient`s behavioral symptoms rather than examining EEG waveforms in order to extract diagnostic information. This App, built to evaluate, visualize & predict neural connectivity and synchronization patterns for patients with neurological disorder, will help physicians, health care provider make objective decisions.

Study elements include hypothesis question: Is there some disruption in neural synchronization pattern present in brain regions of patients with neurological disorder? What does the disordered pattern look like? Classification of patients based on extracted observed pattern in combination with other behavioral factors will help make an objective diagnosis decision.

## Input
Input: 12 channel  EEG signal from 105 normal individuals and 80 individuals with Autism Spectrum Disorder (ASD). 250hz sampled measurements was obtained from EGI equipment with 19 sensors located at the different regions of the brain. (Frontal-F, Parietal/polar-P, Frontal pole-Fp, Temporal-T, Occipital-O) with a 10-20 channel montage scheme, time series data set.

## Algorithm
Algorithm: EEG artifact filter, Fast Fourier Transform, Butterworth bandpass filtering, Phase coupling over distance,   classification algorithm, Python 3d Viewer, ,PyQt5, PyQtgraph, blender

## Ouput
Output: Generate data to support further development of neural connectivity capabilities, aggregate matrix made up of the correlation coefficient values, Sensor Correlation matrix, strength of synchronization, Measures of inter-band difference,  brain region synchronization plot, 2d & 3d visualizations, classification analysis report.

## Current work and Work-in-progress
Correlation matrix and graph of hot correlated sensors generated. The video snippet bellow shows the front end GUI of the App in development mode. Current tabs include 
- Image viewer: Generate patterns in segments of the measurement period and visualize aggregate mode patterns for abnormal vs normal neural circuits. 
- Data aggregator/viewer: Tabulates the extracted matrix and labelled pattern. In the current build, keeping all the variables constant 157/180 of ASD patients possess the     pattern observed on the left image, while 140/150 of normal patient possess the observed pattern on the right. 
- ML Classifier: The third tab shows Machine Learning Classification report planned to apply random forest and classify the extracted patterns and the fourth tab is designed to perform hardware input/output functions. 
- The third & fourth tab is still work in progress.
