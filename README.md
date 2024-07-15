# Motor_AI_Exercise1

Python solution of practical exercise 1 of Motor AI challenge. 

The goal of the exercise is to assess skills regarding to open source satellite data acquisition as well as analyzing and processing vector and raster data.

The script first downloads a Sentinel 2 image for Berlin region as well as OSM road data. S2 image is masked (clipped) with buffered roads that are filtered wrt to a speed and direction limit. 

In last steps, clipped image is reprojected to EPSG: 25833 and raster tiles with sizes of 512 by 512 is generated.

### Visualization of initial Sentinel 2 image for Berlin region:

![image](https://github.com/user-attachments/assets/90a91ebf-7902-4aca-bd46-66bf38475e86)

### Reprojected masked Sentinel-2 image:

![image](https://github.com/user-attachments/assets/8db300ec-9b53-433b-a114-8ce2fbe31ec7)

### JPEG image tiles (512x512) displayed in QGIS:
<img width="827" alt="image_tiles_512x512" src="https://github.com/user-attachments/assets/ac0c5ec7-9bc9-4ce5-8443-8543d7a3802e">



