# Multi-Epoch and Multi-Imagery (MEMI) Photogrammetric Workflow for Enhanced Change Detection Using Time-Lapse Cameras
Author: Xabier Blanch<br/>
Contact: xabierblanch@gmail.com<br/>
Publication: https://www.mdpi.com/2072-4292/13/8/1460

Code developed in MATLAB to perform the PCStacking algorithm on point clouds. The code is developed for a particular case, some modifications will be necessary.

* More information is detailed in the [article](https://www.mdpi.com/2072-4292/13/8/1460) 

How to citate:
-----

Blanch, X.; Eltner, A.; Guinau, M.; Abellan, A. Multi-Epoch and Multi-Imagery (MEMI) Photogrammetric Workflow for Enhanced Change Detection Using Time-Lapse Cameras. Remote Sens. 2021, 13, 1460. https://doi.org/10.3390/rs13081460

Graphical Abstract:
-----

![remotesensing-13-01460-ag](https://user-images.githubusercontent.com/37353398/151870101-b3b4cb57-fed8-4af3-bd7f-d1626d6edb60.png)

Usage
-----
In this repository are the codes needed to automatically process the MEMI workflow in the [Agisoft Metashape](https://www.agisoft.com/) (c) software. The process has been divided into two codes. The code is developed for a particular case, some modifications will be necessary.

* [metashape_aligment_backup.py](metashape_aligment_backup.py) -> This code is in charge of bundle adjustment and camera alignment.

* [metashape_densecloud.py](metashape_densecloud.py) -> This code is responsible for computing the dense point cloud.

Contribute
-----

Contributions are always welcome!
Feel free to contact me: xabierblanch@gmail.com

License
-----

Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)<br/><br/>
[![CC0](https://licensebuttons.net/i/cc-gift-guide/by-sa.png)](https://creativecommons.org/licenses/by-sa/4.0/)
