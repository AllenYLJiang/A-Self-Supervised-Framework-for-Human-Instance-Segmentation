# SSINS
environments:
python = 3.8 
matplotlib>=3.2.2
numpy>=1.18.5
opencv-python>=4.1.2
Pillow
PyYAML>=5.3.1
scipy>=1.4.1
torch>=1.7.0
torchvision>=0.8.1
tqdm>=4.41.0
tensorboard>=2.4.1
seaborn>=0.11.0
pandas
thop

# Run the modules for people detection and tracking: 
python window.py 
> place the decoded frames into data_for_test, the frames of each video are placed in one folder 
the results will be automatically stored in cache 

> The module for tracking is the basis for the module for instance segmentation which will be released soon 
