# PSC_Regressor
Repository storing the regressor model training and evaluation for PCE of PSCs.

The code is a walk through of the development process.

The model files and datasets are not provided due to larger file sizes.


> cloud_trainer/Perov_XGBoost_20_Fold_10_optim

> cloud trainer/perov_MLP_20_Fold_30_optim_0.25DO

> cloud trainer/perov_TabNet_20_Fold_30_optim

> cloud trainer/perov_lasso_ridge_20_Fold_20_optim

> cloud trainer/perov_sklearn_linear_reg_no_optim

The above files are used to run most of the models both in Googlecolab and Kaggle kernel.

The notebook with QSLR and QLR will be uploaded soon.  

The functions in the above files are similar as all the model follows 20 fold crossvalidation with optuna hyperparameter optimization. 

The quantum ML models are under parameter tuning and debugging soon all the models with loss data will be provided 

### If necessary the dataset and models can be provided with link !!


Environment Detail

pip==21.2.4

python==3.7.10
