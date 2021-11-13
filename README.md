# sEMG-classification
The purpose of this study was to determine electromyographically if there are significant differences in the movement associated with the knee muscle, gait, leg extension from a sitting position, and flexion of the leg up for regular and abnormal sEMG data. Surface electromyography (sEMG) data was obtained from the lower limbs of 22 people during three different exercises: sitting, standing, and walking (11 with and 11 without knee abnormality). Participants with a knee deformity take longer to finish the task than healthy subjects. The sEMG signal duration of patients with abnormalities is longer than that of healthy ones, resulting in an imbalance in the obtained sEMG signal data. As a result of the data's bias towards the majority class, developing a classification model for automated analysis of such sEMG signals is arduous. The sEMG collected data is denoised and filtered, followed by the extraction time-domain characteristics. Machine Learning methods are then used for predicting the three distinct movements (sitting, standing, and walking) associated with electrical impulses for normal and abnormal sets. Also, different Anomaly detection techniques are used for detecting occurrences in the sEMG signals that differ considerably from the majority of data and hence used for enhancing the performance of our model. The iforest anomaly detection technique presented in this work can achieve 98.5\% accuracy on the Light Gradient Boosting Machine algorithm, surpassing the previous results that we can achieve maximum accuracy of 92.5\% and 91\%, improving accuracy by 6\%-7\% for classification of knee abnormality using Machine Learning.