## Machine learning prediction of postoperative complications after high tibial osteotomy for canine cranial cruciate ligament disease
**Overview**
* This repository contains the code and trained XGBoost model for the <b><u>PROSPECT</u></b> (<b><u>P</u></b>redicting <b><u>R</u></b>isk <b><u>O</u></b>f <b><u>S</u></b>urgical com<b><u>P</u></b>lications aft<b><u>E</u></b>r <b><u>C</u></b>CWO and T<b><u>P</u></b>LO)
 model.
* Publication pending.

**Model**

* The XGBoost classifier was trained on the dataset with Bayesian hyperparameter optimisation to predict postoperative ambulation recovery.
* Best XGBoost hyperparameters: {'learning_rate': 0.16,'max_depth': 3, 'n_estimators': 400,
'subsample': 0.80, 'colsample_bytree': 0.92}

**Permissions**
* The open access of this model is granted for research purposes only. Any use of the model for clinical decision-making is not recommended or endorsed. The sole responsibility of patient care remains that of the attending veterinarian, and we assume no responsibility or liability if this model is used outside of its intended scope.
* Contributions are welcome! If you'd like to improve the model or code, please open an issue or submit a pull request.

**Files in this Repository**

📂 

📂 MIT LICENSE - CC Attributions 4.0 Open Source License

📂 README.md – This documentation

**Acknowledgements**

Algorithm built with clinical cases from:

![fps](https://github.com/user-attachments/assets/067684f6-6dee-41ed-92e8-ec26da8f25d2)


Open access funding granted by IVC Evidensia.

![image](https://github.com/user-attachments/assets/8e4cd562-c27f-493f-af40-c162c0d62d13)
