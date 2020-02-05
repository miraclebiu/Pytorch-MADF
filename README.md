# Pytorch-MADF

An Implement of MADF (Image Inpainting by Single-Shot Cascaded Refinement with Mask Awareness) for Pytorch version.

# Requirements
  - Pytorch 1.0.0
  - python 3.*
  - numpy 1.13.1
  
  
# Usages
  ## downlaod repo
  - download this repo by the following instruction:
  
        $ git clone https://github.com/cvpr2020-inpainting-anonymous/Pytorch-MADF.git
        $ cd Pytorch-MADF-master
      
  ## download datasets
  
  ## Mask sets
  - Mask sets can be download [here](https://nv-adlr.github.io/publication/partialconv-inpainting). We train all the datasets with the same mask sets.


  ### Places2
  - You can download this dataset [here](http://places2.csail.mit.edu/download.html). We use the High-resolution version in this repo.
    
  
  ### Celeba-HQ
  - You can download this dataset [here]().
  
  ### Paris street view
  - You can download this dataset [here]().
 
  ## training
  
      $ python train.py --train_root train_root --mask_root mask_root --test_root test_root --use_incremental_supervision  
      
  ## testing
  
      $ python test.py --list_file test_list --snapshot model_path
      
  ## Pretrained models
  [Places2](https://drive.google.com/open?id=10iXhPEiOiNzTbM-Yc1GRy2-D9Xjmd1cI)|[Celeba-HQ]()|[PSV]()
