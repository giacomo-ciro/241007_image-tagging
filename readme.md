## Image Tagging
Github repo with inference tutorial [here](https://github.com/xinyu1205/recognize-anything?tab=readme-ov-file).  
  
The model `ram_plus_swin_large_14m.pth` as `350M` params. 
  
1. Download checkpoints from the original repo into `/pretrained/` directory.  
  
2. Then, create an environment and import required packages  
`conda create -n recognize-anything python=3.8 -y`  
`conda activate recognize-anything`  
`pip install git+https://github.com/xinyu1205/recognize-anything.git`
  
3. Now you can run inference on custom image:  
`python inference_ram_plus.py --image img/demo1.jpg --pretrained pretrained/ram_plus_swin_large_14m.pth`