# Image_Input_TF2.3
In order to expedite the training, we need to optimize the data extraction, data transformation, and data loading process all of which happens on the CPU.
## Data Extraction: Optimize the data read from data sources
## Data Transformation: Parallelize the data augmentation
## Data Loading: Prefetch the data one step ahead of training
These techniques will efficiently utilize the CPU and GPU/TPU resources for data preprocessing and training.

