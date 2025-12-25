Automatic Classification of Carotid Artery Stenosis from Ultrasound Images

This repository contains the code developed for the Research and Development Project in Computer Engineering with Industry (10 ECTS) at Aarhus University.
The project investigates the feasibility of deep learning–based classification of carotid artery stenosis using static Doppler ultrasound screenshots under realistic clinical constraints

.
├── data/
│   ├── FINAL_DATASET_MODEL_READY.csv
│   ├── FINAL_DATASET_ORDINAL.csv
│   ├── ordinal_train.csv
│   ├── ordinal_val.csv
│   └── ordinal_test.csv
│
├── notebooks/
│   ├── dicom-to-png.ipynb
│   ├── part2_extracted_doppler_roi.ipynb
│   ├── multimodal_model.ipynb
│   └── ordinal_multimodal_model.ipynb
│
├── models/
│   ├── best_multimodal_model.pth
│   ├── best_multimodal_focal_regularized.pth
│   └── best_ordinal_multimodal.pth
│
├── figures/
│   ├── efficientnet_b0_backbone.png
│   ├── fusion_pipeline.png
│   └── confusion_matrices/
│
├── requirements.txt
└── README.md


