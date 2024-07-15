# Motor_AI_Exercise1

Python solution of practical exercise 1 of Motor AI challenge. 

The goal of the exercise is to assess skills regarding to open source satellite data acquisition as well as analyzing and processing vector and raster data.

The script first downloads a Sentinel 2 image for Berlin region as well as OSM road data. S2 image is masked (clipped) with buffered roads that are filtered wrt to a speed and direction limit. 

In last steps, clipped image is reprojected to EPSG: 25833 and raster tiles with sizes of 512 by 512 is generated.

Reprojected masked Sentinel-2 image:

![image](https://github.com/user-attachments/assets/8db300ec-9b53-433b-a114-8ce2fbe31ec7)

