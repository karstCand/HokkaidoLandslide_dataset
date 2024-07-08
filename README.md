# HokkaidoLandslide_dataset
Candide Lissak, Thomas Corpetti
##
This page contains the dataset used in our paper *Fusion network and open access dataset for landslide detection: a comparative analysis on bijie and hokkaido datasets* presented in [IGARSS 2024](https://www.2024.ieeeigarss.org/). If you use this dataset, please cite the following paper :

[1] Lissak, C. and Corpetti, T. (2024, July). Fusion network and open access dataset for landslide detection: a comparative analysis on bijie and hokkaido datasets.  In _IGARSS 2024-2024 IEEE International Geoscience and Remote Sensing Symposium_ (pp. 5231-5234). IEEE [pdf](https://drive.google.com/file/d/1DoQ-xDvX0h-5yzjXHQ3JSopgCLt2GBvw/view?usp=sharing).
##
### About data and study site
The Hokkaido dataset focuses on landslide events triggered in the eastern Iburi region in Hokkaido island in Japan (Sept.2018) by a  $M_w 6.6$ [earthquake in 2018](https://link.springer.com/article/10.1007/s10346-019-01206-7). The landslide dataset has been created from high spatial resolution RGB images (Sentinel-2) and [10m elevation models](https://fgd.gsi.go.jp/download/menu.php). The small dataset (70 images) encompasses more than 7 800 landslides  within the Hokkaido region (Japan) mixing shallow and deep landslides with various sizes.
##

### Images used for training / testing our network
- The dataset used in our paper [1] is composed of 68 snippets (39 training/ 14 validation/15 test) image patches. We have used this network for fine tuning a network trained on [Bijie Dataset](http://gpcv.whu.edu.cn/data/Bijie_pages.html). As this network is trained on RGB images, we have used the following SENTINEL-2 bands : B02, B03, B04
- All snippets can be downloaded here :
	- [png](https://drive.google.com/file/d/1eRh6XMw7R8V3AkOPIHmsAvu5kZ_aIoDX/view?usp=sharing) (8-bits from 0 to 255)
	- [geotif](https://drive.google.com/file/d/1_fq7bNhYA1S09q5oihIdcHfPfBRtV-8i/view?usp=sharing)

##

### Raw data
Below are the geotiff complete scenes:
- [DEM](https://drive.google.com/file/d/1TcqJFyFWyfCtUHjV1fXpf5voxV0Cy4dF/view?usp=sharing)
- [SENTINEL-2 (all bands)](https://drive.google.com/file/d/1oeVaJI3igoCuvKj6kpsnKUzZKQgL0i49/view?usp=sharing)
- [Masks of landslides](https://drive.google.com/file/d/1w45lS41lcuCTCEEMTjTqn1_TzWlNMI9f/view?usp=sharing)

We created these snippets from openaccess data:
- Raw landslide inventory at northern Atsuma (Iburi Subprefecture in southern Hokkaido, Japan) www.gsi.go.jp ;
- Digital elevation model (DEM) of 10m resolution https://fgd.gsi.go.jp/download/menu.php ;
- Multispetral data with Sentinel 2 images https://dataspace.copernicus.eu/
##
### Categories
Landslide, remote sensing, machine learning, deep learning, satellite image
