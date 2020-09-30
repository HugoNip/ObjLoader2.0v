# How to Convert OBJ to Point Cloud

## Point Cloud Library (PCL)

### Implement
Source code location: ./path/to/pcl/io/tools/converter.cpp

**converter.cpp** converts OBJ, PCD, PLY, STL, VTK files containing point clouds or meshes into every other format. This tool allows to specify the file output type between ASCII, binary and binary compressed.

Compile the code and run following command:

```
$ ./build/bin/pcl_converter -c ./model/source.obj ./results/dest.pcd
```
### Input

![hallway.png](https://github.com/HugoNip/ObjLoader2.0v/blob/master/figures/hallway.png)

### Output
```
$ ./build/bin/pcl_converter -c ./model/source.obj ./results/dest.pcd
Loaded a mesh with 5100 points (total size is 244800) and the following channels:
x y z normal_x normal_y normal_z curvature
Saving file ./results/havl.pcd as binary.
```


![pcl1.png](https://github.com/HugoNip/ObjLoader2.0v/blob/master/figures/pcl1.png)



## Download
[**PCL**](https://github.com/PointCloudLibrary/pcl)    
[**Online Point Cloud Viewer**](https://www.creators3d.com/online-viewer)     
