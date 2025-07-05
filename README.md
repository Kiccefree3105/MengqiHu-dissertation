# MengqiHu-dissertation
# The TSA_max_min_mean.xlsx file contains the calculated 100000 TAS daily max, min and mean data from the CLUM output. The corresponding code is ERP_max_min_mean.ipynb
#·The TSA_max_min_mean.xlsx file contains the calculated 100000 TAS daily max, min and mean data from the CLUM output. The corresponding code is ERP_max_min_mean.ipynb
#·The ERP_autoML.ipynb is the code for train the model using FLAML, the corresponding model is save as ERP_automl_model.pkl 
#·The ERP_ML_MLP.ipynb is the code for train the DL model using MLP, the corresponding model is save as ERP_mlp_regressor.pth 
#·The ERP_visual.ipynb is the code for using the two models to predict the extracted U-surf data from Manchester, togather with comparison of the model result. The results show   that output max TSA from FLAML is about 1 K higher than the output from MLP, to futher explore this difference, I compared the two outputs from using the test data as input,   the results show no distict differnence. The corresponding files are ERP_y_pred_grid_klaml.nc, ERP_y_pred_grid_mlp.nc, ERP_ds_test_klaml.nc, ERP_ds_test_mlp.nc 
#·The ERP_features_Man.nc contains the extracted U-surf data of rough rectangle region of the 'Great Manchester'.
#·The ERP_shpfile_test.ipynb contains the precedure to extract the exact boarder of the 'Great Manchester'.
