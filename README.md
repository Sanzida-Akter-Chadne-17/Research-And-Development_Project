Automatic Classification of Carotid Artery Stenosis from Ultrasound Images

This repository contains the code developed for the Research and Development Project in Computer Engineering with Industry (10 ECTS) at Aarhus University.
The project investigates the feasibility of deep learning–based classification of carotid artery stenosis using static Doppler ultrasound screenshots under realistic clinical constraints

├── data_preprocessing/
│   ├── dicom_to_png.ipynb
│   ├── roi_extraction.ipynb
│   └── feature_extraction.ipynb
│
├── models/
│   ├── efficientnet_backbone.py
│   ├── multimodal_model.py
│   └── ordinal_model.py
│
├── training/
│   ├── train_model1.py
│   ├── train_model2_focal.py
│   └── train_model3_ordinal.py
│
├── evaluation/
│   ├── metrics.py
│   ├── confusion_matrices.py
│   └── results_analysis.ipynb
│
├── requirements.txt
└── README.md

