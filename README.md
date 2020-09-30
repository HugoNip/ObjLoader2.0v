# How to Convert OBJ to Point Cloud

## Point Cloud Library (PCL)

source code path: ./path/to/pcl/io/tools/converter.cpp

converter.cpp converts OBJ, PCD, PLY, STL, VTK files containing point clouds or meshes into every other format. This tool allows to specify the file output type between ASCII, binary and binary compressed.

Compile the code and run following command:

```
$ ./build/bin/pcl_converter -c ./model/source.obj ./results/dest.pcd
```




## Download
[**PCL**](https://github.com/PointCloudLibrary/pcl)    
