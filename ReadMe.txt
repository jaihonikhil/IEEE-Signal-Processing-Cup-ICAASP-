Run Main_File.ipynb to see the final model in action

Two approaches are contained in this folder, first is Isolation Forest(Actually Used) & the other is ARMA-Forecasting & CNN based forecasting.

The EM(for EVALUATION) curves of both of these approaches are contained in Main_File.ipynb (For Isolation Forest) & Approach1 Timeforecasting using CNN.ipynb (CNN based forecasting)

Directory Structure:

├── ABNORMAL
│   ├── File0
│   │   ├── angvel.csv
│   │   ├── camera.csv
│   │   ├── camera_data.csv
│   │   ├── File0.bag.csv
│   │   ├── imu_data.csv
│   │   ├── linacc.csv
│   │   ├── mag_data.csv
│   │   ├── mf.csv
│   │   ├── orientation.csv
│   │   ├── staticp.csv
│   │   ├── staticp_data.csv
│   │   ├── temp.csv
│   │   └── temp_data.csv
│   ├── File1
│   │   ├── angvel.csv
│   │   ├── camera.csv
│   │   ├── camera_data.csv
│   │   ├── File1.bag.csv
│   │   ├── imu_data.csv
│   │   ├── linacc.csv
│   │   ├── mag_data.csv
│   │   ├── mf.csv
│   │   ├── orientation.csv
│   │   ├── staticp.csv
│   │   ├── staticp_data.csv
│   │   ├── temp.csv
│   │   └── temp_data.csv
│   ├── File2
│   │   ├── angvel.csv
│   │   ├── camera.csv
│   │   ├── camera_data.csv
│   │   ├── File2.bag.csv
│   │   ├── imu_data.csv
│   │   ├── linacc.csv
│   │   ├── mag_data.csv
│   │   ├── mf.csv
│   │   ├── orientation.csv
│   │   ├── staticp.csv
│   │   ├── staticp_data.csv
│   │   ├── temp.csv
│   │   └── temp_data.csv
│   ├── File3
│   │   ├── angvel.csv
│   │   ├── camera.csv
│   │   ├── camera_data.csv
│   │   ├── File3.bag.csv
│   │   ├── imu_data.csv
│   │   ├── linacc.csv
│   │   ├── mag_data.csv
│   │   ├── mf.csv
│   │   ├── orientation.csv
│   │   ├── staticp.csv
│   │   ├── staticp_data.csv
│   │   ├── temp.csv
│   │   └── temp_data.csv
│   ├── File4
│   │   ├── angvel.csv
│   │   ├── camera.csv
│   │   ├── camera_data.csv
│   │   ├── File4.bag.csv
│   │   ├── imu_data.csv
│   │   ├── linacc.csv
│   │   ├── mag_data.csv
│   │   ├── mf.csv
│   │   ├── orientation.csv
│   │   ├── staticp.csv
│   │   ├── staticp_data.csv
│   │   ├── temp.csv
│   │   └── temp_data.csv
│   └── File5
│       ├── angvel.csv
│       ├── camera.csv
│       ├── camera_data.csv
│       ├── File5.bag.csv
│       ├── imu_data.csv
│       ├── linacc.csv
│       ├── mag_data.csv
│       ├── mf.csv
│       ├── orientation.csv
│       ├── staticp.csv
│       ├── staticp_data.csv
│       ├── temp.csv
│       └── temp_data.csv
├── Approach1 Timeforecasting using CNN.ipynb
├── CLASSIFIER.ipynb
├── iforest_classifier.sav
├── Main_File.ipynb
├── model.h5
├── NORMAL
│   ├── File0
│   │   ├── angvel.csv
│   │   ├── camera.csv
│   │   ├── camera_data.csv
│   │   ├── File0.bag.csv
│   │   ├── imu_data.csv
│   │   ├── linacc.csv
│   │   ├── mag_data.csv
│   │   ├── mf.csv
│   │   ├── orientation.csv
│   │   ├── staticp.csv
│   │   ├── staticp_data.csv
│   │   ├── temp.csv
│   │   └── temp_data.csv
│   ├── File1
│   │   ├── angvel.csv
│   │   ├── camera.csv
│   │   ├── camera_data.csv
│   │   ├── File1.bag.csv
│   │   ├── imu_data.csv
│   │   ├── linacc.csv
│   │   ├── mag_data.csv
│   │   ├── mf.csv
│   │   ├── orientation.csv
│   │   ├── staticp.csv
│   │   ├── staticp_data.csv
│   │   ├── temp.csv
│   │   └── temp_data.csv
│   ├── File2
│   │   ├── angvel.csv
│   │   ├── camera.csv
│   │   ├── camera_data.csv
│   │   ├── File2.bag.csv
│   │   ├── imu_data.csv
│   │   ├── linacc.csv
│   │   ├── mag_data.csv
│   │   ├── mf.csv
│   │   ├── orientation.csv
│   │   ├── staticp.csv
│   │   ├── staticp_data.csv
│   │   ├── temp.csv
│   │   └── temp_data.csv
│   ├── File3
│   │   ├── angvel.csv
│   │   ├── camera.csv
│   │   ├── camera_data.csv
│   │   ├── File3.bag.csv
│   │   ├── imu_data.csv
│   │   ├── linacc.csv
│   │   ├── mag_data.csv
│   │   ├── mf.csv
│   │   ├── orientation.csv
│   │   ├── staticp.csv
│   │   ├── staticp_data.csv
│   │   ├── temp.csv
│   │   └── temp_data.csv
│   ├── File4
│   │   ├── camera_data.csv
│   │   ├── File4.bag.csv
│   │   ├── imu_data.csv
│   │   ├── mag_data.csv
│   │   ├── staticp_data.csv
│   │   └── temp_data.csv
│   └── File5
│       ├── camera_data.csv
│       ├── File5.bag.csv
│       ├── imu_data.csv
│       ├── mag_data.csv
│       ├── staticp_data.csv
│       └── temp_data.csv
├── PCA In-Depth Analysis.ipynb
├── pca_transform.sav
├── ReadMe.txt
├── Resampling.ipynb
├── Topics.txt
└── Video Feature Extraction.ipynb


For Isolation Forest:

/NORMAL/File 0 - File 4 => Training Data
/ABNORMAL/File1 - File 4 => Training Data
/NORMAL/File 5 => Testing Data
/ABNORMAL/File 5 => Testing Data

For Forecasting & CNN based Method:

/NORMAL/File 0 - File 4 => Training Data
Rest is Testing Data

For Files of name File[0,1,2,3,4,5].bag.csv inside /NORMAL/File[0,1,2,3,4,5] or /ABNORMAL/File[0,1,2,3,4,5] ; format of data entry is as follows:

----------------------------
Orientation X|
----------------------------
Orientation Y|
----------------------------
Orientation Z|
----------------------------
Orientation W|
----------------------------
av_x_resampled|
----------------------------
av_y_resampled|
----------------------------
av_z_resampled|
----------------------------
la_x_resampled|
----------------------------
la_y_resampled|
----------------------------
la_z_resampled|
----------------------------
mf_x_resampled|
----------------------------
mf_y_resampled|
----------------------------
mf_z_resampled|
----------------------------
temp_resampled|
----------------------------
staticp_resampled|
----------------------------
camera_resampled|
----------------------------

