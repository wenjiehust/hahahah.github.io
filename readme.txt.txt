#我们的工作主要就是搬运了部分的代码，并对其中某一些代码进行了编译运行，然后整合在了一下。

我们所选的平台是Windows 7:
1.首先分别解压缩CMVS-PMVS-master.zip，pba_v1.0.5.zip,SiftGPU-V400.zip,VisualSFM_windows_64bit.zip
四个文件，然后根据需要进行下面的工作：

2.编译：
进入SiftGPU-V400.zip解压缩的文件夹内部，按照readme里面的指示进行SiftGpu代码的编译。
然后进入pba_v1.0.5.zip解压缩的文件夹内部，按照readme里面的指示进行pba代码的编译。
而CMVS可以直接用其中的可执行文件。

3.运行：
把上面编译得到的SiftGPU64.dll，pba_x64.dll，cmvs.exe放入到VisualSFM_windows_64bit.zip解压缩的文件夹中和
VisualSFM.exe所在的同一级目录下，然后就可以执行VisualSFM.exe进入界面来操作执行三维重建。

注：本VisualSFM_windows_64bit.zip里面经过我们的整合已经包含了所有所需要的库和可执行文件，可以解压缩后
直接使用。

4.界面操作：
VisualSFM.exe的简要操作步骤可以参照网站：http://ccwu.me/vsfm/中的操作指示，非常简单方便。

5.表面重建和纹理映射：
后续点云的表面重建和纹理映射，我们使用MeshLab这个软件来进行操作，参照http://blog.csdn.net/xiaolizi399/article/details/44300581
这篇博客中的内容。