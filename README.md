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

## test
Download the model weights from [Google Drive](https://drive.google.com/drive/folders/1PS4inLS8bWNCecpYZ0W2fE5-A04DvTcd?usp=sharing) 
- video-test
```
python tracking/video_demo.py ostrack vitb_384_mae_ce_32x4_ep300 ./video/name.mp4
```
## display
```
ours
```
https://user-images.githubusercontent.com/85088116/223421585-e1429810-70b3-4b6f-8439-5a7a9d298728.mp4

https://user-images.githubusercontent.com/85088116/235887632-4a63d40e-552d-4090-b960-e2bb13a54861.mp4

