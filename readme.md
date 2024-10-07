## recognize-anything
Github repo with inference tutorial [here](https://github.com/xinyu1205/recognize-anything?tab=readme-ov-file).  
The model `ram_plus_swin_large_14m.pth` as `350M` params. 

### Create Env
`conda create -n recognize-anything python=3.8 -y`  
`conda activate recognize-anything`  
`pip install git+https://github.com/xinyu1205/recognize-anything.git`
### Run Inference
`python inference_ram_plus.py --image images/demo/demo1.jpg --pretrained pretrained/ram_plus_swin_large_14m.pth`