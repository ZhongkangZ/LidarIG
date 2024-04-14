## LidarIG: A Image-Guided Point Cloud  Generation  via  Coarse-to-Fine Network for 3D Object Detetion

## It will be improved later...

## Introduction


<table class="center">
    <tr>
    <td width=100% style="border: none"><img src="assert/overview.png" style="width:100%"></td>
    </tr>
    <tr>
    <td width="100%" style="border: none; text-align: center; word-wrap: break-word">Overview of our C2FiPCN
</td>
  </tr>

  **Abstract**: Multi-modal 3D object detection, and emphasize the use of virtual point cloud generation technology, point cloud voxelization technology, and coarse-to-fine manner, here is an example:

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
git clone https://github.com/ZhongkangZ/LidarIG
cd C2FiPCN
conda create -n LidarIG python==3.7
conda activate LidarIG
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
