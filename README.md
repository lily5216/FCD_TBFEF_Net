# TBFEF-Net for focal cortical dysplasia lesion segmentation

## Usage. 
* Data Preparation
The data preprocessing follows the nnUNet pipeline. [nnUNet](https://github.com/MIC-DKFZ/nnUNet).
* Train
`nnUNet_train 3d_fullres nnUNetTrainerV2_TBFEF 04 0`
*  Test
`nnUNet_predict -i INPUT_PATH -o OUTPUT_PATH -t 04 -f 0 -tr nnUNetTrainerV2_TBFEF`
