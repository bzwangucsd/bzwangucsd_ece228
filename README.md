MY ENVIRONMENT

Python 3.9.2, environment created with conda

REQUREMENTS 

numpy, torch, matplotlib, cv2, tqdm, pycocotools, scipy -- all latest versions for Python 3.9.2

ffmpeg on PATH

TO INSTALL

Download sam_vit_h_4b8939.pth from https://github.com/facebookresearch/segment-anything and place in models/

Download folder segment_anything/ from https://github.com/facebookresearch/segment-anything and place in root directory (i.e. bzwangucsd_ece228/segment_anything/)

Download groundingdino_swint_ogc.pth from https://github.com/IDEA-Research/GroundingDINO and place in models/

Follow steps at https://github.com/IDEA-Research/GroundingDINO?tab=readme-ov-file#hammer_and_wrench-install to build and install GroundingDINO for your system

TO RUN

To run with the example video, simply run all cells in motion_tracking.ipynb and output is stored at sequences/sav_000001/sav_000001_out.mp4

To run with your own video:

1. Place your video at sequences/video_name/video_name.mp4

2. In motion_tracking.ipynb, chance SEQUENCE_NAME and TEXT_PROMPT to your desired inputs.

3. In code block 7, you may need to change tracker_start so that the star in the image output from that block is on top of the target object (not always needed)

4. Run the entire notebook