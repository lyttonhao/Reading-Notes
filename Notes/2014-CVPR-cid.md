# CID: Combined Image Denoising in Spatial and Frequency Domains Using Web Images

2014 CVPR, Huanjing Yue, Xiaoyan Sun, Jingyu Yang, Feng Wu

### Algorithm

deal with *heavy noise*

* Intrisic cube --> Frequency filtering(like BM3D, Wiener Filtering)
* Extrinsic cube (from web simialr pictures) --> Spatial filtering (like median filtering)
* Do two steps 
* Combine: Extrinsic (distorted in low frequency since the variation of illumination)