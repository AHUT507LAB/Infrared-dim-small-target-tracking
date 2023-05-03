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
https://user-images.githubusercontent.com/85088116/235887632-4a63d40e-552d-4090-b960-e2bb13a54861.mp4

https://user-images.githubusercontent.com/85088116/235891136-b168c76f-7134-417f-8b15-9929dc3798f8.mp4

https://user-images.githubusercontent.com/85088116/235888297-6e6e49c6-2ca4-4b34-a71b-6bddc301080d.mp4

https://user-images.githubusercontent.com/85088116/235888972-70597040-50b3-401f-8a57-38292af56e69.mp4

https://user-images.githubusercontent.com/85088116/235892827-d95cb651-3f1a-440c-8166-dab0c1fe5c21.mp4
```
OSTrack
```
https://user-images.githubusercontent.com/85088116/235898751-dc8e3ad5-f8b3-4c57-a813-a4298ed44243.mp4
```
SiamRPN
```
https://user-images.githubusercontent.com/85088116/235894337-fb424213-9f4e-431f-928b-251e5a7ce830.mp4
