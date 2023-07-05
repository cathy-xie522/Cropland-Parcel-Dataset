# Cropland-Parcel-Dataset
To address the lack of public dataset of cropland parcels that can be used for deep learning model training, we adopts ArcGIS software to manually label the samples in the images based on two GF-2 remote sensing images which are located in different regions, such as Funan County, Anhui Province and Ruian County, Zhejiang Province. We cropped them into 1,761 tiles with 512×512 pixels. The ready-to-use samples are divided into three parts: a training set (1,059 tiles), a validation set (351 tiles) and a test set (351 tiles).

The main types of farmland included in our dataset are: dryland, paddy field, fallow land and shed-grown land.
![Image text](https://github.com/cathy-xie522/img-folder/blob/main/%E5%86%9C%E7%94%B0%E4%B8%BB%E8%A6%81%E7%B1%BB%E5%9E%8B1.jpg)

We took into account the diversity of cropland types and spatial distribution differences, and selected the sample construction area on the premise of including all cropland types as far as possible and ensuring the completeness of the sample. In the process of vector data production, we strictly follow the cross-checking method to ensure the quality of the dataset.
![Image text](https://github.com/cathy-xie522/img-folder/blob/main/%E6%A0%B7%E6%9C%AC%E6%9E%84%E5%BB%BA%E5%8C%BA%E5%9F%9F%E9%80%89%E5%8F%962.jpg)

The shapefile was rasterized. Finally we produced three formats based on the characteristics of three different types of tasks: semantic segmentation, edge detection and instance segmentation.
![Image text](https://github.com/cathy-xie522/img-folder/blob/main/%E6%A0%85%E6%A0%BC%E6%A0%87%E7%AD%BE%E7%A4%BA%E6%84%8F%E5%9B%BE1.JPG)
