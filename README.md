# Mesh to PointCloud

This tool can uniformly sample 3D points from mesh. The 3D point cloud is used for pose estimation of known objects using ICP. 
The output is a simple ascii format `[x] [y] [z]` point cloud file.

## Requirements
- python3
- numpy
- trimesh

## Usage

```
python mesh2points.py [-h] -i INPUT_FILE -o OUTPUT_FILE [-n NUMBER_OF_POINTS] [--normalize]

python mesh2points.py -i model.stl -o output.pcd -n 1000

python mesh2points.py -i model.stl -o output.pcd -n 1000 --normalize
```

## TODO

- `.pcd`, `.xyz`, and `.pts` .etc file formats support
