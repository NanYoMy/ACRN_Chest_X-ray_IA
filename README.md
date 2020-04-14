# Learning Deformable Registration of Medical Images with Anatomical Constraints
Repository of AC-RegNet, a new method to regularize CNN-based deformable image registration by considering global anatomical priors in the form of segmentation masks.

In this repository you can find the AC-RegNet source code and results produced for the paper "Learning deformable registration of medical images with anatomical constraints" (Neural Networks, 2020). You can download our paper from [here](https://arxiv.org/abs/2001.07183).

## Content
- [CLI Application](https://github.com/lucasmansilla/ACRN_Chest_X-ray_IA/tree/master/CLI_application/acregnet): An open source command line tool for chest x-ray image registration.
- [AC-RegNet](https://github.com/lucasmansilla/ACRN_Chest_X-ray_IA/tree/master/acregnet): Implementation of AC-RegNet model with TensorFlow.
- [NIH Chest-XRay14 segmentations](https://github.com/lucasmansilla/NIH_chest_xray14_segmentations): Anatomical segmentation masks produced for NIH Chest-XRay14 dataset using AC-RegNet with a multi-atlas segmentation model.

## Reference
If you use source code or results from this repository in your publication, please cite our paper:
- Mansilla, L., Milone, D. H., & Ferrante, E. (2020). Learning deformable registration of medical images with anatomical constraints. Neural Networks, 124, 269-279.

## License
[MIT](https://choosealicense.com/licenses/mit/)
