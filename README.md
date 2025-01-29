# MemBrain-v2
This is the main repository for MemBrain v2. It includes MemBrain-seg, MemBrain-pick, MemBrain-stats, and several Napari tools.

<div style="text-align: center;">
<img src="https://github.com/user-attachments/assets/ec551213-ca71-40eb-a3fa-93f8594eab14" alt="lasso_gif" width="36%" />
<img src="https://github.com/user-attachments/assets/eb7f8478-44df-4174-b368-ba03b9bbf8ea" alt="lasso_gif" width="30.8%" />
<img src="https://github.com/user-attachments/assets/3991f0a4-dde8-4bd0-b027-6e4a8fca876c" alt="lasso_gif" width="13.05%" />
</div>
<div style="text-align: center;">
<img src="https://github.com/user-attachments/assets/e0d02aa4-00af-4258-81bc-182b3dd52fc9" alt="lasso_gif" width="42%" />
<img src="https://github.com/user-attachments/assets/88851e09-6f10-4219-9b45-6f608c3e10b6" alt="lasso_gif" width="38%" />
</div>


## Installation
To install MemBrain-v2, you only need to set up a Python virtual environment and use pip:
```bash
pip install membrain
```
This will install all the necessary dependencies for MemBrain-v2 and give you access to all of MemBrain-v2's tools.

## Usage
The main commands you will want to use are:
```bash
membrain segment
membrain_pick
membrain_stats
```
By typing them, you will get more information on how to use them. However, it is strongly recommended to check the respective repositories for more detailed information and documentation. You can find them in the following links:

### MemBrain-seg
MemBrain-seg gives you the ability to segment 3D cryo-electron tomograms. It is based on the U-Net architecture and is trained on a variety of datasets. \
You can find the repository [here](https://github.com/teamtomo/membrain-seg).\
You can also check out the MemBrain-seg tutoral: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CellArchLab/membrain_tutorial_scripts/blob/main/MemBrain_seg_tutorial.ipynb)



### MemBrain-pick
MemBrain-pick is a tool that allows you to pick membrane particles from 3D cryo-electron tomograms. It is based on the diffusionNet architecture, which operates directly on membrane meshes. \
You can find the repository [here](https://github.com/CellArchLab/membrain-pick).\
You can also check out the MemBrain-pick tutoral: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CellArchLab/membrain_tutorial_scripts/blob/main/MemBrain_pick_example.ipynb)


### MemBrain-stats
MemBrain-stats is a tool that allows you to analyze the statistics of membrane particles picked from 3D cryo-electron tomograms, in combination with the membrane architecture. \
You can find the repository [here](https://github.com/CellArchLab/membrain-stats). 
There is also an example on how to use MemBrain-stats in the above MemBrain-pick tutorial.

### Surforama
Surforama is a Napari-based tool that allows you to visualize and analyze membranes and their embedded particles in 3D cryo-electron tomograms. \
You can find the repository [here](https://github.com/cellcanvas/surforama/).

### Napari-lasso-3d
Napari-lasso-3d is a Napari plugin that allows you to select regions in your segmentations by drawing a lasso in 3D. This aims to facilitate the selection of regions of interest in 3D cryo-electron tomograms. \
You can find the repository [here](https://github.com/CellArchLab/napari-lasso-3d)

## Citation
If you use MemBrain-v2 in your research, please cite the following paper

```
[1] Lamm, L., Zufferey, S., Righetto, R.D., Wietrzynski, W., Yamauchi, K.A., Burt, A., Liu, Y., Zhang, H., Martinez-Sanchez, A., Ziegler, S., Isensee, F., Schnabel, J.A., Engel, B.D., and Peng, T, 2024. MemBrain v2: an end-to-end tool for the analysis of membranes in cryo-electron tomography. bioRxiv, https://doi.org/10.1101/2024.01.05.574336
```