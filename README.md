# COMPLETION OF SPARSE AND PARTIAL POINT CLOUDS OF VEHICLES USING A NOVEL END-TO-END NETWORK

###### <font color=CornflowerBlue>Yan Xia, Weiquan Liu, Zhipeng Luo, Yusheng Xu, Uwe Stilla.</font>

------

### Introduction

This repo contains the codes for our ISPRS Congress 2020 paper: **COMPLETION OF SPARSE AND PARTIAL POINT CLOUDS OF VEHICLES USING A NOVEL END-TO-END NETWORK.** 

In this paper, we design a novel and end-to-end network, termed as S2U-Net, to achieve the completion of 3D shapes of vehicles from the partial and sparse point clouds. Our network includes two modules of the encoder and the generator. The encoder is designed to extract the global feature of the incomplete and sparse point cloud while the generator is designed to produce fine-grained and dense completion. Specially, we adopt an upsampling strategy to output a more uniform point cloud.

The codes are modified from [PCN](https://github.com/wentaoyuan/pcn) and [PU-GAN](https://github.com/liruihui/PU-GAN).

**The codes and data will be coming soon!**

### Citation

```
@Article{isprs-annals-V-2-2020-933-2020,
AUTHOR = {Xia, Y. and Liu, W. and Luo, Z. and Xu, Y. and Stilla, U.},
TITLE = {COMPLETION OF SPARSE AND PARTIAL POINT CLOUDS OF VEHICLES USING A NOVEL END-TO-END NETWORK},
JOURNAL = {ISPRS Annals of Photogrammetry, Remote Sensing and Spatial Information Sciences},
VOLUME = {V-2-2020},
YEAR = {2020},
PAGES = {933--940},
URL = {https://www.isprs-ann-photogramm-remote-sens-spatial-inf-sci.net/V-2-2020/933/2020/},
DOI = {10.5194/isprs-annals-V-2-2020-933-2020}
}
```

### References

1. Li, R., Li, X., Fu, C. W., Cohen-Or, D., & Heng, P. A. (2019). Pu-gan: a point cloud upsampling adversarial network. In *Proceedings of the IEEE International Conference on Computer Vision* (pp. 7203-7212).
2. Yuan, W., Khot, T., Held, D., Mertz, C., & Hebert, M. (2018, September). Pcn: Point completion network. In *2018 International Conference on 3D Vision (3DV)* (pp. 728-737). IEEE.