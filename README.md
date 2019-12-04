# Pose3dFix

This work aims to fix the 3d poses, which are estimated using epipolar geometry method. The idea is borrowed from [PoseFix](https://github.com/mks0601/PoseFix_RELEASE). In this work, we extend the PoseFix from 2D to 3D. 

The code is originally duplicated from [EpipolarPose](https://github.com/mkocabas/EpipolarPose) since they share a similar network structure. For the dataset download and preparation, please refer to the [EpipolarPose](https://github.com/mkocabas/EpipolarPose) repo or its [readme](README_EpipolarPose.md). All the idea extensions are performed based on it.

To train the network, just run the command
```
python scripts/train.py --cfg experiments/h36m/train.yaml
```
