
---
title: "Filling-in Gaps: Increasing Coverage of Buildings in MLS Point Clouds Using Crowd-sourced Images"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - TUM
  - standard
  - digital twin
  - point clouds
  - MLS
  - 3D GIS
  - SfM
  - crowdsourcing
---

![photo](/assets/images/lod3.png)


**Intro**
Nowadays, many cities around the world create semantic 3D city models. However, these models have mostly coarse geometrical representation. As more and more mobile mapping units capture road space environments, datasets barely available before are emerging. This enables reconstruction of 3D models details like buildings‘ façades. Such 3D models are utilized in e.g., autonomous driving simulations, solar potential analysis, and urban planning.

Nevertheless, the Mobile Laser Scanning (MLS) technique has several challenges to overcome w.r.t. building reconstruction. One of them are discontinuities in point clouds depicting buildings that results from occlusions due to presence of objects like trees, parked cars, or traffic signs. Pararelly, the growing popularity of crowd-sourcing platforms (e.g., Mapillary) and social media images (e.g., Flickr) results in influx of data describing city objects in variety of poses at the street level.

**The aim of this project is:**
- to increase coverage of MLS point clouds depicting 3D building models by means of photogrammetric point clouds acquired from crowd-sourced images. 
- In order to estimate the discontinuities in the prior state a projection of point cloud subsets to respective 3D building models is required. Then, estimations of point cloud coverage and gaps should be performed. 
- The crowd-sourced images should be acquired for respective buildings and the scene should be reconstructed. 
- Then the co-registration and fusion of datasets should be performed. 
- Finally, prior scene should be compared with the enriched one and the magnitude of the increased coverage assessed.

The requirements for this Thesis are:
- basic knowledge of GIS and 
- good skills in Python (or similar).  


**Contact:**

- Chair:                                     Photogrammetry & Remote Sensing

- Supervisor:                           Olaf Wysocki, M.Sc.

- Office:                                    1776, TUM main campus

- E-Mail:                                  olaf.wysocki@tum.de

**References:**

Balado Frías, J., Gonzalez Rodriguez, M.E., Verbree, E., Díaz Vilariño, L. and Lorenzo Cimadevila, H.R., 2020. Automatic detection and characterization of ground occlusions in urban point clouds from mobile laser scanning data Griffiths D., Boehm J.  (2019) A review on deep learning techniques for 3D sensed data classification. Remote Sensing, 11:  1499–1528

Biljecki, F., Stoter, J., Ledoux, H., Zlatanova, S. and Çöltekin, A., (2015) Applications of 3D city models: State of the art review. ISPRS International Journal of Geo-Information, 4(4), pp.2842-2889

Chan PH, Dhadyalla G, Donzella V (2020) A Framework to Analyze Noise Factors of Automotive Percep-tion Sensors.  IEEE Sensors Letters, 4:  1–4

Goebbels S, Pohle-Fr ̈ohlich R, Pricken P (2019) Iterative Closest Point algorithm for accurate registration ofcoarsely registered point clouds with CityGML models. ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, IV-2/W5:  201–208

Schwab B, Haas-Goschenhofer S and Wysocki O, (2020) LoD3 Road Space Models. https://github.com/savein/lod3-road-space-models (31 January 2021)

Tuttas S, Stilla U (2012) Reconstruction of rectangular windows in multi-looking oblique view ALS data. ISPRS Annals of Photogrammetry, Remote Sensing and Spatial Information Sciences, I-3:  317–322

Zhu J., Gehrung J., Huang R., Borgmann B., Sun Z., Hoegner L., Hebel M., Xu Y., Stilla U. (2020) TUM-MLS-2016: An annotated mobile LiDAR dataset of the TUM city campus for semantic point-cloud interpretation in urban areas. Remote Sensing, 12(11): 1875

