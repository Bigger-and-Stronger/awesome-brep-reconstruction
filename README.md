# Awesome Brep Reconstruction
A list on Brep reconstruction, primarily consisting of academic papers, along with some useful open-source projects and dataset. 

It should be noted that, in addition to the complete implementation of Brep reconstruction, we also considered related work on **CAD Model Segmentation**, **Surface Fitting** and **Primitive Recognition**, as these are important steps in BRep reconstruction.

:blush: I will update this list regularly. 


# Paper 2021 - 2025
- Zeyu Shen, Mingyang Zhao, Dong-Ming Yan, Wencheng Wang. *"Mesh2Brep: B-rep Reconstruction via Robust Primitive Fitting and Intersection-aware Constraints"*. 
  - TVCG 2025
  - [[Paper](https://ieeexplore.ieee.org/document/10824954)]
- Kseniya Cherenkova, Elona Dupont, Anis Kacem, Gleb Gusev, Djamila Aouada. *"SpelsNet: Surface Primitive Elements Segmentation by B-Rep Graph Structure Supervision"*. 
  - NeurIPS 2024
  - [[Paper](https://proceedings.neurips.cc/paper_files/paper/2024/file/028ef7e68a5ea25fc26cd6abf3a5c147-Paper-Conference.pdf)][[Open Review](https://openreview.net/forum?id=Ad3PzTuqIq)]
- Yilin Liu, Jiale Chen, Shanshan Pan, Daniel Cohen-Or, Hao Zhang, Hui Huang. *"Split-and-Fit: Learning B-Reps via Structure-Aware Voronoi Partitioning"*. 
  - SIGGRAPH 2024 
  - [[Paper](https://arxiv.org/abs/2406.05261)][[Project Page](https://vcc.tech/research/2024/BRepVP)][[Code](https://github.com/yilinliu77/NVDNet)]
- Yujia Liu, Anton Obukhov, Jan Dirk Wegner, Konrad Schindler. *"Point2CAD: Reverse Engineering CAD Models from 3D Point Clouds"*. 
  - CVPR 2024 
  - [[Paper](https://arxiv.org/abs/2312.04962)][[Project Page](https://www.obukhov.ai/point2cad)][[Code](https://github.com/prs-eth/point2cad)]
- Pu Li, Jianwei Guo, Huibin Li, Bedrich Benes, Dong-Ming Yan. *"SfmCAD: Unsupervised CAD Reconstruction by Learning Sketch-based Feature Modeling Operations"*. 
  - CVRP 2024 
  - [[Paper](https://jianweiguo.net/publications/papers/2024_CVPR_SfmCAD_main.pdf)][[Code(May be in the process of organization)](https://github.com/BunnySoCrazy/SfmCAD)]
- Anyu Mu, Zhenyu Liu, Guifang Duan, Jianrong Tan. *"Structural regularity detection and enhancement for surface mesh reconstruction in reverse engineering"*. 
  - CAD 2024
  - [[Paper](https://www.sciencedirect.com/science/article/pii/S0010448524001076)]
- Yuanqi Li, Shun Liu, Xinran Yang, Jianwei Guo, Jie Guo, Yanwen Guo. *"Surface and Edge Detection for Primitive Fitting of Point Clouds"*. 
  - SIGGRAPH 2023 Conference Proceedings
  - [[Paper](https://dl.acm.org/doi/10.1145/3588432.3591522)][[Code](https://github.com/yuanqili78/SED-Net)]
- Pu Li, Jianwei Guo, Xiaopeng Zhang, Dong-Ming Yan. *"SECAD-Net: Self-Supervised CAD Reconstruction by Learning Sketch-Extrude Operations"*. 
  - CVRP 2023 
  - [[Paper](https://jianweiguo.net/publications/papers/2023-CVPR-SECADNet.pdf)][[Code](https://github.com/BunnySoCrazy/SECAD-Net)]
- Anyu Mu, Zhenyu Liu, Guifang Duan, Jianrong Tan. *"Part-to-Surface Mesh Segmentation for Mechanical Models Based on Multi-Stage Clustering"*. 
  - CAD 2023
  - [[Paper](https://www.sciencedirect.com/science/article/pii/S0010448523000775)]
- Chiara Romanengo, Andrea Raffo , Silvia Biasotti, Bianca Falcidieno. *"Recognizing geometric primitives in 3D point clouds of mechanical CAD objects"*. 
  - CAD 2023 
  - [[Paper](https://linkinghub.elsevier.com/retrieve/pii/S0010448523000118)]
- Long Zhang, Jianwei Guo, Jun Xiao, Xiaopeng Zhang, Dong-Ming Yan. *"Blending Surface Segmentation and Editing for 3D Models"*. 
  - TVCG 2022
  - [[Paper](https://ieeexplore.ieee.org/document/9296787)]
- Haoxiang Guo, Shilin Liu, Hao Pan, Yang Liu, Xin Tong, Baining Guo. *"ComplexGen: CAD Reconstruction by B-Rep Chain Complex Generation"*. 
  - SIGGRAPH 2022
  - [[Paper](https://haopan.github.io/papers/ComplexGen.pdf)][[Project Page](https://haopan.github.io/complexgen.html)][[Code](https://github.com/guohaoxiang/ComplexGen)]
- Siming Yan, Zhenpei Yang, Chongyang Ma, Haibin Huang, Etienne Vouga, Qixing Huang. *"HPNet: Deep Primitive Segmentation Using Hybrid Representations"*. 
  - ICCV 2021
  - [[Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Yan_HPNet_Deep_Primitive_Segmentation_Using_Hybrid_Representations_ICCV_2021_paper.pdf)][[Code](https://github.com/SimingYan/HPNet)]
- Eric-Tuan Lê, Minhyuk Sung, Duygu Ceylan, Radomír Měch, Tamy Boubekeur, Niloy Mitra. *"CPFN: Cascaded Primitive Fitting Networks for High-Resolution Point Clouds"*. 
  - ICCV 2021
  - [[Paper](https://arxiv.org/abs/2109.00113)][[Code](https://github.com/erictuanle/CPFN)]

# Paper 2010 - 2020
- Gopal Sharma, Difan Liu, Evangelos Kalogerakis, Subhransu Maji, Siddhartha Chaudhuri, Radomír Měch. *"ParSeNet: A Parametric Surface Fitting Network for 3D Point Clouds"*. 
  - ECCV 2020
  - [[Paper](https://arxiv.org/pdf/2003.12181.pdf)][[Project Page](https://hippogriff.github.io/parsenet/)][[Code](https://github.com/Hippogriff/parsenet-codebase)]
- Xiaolong Yang, Xiaohong Jia. *"Simple primitive recognition via hierarchical face clustering"*. 
  - CVM 2020
  - [[Paper](https://link.springer.com/article/10.1007/s41095-020-0192-6)]
- Lingxiao Li, Minhyuk Sung, Anastasia Dubrovina, Li Yi, Leonidas Guibas. *"Supervised Fitting of Geometric Primitives to 3D Point Clouds"*. 
  - CVPR 2019 Oral
  - [[Paper](https://arxiv.org/abs/1811.08988)][[Code](https://github.com/lingxiaoli94/SPFN)]
- Truc Le, Ye Duan. *"A Primitive-based 3D Segmentation Algorithm for Mechanical CAD Models"*. 
  - GMP 2017
  - [[Paper](https://duanye.org/wp-content/uploads/2023/03/CAGD-2017-compressed.pdf)]
- István Kovács, Tamás Várady, Péter Salvi. *"Applying geometric constraints for perfecting CAD models in reverse engineering"*. 
  - GM 2015
  - [[Paper](https://www.sciencedirect.com/science/article/pii/S1524070315000211)]
  - Computers & Industrial Engineering 2012
- Jun Wang, Dong-xiao Gu, Zhanheng Gao, Zeyun Yu, Changbai Tan, Laishui Zhou. *"Feature-Based Solid Model Reconstruction"*. 
  - Journal of Computing and Information Science in Engineering 2013
  - [[Paper](https://asmedigitalcollection.asme.org/computingengineering/article-abstract/13/1/011004/371405/Feature-Based-Solid-Model-Reconstruction?redirectedFrom=fulltext)]
- Jun Wang, Dong-xiao Gu, Zeyun Yu, Changbai Tan, Laishui Zhou. *"A framework for 3D model reconstruction in reverse engineering"*. 
  - Computers & Industrial Engineering 2012
  - [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0360835212001842)]
- Jun Wang, Zeyun Yu. *"Surface feature based mesh segmentation"*. 
  - SMI 2011
  - [[Paper](https://www.sciencedirect.com/science/article/pii/S0097849311000550)]
- Dong-Ming Yan, Wenping Wang, Yang Liu, Zhouwang Yang. *"Variational Mesh Segmentation via Quadric Surface Fitting"*. 
  - CAD 2012
  - [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0010448512000887)]
- Yangyan Li, Xiaokun Wu, Yiorgos Chrysanthou, Andrei Sharf, Daniel Cohen-Or, Niloy Jyoti Mitra. *"GlobFit: consistently fitting primitives by discovering global relations"*. 
  - SIGGRAPH 2011
  - [[Paper](https://dl.acm.org/doi/10.1145/1964921.1964947)][[Code](https://github.com/yangyanli/globfit)]

# Paper Before 2010
- Ruwen Schnabel, Roland Wahl, Reinhard Klein. *"Efficient ransac for point-cloud shape detection"*. 
  - CGF 2007
  - [[Paper](https://cg.cs.uni-bonn.de/backend/v1/files/publications/schnabel-2007-efficient.pdf)][[Code](https://github.com/alessandro-gentilini/Efficient-RANSAC-for-Point-Cloud-Shape-Detection)][[CGAL Document](https://doc.cgal.org/latest/Shape_detection/index.html)]
- Dong-Ming Yan, Yang Liu, Wenping Wang. *"Quadric Surface Extraction by Variational Shape Approximation"*. 
  - GMP 2006
  - [[Paper](https://link.springer.com/chapter/10.1007/11802914_6)]
- Marco Attene, Michela Spagnuolo, Bianca Falcidieno. *"Hierarchical Mesh Segmentation based on Fitting Primitives"*.
  - TVC 2006
  - [[Paper](https://link.springer.com/article/10.1007/s00371-006-0375-x)][[Software](https://efpisoft.sourceforge.net/)]
- Tahir Rabbani, Frank Van Den Heuvel, George Vosselmann. *"Segmentation of point clouds using smoothness constraint."*.
  - ISPRS J. PhotoGramm. 2006
  - [[Paper](https://www.isprs.org/proceedings/XXXVI/part5/paper/RABB_639.pdf)][[PCL Document](https://pointclouds.org/documentation/classpcl_1_1_region_growing.html)]
- Miguel Vieira, Kenji Shimada. *"Surface mesh segmentation and smooth surface extraction through region growing"*. 
  - CAGD 2005
  - [[Paper](https://www.sciencedirect.com/science/article/pii/S0167839605000282)]
- Pál Benkö, Géza Kós, Tamás Várady, László Andor, Ralph Robert Martin. *"Constrained fitting in reverse engineering"*. 
  - CAGD 2002
  - [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0167839601000851)]
- Pál Benkö, Ralph Robert Martin, Tamás Várady. *"Algorithms for reverse engineering boundary representation models"*. 
  - CAD 2001
  - [[Paper](https://orca.cardiff.ac.uk/id/eprint/1811/1/REalgorithms.pdf)]
- A. David Marshall, Gábor Lukács, Ralph Robert Martin. *"Robust Segmentation of Primitives from Range Data in the Presence of Geometric Degeneracy"*. 
  - TPAMI 2001
  - [[Paper](https://ieeexplore.ieee.org/document/910883)]

# Brep Dataset
- [ABC Dataset](https://deep-geometry.github.io/abc-dataset/)
- [Fusion 360 Gallery Dataset](https://github.com/AutodeskAILab/Fusion360GalleryDataset)
- [MFCAD](https://github.com/hducg/MFCAD)
- [MFCAD++](https://pure.qub.ac.uk/en/datasets/mfcad-dataset-dataset-for-paper-hierarchical-cadnet-learning-from)

# Useful Project (including but not limited to)
- [Open CASCADE Technology](https://dev.opencascade.org/)
- [Geometric Tools Engine](https://github.com/davideberly/GeometricTools)
- [EfPiSoft](https://efpisoft.sourceforge.net/)
- [OCC-QT-Demo](https://github.com/ajune-wang/OCC-QT-Demo)
- [OpenCASCADE中文学习笔记](https://github.com/KonXiong/OpenCASCADE)



