# Sentinel-2-Water-Segmentation
The public dataset for water segmentation using Sentinel-2 multi-spectral satallite imagery
##The dataset can be accessed through [Google Drive](https://drive.google.com/file/d/1FZyT70mTAMyMYGSv8JcDj3uctnkjqtPZ/view?usp=sharing) or [Baidu Net Disk](https://pan.baidu.com/s/1Iy2iiWr3MkITSsfjPp30ww) for Chinese users with code:t6uy

##The dataset is organised as follows:
  ~~~
  ${Sentinel-2 water body detection dataset}
  |-- 2018.04
  `-- |-- rgb_nir
      |   |-- rgb_nir.tif
  `-- |-- swir
      |   |-- swir.tif
  |-- 2018.12
  `-- |-- rgb_nir
      |   |-- rgb_nir.tif
  `-- |-- swir
      |   |-- swir.tif
  |-- label.tif

##
The dataset included two batches of data of same area (Chengdu City) which are collected on April 2018 and December 2018 respectively. The pixelwise label is annotated based on The April's data.
###
rgb_nir.tif(20982 x 20982 x 4 pixels) contains 4 bands (r,g,b,nir) raw raster pixel information and is of 10m pixel resolution.
###
swir.tif(10491 x 10491 x 1 pixels) contains swir band raw raster pixel information and is in 20m pixel resolution.
