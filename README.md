# Pothole
A Hybrid Method to calculate the depth of pothole using LiDAR and Point Cloud
This study presents an automated approach for
detecting potholes and estimating their depth using LiDAR point
cloud data. The methodology involves pre-processing raw LiDAR
data, segmenting the road surface, clustering pothole regions, and
calculating their dimensions. The proposed system utilizes
DBSCAN clustering and convex hull techniques to accurately
identify and measure potholes. The methodology involves
collecting 3D point cloud data from LiDAR sensors, specifically
from .las files, to ensure accurate surface reconstruction. The preprocessing stage applies voxel down-sampling, statistical noise
removal, and plane segmentation using RANSAC to differentiate
road surfaces from potholes. The DBSCAN clustering algorithm is
then utilized to identify pothole regions, and convex hull estimation
aids in extracting the precise dimensions of potholes. The preprocessing stage applies voxel down-sampling, statistical noise
removal, and plane segmentation using RANSAC to differentiate
road surfaces from potholes. The DBSCAN clustering algorithm is
then utilized to identify pothole regions, and convex hull estimation
aids in extracting the precise dimensions of potholes. The approach
enables real-time visualization and accurate depth calculation of
potholes, which is crucial for road safety and maintenance. ![ScreenCapture_2025-03-18-22-22-16](https://github.com/user-attachments/assets/a70be821-b383-40cf-89fb-f586794e5ab3)

Step 3: Input Data into depth.ipynb 
- Load the processed point cloud into depth.ipynb for depth estimation.  
- Run depth estimation and pothole detection.  
- Extract pothole depth in meters.  

Step 4: Visualize & Analyze Results![output](https://github.com/user-attachments/assets/9d62beea-c58d-4fb8-ace4-1408a08baae8)
