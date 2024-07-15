# Motor_AI_Exercise1

Python solution of Motor AI Challenge - Practical Exercise 1.

The goal of the exercise is to assess skills regarding acquisition of open-source satellite data as well as analyzing and processing vector and raster data.

The script first downloads a Sentinel-2 (S2) image for the Berlin region together with OSM road data. S2 image is masked (clipped) with buffered roads that are filtered with respect to a speed (max. speed >=50) and direction (direction of travel is forward) limit.

In the last steps, the clipped image is reprojected to EPSG: 25833, and 110 raster tiles with sizes of 512 by 512 are generated from the clipped image.

### Visualization of initial Sentinel-2 image for Berlin region:

![image](https://github.com/user-attachments/assets/90a91ebf-7902-4aca-bd46-66bf38475e86)

### Reprojected masked Sentinel-2 image:

![image](https://github.com/user-attachments/assets/8db300ec-9b53-433b-a114-8ce2fbe31ec7)

### JPEG image tiles (512x512) displayed in QGIS:
<img width="827" alt="image_tiles_512x512" src="https://github.com/user-attachments/assets/ac0c5ec7-9bc9-4ce5-8443-8543d7a3802e">



