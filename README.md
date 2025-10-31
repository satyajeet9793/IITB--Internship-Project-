# IITB--Internship-Project-
# Visual Attention Mapping Across Task Types

IITB EdTech Internship 2025  
Track: Educational Data Analysis (EDA)  
Group ID: T1_G40  
Team Name: TEAM_DRS  
Department: Data Science  
Faculty Mentor: Mrs. Mrunal M. Wakarekar  

## Project Overview
This project focuses on analyzing visual attention behavior of learners across different task types (easy, medium, and hard).  
Using eye-tracking data, we generate saliency maps and perform comparative analysis to understand how attention patterns vary with task difficulty.  
The insights from this study can help in improving adaptive learning systems and human-computer interaction in education.

## Objectives
- To study and compare visual attention patterns across different task types.  
- To generate empirical saliency maps using eye-tracking fixation data.  
- To apply deep gaze models for predictive attention mapping.  
- To analyze focus variation and attention distribution across easy, medium, and hard tasks.  
- To visualize and interpret gaze-based behavioral insights.

## Methodology
1. Data Collection – Eye-tracking and behavioral data for different tasks.  
2. Preprocessing – Data cleaning, blink removal, and normalization.  
3. Feature Extraction – Fixation points, durations, saccades, and coordinates.  
4. Attention Mapping – Generate fixation density maps and saliency visualizations.  
5. Comparative Analysis – Evaluate attention metrics across easy, medium, and hard questions.  
6. Visualization – Create heatmaps and statistical plots for interpretation.

## Tools and Libraries
Python  
Pandas, NumPy  
OpenCV, Matplotlib, Seaborn  
TensorFlow / Keras  
Scikit-learn  
Jupyter Notebook / Google Colab  

## Dataset Description
EYE.csv – Fixation coordinates (x, y), start time, end time, duration  
IVT.csv – Saccade data (eye movement transitions)  
PSY.csv – Task metadata including difficulty level (easy/medium/hard)  
stimuli/ – Folder containing question or image stimuli  
aois.json (optional) – Areas of Interest definitions  

## Expected Output
- Fixation Density Maps (Empirical Attention Maps)  
- Predicted Saliency Maps (Deep Gaze Model Output)  
- Comparative heatmaps (Easy vs Medium vs Hard)  
- Statistical analysis charts (NSS, KL, CC metrics)

## Results and Conclusion
Successfully visualized and compared attention distribution across tasks.  
Observed distinct attention shifts based on difficulty.  
Generated heatmaps showing focus concentration areas.  
Supports adaptive and personalized learning model designs.

## Repository Structure
project/
├── data/
│   ├── EYE.csv
│   ├── IVT.csv
│   ├── PSY.csv
│   └── stimuli/
├── notebooks/
│   ├── 01_preprocessing_eye.ipynb
│   ├── 02_build_fdm_maps.ipynb
│   ├── 03_metrics_similarity.ipynb
│   ├── 04_deep_gaze_model.ipynb
│   ├── 05_comparative_analytics.ipynb
│   └── 06_visualizations.ipynb
├── models/
│   ├── deep_gaze_model.pt
│   └── center_bias_prior.npy
└── README.md

------------------------------------------------------------


