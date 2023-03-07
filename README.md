# Infrared-dim-small-target-detection
anti-UAV
## Install the environment
Use the Anaconda (CUDA 10.2)
```
conda create -n ostrack python=3.8
conda activate ostrack
bash install.sh
```
## Set project paths
Run the following command to set paths for this project
```
python tracking/create_default_local_file.py --workspace_dir . --data_dir ./data --save_dir ./output
```

## Data Preparation
Create a folder video .Put the tracking datasets in ./video

## Evaluation
