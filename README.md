## M3D-DVC: A Multimodal 3D Detection and Voxel Completion Framework Using Virtual Point Clouds from Coarse to Fine

## It will be improved later...

## Introduction


<table class="center">
    <tr>
    <td width=100% style="border: none"><img src="assert/overview.png" style="width:100%"></td>
    </tr>
    <tr>
    <td width="100%" style="border: none; text-align: center; word-wrap: break-word">Overview of our M3D-DVC
</td>
  </tr>

  **Abstract**: Multi-modal 3D object detection, and emphasize the use of virtual point cloud completion technology, point cloud voxelization technology, and coarse-to-fine manner, here is an example:

<table class="center">
    <tr>
    <td width=100% style="border: none"><img src="assert/image-Point_enhancement.png" style="width:100%"></td>
    </tr>
    <tr>
    <td width="100%" style="border: none; text-align: center; word-wrap: break-word">Pseudo point cloud enhancement
</td>
  </tr>
</table>


## Preparations

**1. Set Environment**

```bash
git clone https://github.com/ZhongkangZ/C2FiPCN
cd M3D-DVC
conda create -n M3D-DVC python==3.7
conda activate M3D-DVC
pip install -r requirements.txt
mkdir repositories
mkdir -p generated_vir/demo_virpoint
mkdir models/vir_point
```
**2. Download Libraries**
```bash
cd repositories
git clone https://github.com/xingyizhou/CenterNet2
git clone https://tianweiy.github.io/mvp
mv vir_point vir_point-ai
cd ..
```
