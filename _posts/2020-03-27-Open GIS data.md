---
title: "Transfer of Semantics: Usability Analysis of Semantic 3D Building Models in Automatic Annotation of MLS Point Clouds"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - Master Thesis
  - MLS point clouds
  - digital twin
  - 3D GIS
  - Labeling
---


![photo](/assets/images/lod3b.png)


**Intro**


For training and validation of machine learning models, one needs to have a reliable source of the ground-truth information. Currently, most of the ground-truth annotations for Mobile Laser Scanning (MLS) point clouds are acquired manually which is both a laborious and tedious task that prevents scalability of the solution. Moreover, even manually annotated datasets mostly do not consist of classes depicting building’s details like windows or doors which excludes them from applications regarding 3D models reconstruction. 

Nowadays, most of large cities around the world maintain highly reliable 3D models characterized by high global accuracy and rich semantics at different level of details (LoD). Therefore, it is believed that the legacy of semantic city models created throughout the years should not be squandered and the a priori knowledge of the scene can be transferred to MLS point clouds.

**The aim of this project is:**
- to develop a method for information transfer from structured (semantic 3D models) to unstructured (point clouds) datasets. 
- The method should address co-registration issues of fused datasets. The evaluation should be conducted w.r.t. transfer accuracy by comparison with labeled point cloud datasets. 
- The critical review of city models usability should be provided analyzing city models availability at different levels of details and its impact on the final accuracy.

The requirements for this Thesis are:
- basic knowledge of GIS and 
- good skills in Python (or similar).  


**Contact:**

- Chair:                                     Photogrammetry & Remote Sensing

- Supervisor:                           Olaf Wysocki, M.Sc.

- Office:                                    1776, TUM main campus

- E-Mail:                                  olaf.wysocki@tum.de

**References:**

Biljecki, F., Stoter, J., Ledoux, H., Zlatanova, S. and Çöltekin, A., (2015) Applications of 3D city models: State of the art review. ISPRS International Journal of Geo-Information, 4(4), pp.2842-2889

Griffiths D., Boehm J. (2019) A review on deep learning techniques for 3D sensed data classification. Remote Sensing, 11: 1499–1528

Schwab B, Haas-Goschenhofer S and Wysocki O, (2020) LoD3 Road Space Models. [https://github.com/savein/lod3-road-space-models](https://github.com/savein/lod3-road-space-models) (31 January 2021)

Zhu J., Gehrung J., Huang R., Borgmann B., Sun Z., Hoegner L., Hebel M., Xu Y., Stilla U. (2020) TUM-MLS-2016: An annotated mobile LiDAR dataset of the TUM city campus for semantic point-cloud interpretation in urban areas. Remote Sensing, 12(11): 1875
