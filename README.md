# PSC_Regressor
Repository storing the regressor model training and evaluation for PCE of PSCs.

The code is a walk through of the development process.

The model files and datasets are not provided due to larger file sizes.

> xgboost-reg-main_cloud_trainer.ipynb

> cloud trainer/code-tabnet-reg-main_cloud_trainer

> cloud trainer/lasso-ridge-reg-main_cloud_trainer

> cloud trainer/linear-regression-main_cloud_trainer

> cloud trainer/MLPerceptron-torch-norm-nD-eS5_cloud_trainer

> cloud trainer/Quantum_NN-pl-torch-cloud_trainer

The above files are used to run most of the models both in Googlecolab and Kaggle kernel. As these kernels are used extensively for training the model the python dependencies are not important to mention.

The notebook with QSLR and QLR will be uploaded soon.  

The functions in the above files are similar as all the model follows 20 fold crossvalidation with optuna hyperparameter optimization. 

The quantum ML models are under parameter tuning and debugging soon all the models with loss data will be provided 

### If necessary the dataset and models can be provided with a google drive link !!
