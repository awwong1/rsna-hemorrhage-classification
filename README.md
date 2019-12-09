# RSNA Hemorrhage Classification

Source code for University of Alberta, CMPUT 617: Medical Image Analysis (Fall 2019). Lead by Prof. Nilanjan Ray. 

* [Original Kaggle Competition](https://www.kaggle.com/c/rsna-intracranial-hemorrhage-detection/overview)

## Running Instructions

1. Download and extract the RSNA intracranial hemorrhage detection competition dataset
```bash
kaggle competitions download -c rsna-intracranial-hemorrhage-detection
mkdir data && unzip -o rsna-intracranial-hemorrhage-detection.zip -d data
```

2. Show the data contents
```bash
ls data/rsna-intracranial-hemorrhage-detection/
# stage_2_sample_submission.csv  stage_2_test  stage_2_train  stage_2_train.csv
du -h data/rsna-intracranial-hemorrhage-detection/
# 60G     data/rsna-intracranial-hemorrhage-detection/stage_2_test
# 371G    data/rsna-intracranial-hemorrhage-detection/stage_2_train
# 431G    data/rsna-intracranial-hemorrhage-detection/
```

3. Run the [process_and_view_dicom](./process_and_view_dicom.ipynb) Jupyter notebook.
