# Delta-Radiomics-Project
Delta-Radiomics Using Machine Learning Classifiers with Auxiliary Datasets to Predict Disease Progression during MR-guided Radiotherapy in Adrenal Metastases

# Abstract
PURPOSE: MR-guided radiotherapy (MRgRT) improves soft tissue delineation of tumors and normal tissues. Adaptive radiotherapy can account for inter-fractional anatomical changes, while biologically-adapted radiotherapy remains elusive. We hypothesize that changes in the Gross Tumor Volumes (GTVs) identified during daily scans could be analyzed using delta-radiomics to predict disease progression. To overcome the limited sample size, we evaluated the hypothesis of whether auxiliary datasets could improve the prediction performance.
MATERIALS AND METHODS: We analyzed 108 patients (n=90 internal; n=18 external) who received ablative radiotherapy. The internal dataset included 42 adrenal metastases, 23 primary lung cancer, and 25 primary pancreas cancer patients, with the clinical endpoint predicting the presence of progression-free survival events. The median dose was 50 Gy(40-60 Gy) delivered over five fractions. The delta features are the ratio of the features of the last to the first treatment fraction, F5/F1, and the combination of first and last fraction features, F1||F5. We studied decision trees machine learning classifier with and without auxiliary datasets with the external dataset exclusively for independent testing of the final models.
RESULTS: During internal training, F1||F5 model, the inclusion of the lung dataset increased our AUC-ROC from 0.5265 ± 0.116 (without auxiliary data) to 0.6048 ± 0.110, while the inclusion of the pancreas data increased it to 0.6024 ± 0.110. For the F5/F1 model, the inclusion of the lung auxiliary data increased our AUC-ROC from 0.5214 ± 0.137  to 0.6452 ± 0.110,  while it modestly changed by 0.6262 ± 0.130 when the pancreas data was included. For external testing, For the F5/F1 model, we reported an AUC-ROC of 0.60 with the lung auxiliary data and 0.425 with the pancreas data. Also, for the F5||F1 model, we reported an AUC-ROC of 0.70 with the lung auxiliary and 0.60 with the pancreas data. 
CONCLUSION: Decision Trees provided a robust and explainable classification model on the external dataset. Including auxiliary lung data during training improved our model, and the validation of our model on an external data set indicates this may be the first step to biologically-adapted radiotherapy recognizing radiomic signals for potential recurrence.

Keywords: Magnetic resonance-guided radiotherapy, Delta radiomics, Progression event, Adrenal cancer, Lung cancer, Machine learning

Abbreviations 
MRgRT – Magnetic Resonance-guided Radiotherapy
GTV – Gross Tumor Volume
MRL – Magnetic Resonance Linear Accelerator
MRI – Magnetic Resonance Imaging
AUC-ROC – Area Under the Receiver Operator Characteristic Curve
 

