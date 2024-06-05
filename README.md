## Study on Electromyography and Knee Abnormalities

### Purpose of the Study
The aim of this study was to determine, using electromyography (EMG), if there are significant differences in movements associated with the knee muscles during gait, leg extension from a sitting position, and leg flexion for regular and abnormal sEMG data.

### Methodology

- **Participants**:
  - 22 people participated in the study.
  - 11 with knee abnormalities.
  - 11 without knee abnormalities.

- **Exercises Conducted**:
  - Sitting
  - Standing
  - Walking

- **Data Collection(Note: Dataset Downloaded from publicly available repository)**:
  - Surface electromyography (sEMG) data was obtained from the lower limbs.
  - sEMG signal duration was measured.
  - It was observed that participants with knee deformities took longer to complete tasks than healthy subjects.

### Key Findings

- **sEMG Signal Duration**:
  - The duration of sEMG signals in patients with knee abnormalities was longer than in healthy individuals.
  - This resulted in an imbalance in the obtained sEMG signal data.

- **Data Imbalance**:
  - Due to the bias towards the majority class, developing a classification model for automated analysis of sEMG signals was challenging.

### Data Processing and Analysis

1. **Data Denoising and Filtering**:
   - Collected sEMG data was denoised and filtered.

2. **Feature Extraction**:
   - Time-domain characteristics were extracted from the sEMG data.

3. **Machine Learning**:
   - Machine learning methods were used to predict the three distinct movements (sitting, standing, and walking) based on electrical impulses for normal and abnormal sets.

### Anomaly Detection

- **iForest Anomaly Detection Technique**:
  - The isolation forest (iForest) anomaly detection technique achieved 98.5% accuracy with the Light Gradient Boosting Machine algorithm.
  - This surpassed previous maximum accuracies of 92.5% and 91%, improving accuracy by 6%-7% for the classification of knee abnormalities using machine learning.

 ## Workflow Diagram

 ![Workflow](https://github.com/raj-chinagundi/sEMG-classification/blob/main/Screenshot%202024-06-06%20at%2012.24.35%20AM.png)
