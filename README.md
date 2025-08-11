
# CMF2Net

# This is the repository for the paper CMF2Net: Cross-Modal Feature Fusion Model for Breast Tumor Seg-
mentation in Dynamic Contrast-Enhanced and T2-Weighted MRI

## Usage

* Data Preparation

  - Prepare your already registered data..

  - Convert the files' name by

  `python /xxx/dataset_conversion/Task131_DCET2Reg.py`

  - Preprocess the data by

  `python /xxx/experiment_planning/nnUNet_plan_and_preprocess.py -t 131 --verify_dataset_integrity`

* Train

  Train the model by

  `python /xxx/run/run_training_breast_MAML3_channel.py`

 `CMF2Net` is integrated with the out-of-box [nnUNet](https://github.com/MIC-DKFZ/nnUNet). Please refer to it for more usage.

If you would like to learn more about the usage details of the model, please contact:
[yaoqi0831@gmail.com]()

