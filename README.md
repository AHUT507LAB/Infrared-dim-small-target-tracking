# Infrared-dim-small-target-tracking
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
https://github.com/AHUT507LAB/Infrared-dim-small-target-tracking/assets/85088116/f353aaaa-a38c-4fa1-ab66-f66cb332082e

https://github.com/AHUT507LAB/Infrared-dim-small-target-tracking/assets/85088116/5aaa2791-61a4-4b6a-b64f-29f33ac2c16c

https://github.com/AHUT507LAB/Infrared-dim-small-target-tracking/assets/85088116/a9850454-0e0b-4deb-abb0-21c5e9da60ab

https://github.com/AHUT507LAB/Infrared-dim-small-target-tracking/assets/85088116/f2363890-dd53-405b-a47c-181442803b48

https://user-images.githubusercontent.com/85088116/235892827-d95cb651-3f1a-440c-8166-dab0c1fe5c21.mp4
```
OSTrack
```
https://github.com/AHUT507LAB/Infrared-dim-small-target-tracking/assets/85088116/78cf1f6b-8ee5-4e94-8a5f-1ea798e95149
```
SiamRPN
```
https://github.com/AHUT507LAB/Infrared-dim-small-target-tracking/assets/85088116/1b67c34a-b200-425a-b73d-64709b21c292
