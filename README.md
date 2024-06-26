# 3D Shape Recognition and Clustering
A mesh clustering tool for Rhino3D. It can filter/ cluster similar 3d meshes from mesh pools. The tool is sensitive to minute changes in shapes of meshes. So even meshes with similar face counts but varied topologies can be differentiated successfully.

<p align="center" width="100%">
<img src="https://github.com/gasingh/shapeRecognition/blob/main/meshFaceListMapper_and_builder_%20diverseMeshesFilter%26Align_03%20-%20Copy__newViews_run1_frame_5.png" width="400" />
<img src="https://github.com/gasingh/shapeRecognition/blob/main/240601_shapeClusters_run2-zoomInLook_edit3_frame_112.png" width="400" />
  <br>
</p>

`#statistics` `#linear-algebra` `#unsupervised learning` `#ML` `#applied-maths` `#3d` `#computational geometry`

## Toolkit Purpose
The 3d shape recognition toolkit exposes the following new functionalities inside Rhino3D as commands:
1. Select similar mesh geometries.
2. Automated Clustering of mesh geometries.

## Use cases
1. **3D Geometry Clustering**: The tool allows for generation of 3d shape based estimates.
2. **Relevance in Architecture, Engineering and Construction**: Automated clustering of families.

4. **Relevance in Archeology Research**: This can be an useful tool in finding similar shaped scanned artifacts in digital archives, and can be used by Archeologists who are interested in differentiating 3d artifacts based on minute details, and subtle variation of those details. Eg. the rim of the base of a ceramic cup/ the handles of kettles can vary across artifacts from different historic periods. All these are relevant important details, and this tool can help capture them.

## Documentation
### i. Picker from Mesh Pool
<p align="center" width="100%">
<img src="https://github.com/gasingh/shapeRecognition/blob/main/240530_meshSimilarity_pickFromMeshPool.gif" width="600" /> <br>
<i> The GIF illustrates the shape selection functionality.</i> <br>
</p>

### ii. Automated Shape Clusters
The tool automatically clusters unique 3d meshes from an ordered collection of meshes.
<p align="center" width="100%">
<img src="https://github.com/gasingh/shapeRecognition/blob/main/240601_shapeClusters_run2_edit2.gif" width="600" /> <br>
<i> The GIF illustrates automated generation of shape clusters from an unlabelled collection of mesh objects.</i> <br> 
  <img src="https://github.com/gasingh/shapeRecognition/blob/main/240601_shapeClusters_run2_edit2_frame_1.png" width="400" />
<img src="https://github.com/gasingh/shapeRecognition/blob/main/240601_shapeClusters_run2_edit2_frame_474.png" width="400" /> <br>
  <img src="https://github.com/gasingh/shapeRecognition/blob/main/240601_shapeClusters_run2_edit2_frame_682.png" width="400" /> 
  <img src="https://github.com/gasingh/shapeRecognition/blob/main/240601_shapeClusters_run2_edit2_frame_775.png" width="400" /><br>
  <img src="https://github.com/gasingh/shapeRecognition/blob/main/240601_shapeClusters_run2_edit2_frame_868.png" width="400" /> 
  <img src="https://github.com/gasingh/shapeRecognition/blob/main/240601_shapeClusters_run2-zoomInLook_edit3_frame_458.png" width="400" /> <br>
<i> Images above showcase the automated clustering process in sequence. </i>
  <img src="https://github.com/gasingh/shapeRecognition/blob/main/240601_shapeClusters_run2-zoomInLook_edit3_resized3.gif" width="600" /> <br>
<i> The GIF takes a closer look at the dataset of 3d meshes. </i>i><br>
</p>

### iii. Difference Volume Generation across similar looking meshes
(WIP) <br>
_The GIF illustrates the generation of shape volumes for finding out shape differences._


