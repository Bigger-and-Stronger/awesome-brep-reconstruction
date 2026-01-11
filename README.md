# Awesome Brep Reconstruction [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A list on Brep reconstruction, primarily consisting of academic papers, along with some useful open-source projects and dataset. 

It should be noted that, in addition to the **Complete Implementation of Brep Reconstruction**, we also considered related work on **CAD Model Segmentation**, **Surface Fitting**, **Primitive Recognition** and **Feature-line Reconstruction**, as these are important steps in BRep reconstruction.

:blush: I will update this list regularly. 

# Keywords
__`seg.`__ : cad model segmentation &emsp; | &emsp; __`fit.`__ : surface fitting 

__`pri.`__ : primitive recognition &emsp; | &emsp; __`fea.`__ : feature-line reconstruction

__`com.`__ : complete implementation of brep reconstruction &emsp; | &emsp; __`oth.`__ : other

:balloon: **reference to [awesome-point-cloud-analysis](https://github.com/Yochengliu/awesome-point-cloud-analysis).**

:confounded: The categorization of these directions may carry some ambiguity, therefore **the above classification is solely based on my personal subjective judgment** !
# 2026
- Fuentes Perez, Lizeth J. and Lafarge, Florent and Pajarola, Renato. *"NURBSFit: Robust Fitting of NURBS Surfaces to Point Clouds"*. 
  - 3DV 2026
  - [[Paper](https://hal.science/hal-05411017/document)][[Code](https://github.com/lizOnly/nurbsfit)]
  - __`seg.`__ __`fit.`__ __`pri.`__ 

# 2025
- Yilin Liu, Duoteng Xu, Xingyao Yu, Xiang Xu, Daniel Cohen-Or, Hao Zhang, Hui Huang. *"HoLa: B-Rep Generation using a Holistic Latent Representation"*. 
  - SIGGRAPH 2025
  - [[Paper](https://arxiv.org/abs/2504.14257)][[Project Page](https://vcc.szu.edu.cn/research/2025/HolaBRep)][[WebUI](https://huggingface.co/spaces/YuXingyao/HoLa-BRep)]
  - __`com.`__
- Jing-En Jiang, Hanxiao Wang, Mingyang Zhao, Dong-Ming Yan, Shuangmin Chen, Shiqing Xin, Changhe Tu, Wenping Wang. *"DeFillet: Detection and Removal of Fillet Regions in Polygonal CAD Models"*. 
  - SIGGRAPH 2025
  - [[Paper](https://dl.acm.org/doi/abs/10.1145/3731166)][[Project Page](https://xiaowuga.github.io/pub/DeFillet.html)][[Code](https://github.com/xiaowuga/DeFillet)]
  - __`seg.`__
- Yuan Li, Cheng Lin, Yuan Liu, Xiaoxiao Long, Chenxu Zhang, Ningna Wang, Xin Li, Wenping Wang, Xiaohu Guo. *"CADDreamer: CAD object Generation from Single-view Images"*. 
  - CVPR 2025
  - [[Paper](https://lidan233.github.io/caddreamer/static/papers/main.pdf)][[Project Page](https://lidan233.github.io/caddreamer/)][[Code](https://github.com/lidan233/CADDreamer)]
  - __`com.`__
- Cheng Chen, Jiacheng Wei, Tianrun Chen, Chi Zhang, Xiaofeng Yang, Shangzhan Zhang, Bingchen Yang, Chuan-Sheng Foo, Guosheng Lin, Qixing Huang, Fayao Liu. *"CADCrafter: Generating Computer-Aided Design Models from Unconstrained Images"*. 
  - CVPR 2025
  - [[Paper](https://arxiv.org/pdf/2504.04753)]
  - __`com.`__
- Danila Rukhovich, Elona Dupont, Dimitrios Mallis, Kseniya Cherenkova, Anis Kacem, Djamila Aouada. *"CAD-Recode: Reverse Engineering CAD Code from Point Clouds"*. 
  - ICCV 2025
  - [[Paper](https://arxiv.org/abs/2412.14042)][[Project Page](https://cad-recode.github.io/)][[Code](https://github.com/filapro/cad-recode)]
  - __`com.`__
- Zheng Fang, Chuanqing Zhuang, Zhengda Lu, Yiqun Wang, Lupeng Liu, Jun Xiao. *"BGPSeg: Boundary-Guided Primitive Instance Segmentation of Point Clouds"*. 
  - TIP 2025
  - [[Paper](https://ieeexplore.ieee.org/document/10896454)][[Code](https://github.com/fz-20/BGPSeg)]
  - __`seg.`__ __`pri.`__ 
- Yuanqi Li, Hongshen Wang, Yansong Liu, Jingcheng Huang, Shun Liu, Chenyu Huang, Jianwei Guo, Jie Guo, Yanwen Guo. *"Deep Point Cloud Edge Reconstruction via Surface Patch Segmentation"*. 
  - TVCG 2025
  - [[Paper](https://ieeexplore.ieee.org/abstract/document/10909144)]
  - __`seg.`__ __`fea.`__ 
- Zeyu Shen, Mingyang Zhao, Dong-Ming Yan, Wencheng Wang. *"Mesh2Brep: B-rep Reconstruction via Robust Primitive Fitting and Intersection-aware Constraints"*. 
  - TVCG 2025
  - [[Paper](https://ieeexplore.ieee.org/document/10824954)]
  - __`seg.`__ __`fit.`__  __`com.`__ 
- Yike Xu, Jianwei Guo, Li Cao, Xiaoping Liu. *"EDWG: Efficient Edge Detection and Wireframe Generation from Point Clouds"*. 
  - IEEE Transactions on Instrumentation & Measurement, 2025
  - [[Paper](https://ieeexplore.ieee.org/abstract/document/11005571)]
  - __`fea.`__ 
- Nomi Yu, Md Ferdous Alam, A John Hart, Faez Ahmed. *"GenCAD-3D: CAD Program Generation Using Multimodal Latent Space Alignment and Synthetic Dataset Balancing"*. 
  - International Design Engineering Technical Conferences and Computers and Information in Engineering Conference, 2025
  - [[Paper](https://arxiv.org/pdf/2509.15246)][[Code](https://github.com/yunomi-git/GenCAD-3D)]
  - __`com.`__

# 2024
- Yilin Liu, Jiale Chen, Shanshan Pan, Daniel Cohen-Or, Hao Zhang, Hui Huang. *"Split-and-Fit: Learning B-Reps via Structure-Aware Voronoi Partitioning"*. 
  - SIGGRAPH 2024 
  - [[Paper](https://arxiv.org/abs/2406.05261)][[Project Page](https://vcc.tech/research/2024/BRepVP)][[Code](https://github.com/yilinliu77/NVDNet)]
  - __`seg.`__ __`com.`__
- Yujia Liu, Anton Obukhov, Jan Dirk Wegner, Konrad Schindler. *"Point2CAD: Reverse Engineering CAD Models from 3D Point Clouds"*. 
  - CVPR 2024 
  - [[Paper](https://arxiv.org/abs/2312.04962)][[Project Page](https://www.obukhov.ai/point2cad)][[Code](https://github.com/prs-eth/point2cad)]
  - __`fit.`__  __`com.`__ 
- Mohsen Yavartanoo, Sangmin Hong, Reyhaneh Neshatavar, Kyoung Mu Lee. *"CNC-Net: Self-Supervised Learning for CNC Machining Operations"*. 
  - CVPR 2024 
  - [[Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Yavartanoo_CNC-Net_Self-Supervised_Learning_for_CNC_Machining_Operations_CVPR_2024_paper.html)][[Code](https://github.com/myavartanoo/CNC-Net_PyTorch)]
  - __`com.`__ 
- Mohammad Sadil Khan, Elona Dupont, Sk Aziz Ali, Kseniya Cherenkova, Anis Kacem, Djamila Aouada. *"CAD-SIGNet: CAD Language Inference from Point Clouds using Layer-wise Sketch Instance Guided Attention"*. 
  - CVPR 2024 
  - [[Paper](https://arxiv.org/abs/2402.17678)][[Project Page](http://skazizali.com/cadsignet.github.io/)]
  - __`com.`__ 
- Pu Li, Jianwei Guo, Huibin Li, Bedrich Benes, Dong-Ming Yan. *"SfmCAD: Unsupervised CAD Reconstruction by Learning Sketch-based Feature Modeling Operations"*. 
  - CVRP 2024 
  - [[Paper](https://jianweiguo.net/publications/papers/2024_CVPR_SfmCAD_main.pdf)][[Code(May be in the process of organization)](https://github.com/BunnySoCrazy/SfmCAD)]
  - __`pri.`__
- Kseniya Cherenkova, Elona Dupont, Anis Kacem, Gleb Gusev, Djamila Aouada. *"SpelsNet: Surface Primitive Elements Segmentation by B-Rep Graph Structure Supervision"*. 
  - NeurIPS 2024
  - [[Paper](https://proceedings.neurips.cc/paper_files/paper/2024/file/028ef7e68a5ea25fc26cd6abf3a5c147-Paper-Conference.pdf)][[Open Review](https://openreview.net/forum?id=Ad3PzTuqIq)]
  - __`seg.`__
- Elona Dupont, Kseniya Cherenkova, Dimitrios Mallis, Gleb Gusev, Anis Kacem, Djamila Aouada. *"Transcad: A hierarchical transformer for cad sequence inference from point clouds"*. 
  - ECCV 2024
  - [[Paper](https://arxiv.org/pdf/2407.12702)]
  - __`com.`__
- Anyu Mu, Zhenyu Liu, Guifang Duan, Jianrong Tan. *"Structural regularity detection and enhancement for surface mesh reconstruction in reverse engineering"*. 
  - CAD 2024
  - [[Paper](https://www.sciencedirect.com/science/article/pii/S0010448524001076)]
  - __`oth.`__
- Yuta Fukushima, Anran Qi, I-Chao Shen, Yulia Gryaditskaya, Takeo Igarashi. *"3D Reconstruction from Sketch with Hidden Lines by Two-Branch Diffusion Model"*. 
  - EG 2024 Short Paper
  - [[Paper](https://diglib.eg.org/items/f669041e-4a18-4406-88d4-e9c20cad7cc9)]
  - __`oth.`__

# 2023
- Yuanqi Li, Shun Liu, Xinran Yang, Jianwei Guo, Jie Guo, Yanwen Guo. *"Surface and Edge Detection for Primitive Fitting of Point Clouds"*. 
  - SIGGRAPH 2023 Conference Proceedings
  - [[Paper](https://dl.acm.org/doi/10.1145/3588432.3591522)][[Code](https://github.com/yuanqili78/SED-Net)]
  - __`seg.`__ __`fea.`__ __`pri.`__ 
- Pu Li, Jianwei Guo, Xiaopeng Zhang, Dong-Ming Yan. *"SECAD-Net: Self-Supervised CAD Reconstruction by Learning Sketch-Extrude Operations"*. 
  - CVRP 2023 
  - [[Paper](https://jianweiguo.net/publications/papers/2023-CVPR-SECADNet.pdf)][[Code](https://github.com/BunnySoCrazy/SECAD-Net)]
  - __`pri.`__ 
- Rao Fu, Cheng Wen, Qian Li, Xiao Xiao, Pierre Alliez. *"BPNet: Bézier Primitive Segmentation on 3D Point Clouds"*. 
  - IJCAI 2023 
  - [[Paper](https://www.ijcai.org/proceedings/2023/84)][[Code](https://github.com/bizerfr/BPNet)]
  - __`seg.`__ __`pri.`__ 
- Anyu Mu, Zhenyu Liu, Guifang Duan, Jianrong Tan. *"Part-to-Surface Mesh Segmentation for Mechanical Models Based on Multi-Stage Clustering"*. 
  - CAD 2023
  - [[Paper](https://www.sciencedirect.com/science/article/pii/S0010448523000775)]
  - __`seg.`__ __`pri.`__ 
- Chiara Romanengo, Andrea Raffo , Silvia Biasotti, Bianca Falcidieno. *"Recognizing geometric primitives in 3D point clouds of mechanical CAD objects"*. 
  - CAD 2023 
  - [[Paper](https://linkinghub.elsevier.com/retrieve/pii/S0010448523000118)]
  - __`seg.`__ __`pri.`__ 

# 2022
- Haoxiang Guo, Shilin Liu, Hao Pan, Yang Liu, Xin Tong, Baining Guo. *"ComplexGen: CAD Reconstruction by B-Rep Chain Complex Generation"*. 
  - SIGGRAPH 2022
  - [[Paper](https://haopan.github.io/papers/ComplexGen.pdf)][[Project Page](https://haopan.github.io/complexgen.html)][[Code](https://github.com/guohaoxiang/ComplexGen)]
  - __`seg.`__ __`com.`__ 
- Albert Matveev, Ruslan Rakhimov, Alexey Artemov, Gleb Bobrovskikh, Vage Egiazarian, Emil Bogomolov, Daniele Panozzo, Denis Zorin, Evgeny Burnaev. *"DEF: Deep Estimation of Sharp Geometric Features in 3D Shapes"*. 
  - SIGGRAPH 2022
  - [[Paper](https://cims.nyu.edu/gcl/papers/2022-DEF.pdf)][[Project Page](https://artonson.github.io/publications/2022-def/)][[Code](https://github.com/artonson/def)]
  - __`fea.`__
- Rui Xu, Zixiong Wang, Zhiyang Dou, Chen Zong, Shiqing Xin, Mingyan Jiang, Tao Ju, Changhe Tu. *"RFEPS: Reconstructing Feature-line Equipped Polygonal Surface"*. 
  - SIGGRAPH Asia 2022
  - [[Paper](https://arxiv.org/abs/2212.03600)][[Project Page](https://ruixu.me/html/RFEPS/index.html)][[Code](https://github.com/Xrvitd/RFEPS)]
  - __`fea.`__ 
- Mikaela Angelina Uy, Yen-Yu Chang, Minhyuk Sung, Purvi Goel, Joseph G Lambourne, Tolga Birdal, Leonidas J Guibas. *"Point2cyl: Reverse engineering 3d objects from point clouds to extrusion cylinders"*. 
  - CVPR 2022
  - [[Paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Uy_Point2Cyl_Reverse_Engineering_3D_Objects_From_Point_Clouds_to_Extrusion_CVPR_2022_paper.pdf)][[Project Page](https://point2cyl.github.io/)][[Code](https://github.com/mikacuy/point2cyl)]
  - __`seg.`__ __`pri.`__ 
- Long Zhang, Jianwei Guo, Jun Xiao, Xiaopeng Zhang, Dong-Ming Yan. *"Blending Surface Segmentation and Editing for 3D Models"*. 
  - TVCG 2022
  - [[Paper](https://ieeexplore.ieee.org/document/9296787)]
  - __`seg.`__ __`pri.`__ 

# 2021
- Siming Yan, Zhenpei Yang, Chongyang Ma, Haibin Huang, Etienne Vouga, Qixing Huang. *"HPNet: Deep Primitive Segmentation Using Hybrid Representations"*. 
  - ICCV 2021
  - [[Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Yan_HPNet_Deep_Primitive_Segmentation_Using_Hybrid_Representations_ICCV_2021_paper.pdf)][[Code](https://github.com/SimingYan/HPNet)]
  - __`seg.`__ __`pri.`__ 
- Eric-Tuan Lê, Minhyuk Sung, Duygu Ceylan, Radomír Měch, Tamy Boubekeur, Niloy Mitra. *"CPFN: Cascaded Primitive Fitting Networks for High-Resolution Point Clouds"*. 
  - ICCV 2021
  - [[Paper](https://arxiv.org/abs/2109.00113)][[Code](https://github.com/erictuanle/CPFN)]
  - __`seg.`__ __`pri.`__ 
- Jingwei Huang, Yanfeng Zhang, Mingwei Sun. *"PrimitiveNet: Primitive Instance Segmentation with Local Primitive Embedding under Adversarial Metric"*. 
  - ICCV 2021
  - [[Paper](https://openaccess.thecvf.com/content/ICCV2021/html/Huang_PrimitiveNet_Primitive_Instance_Segmentation_With_Local_Primitive_Embedding_Under_Adversarial_ICCV_2021_paper.html)][[Code](https://github.com/hjwdzh/PrimitiveNet)]
  - __`seg.`__ __`pri.`__ 

# 2020
- Gopal Sharma, Difan Liu, Evangelos Kalogerakis, Subhransu Maji, Siddhartha Chaudhuri, Radomír Měch. *"ParSeNet: A Parametric Surface Fitting Network for 3D Point Clouds"*. 
  - ECCV 2020
  - [[Paper](https://arxiv.org/pdf/2003.12181.pdf)][[Project Page](https://hippogriff.github.io/parsenet/)][[Code](https://github.com/Hippogriff/parsenet-codebase)]
  - __`seg.`__ __`pri.`__ 
- Sommer Christiane, Sun Yumin, Bylow Erik, Cremers Daniel. *"PrimiTect: Fast Continuous Hough Voting for Primitive Detection"*. 
  - ICRA 2020
  - [[Paper](https://arxiv.org/pdf/2005.07457)][[Code](https://github.com/c-sommer/primitect)]
  - __`seg.`__ __`pri.`__ 
- Xiaolong Yang, Xiaohong Jia. *"Simple primitive recognition via hierarchical face clustering"*. 
  - CVM 2020
  - [[Paper](https://link.springer.com/article/10.1007/s41095-020-0192-6)]
  - __`seg.`__ __`pri.`__ 

# 2019
- Lingxiao Li, Minhyuk Sung, Anastasia Dubrovina, Li Yi, Leonidas Guibas. *"Supervised Fitting of Geometric Primitives to 3D Point Clouds"*. 
  - CVPR 2019 Oral
  - [[Paper](https://arxiv.org/abs/1811.08988)][[Code](https://github.com/lingxiaoli94/SPFN)]
  - __`seg.`__ __`fit.`__ __`pri.`__
- Jung Min Park, Byung Chai Lee, Soo Won Chae, Ki Youn Kwon. *"Surface reconstruction from FE mesh model"*. 
  - Journal of Computational Design and Engineering 2019
  - [[Paper](https://academic.oup.com/jcde/article/6/2/197/5732318?login=false)]
  - __`seg.`__ 
- Márton Vaitkus, Tamás Várady. *"A Labeling Algorithm for Trimmed Surface Fitting"*. 
  - CADA 2019
  - [[Paper](https://www.cad-journal.net/files/vol_16/CAD_16(4)_2019_720-732.pdf)]
  - __`fit.`__

# 2018
- Lequan Yu, Xianzhi Li, Chi-Wing Fu, Daniel Cohen-Or, Pheng-Ann Heng. *"Ec-net: an edge-aware point set consolidation network"*. 
  - ECCV 2018
  - [[Paper](https://openaccess.thecvf.com/content_ECCV_2018/papers/Lequan_Yu_EC-Net_an_Edge-aware_ECCV_2018_paper.pdf)][[Project Page](https://yulequan.github.io/ec-net/)][[Code](https://github.com/yulequan/EC-Net)]
  - __`fea.`__
- Márton Vaitkus, Tamás Várady. *"Parameterizing and extending trimmed regions for tensor-product surface fitting"*. 
  - CAD 2018
  - [[Paper](https://www.sciencedirect.com/science/article/pii/S0010448517302312)]
  - __`fit.`__
- Daniel Mejia, Oscar Ruiz-Salguero, Jairo R Sánchez, Jorge Posada, Aitor Moreno, Carlos A Cadavid. *"Hybrid geometry/topology based mesh segmentation for reverse engineering"*. 
  - C&G 2018
  - [[Paper](https://www.sciencedirect.com/science/article/pii/S0097849318300372)]
  - __`seg.`__ __`pri.`__ 

# 2017
- Yixin Zhuang, Hang Dou, Nathan Carr, Tao Ju. *"Feature-Aligned Segmentation using Correlation Clustering"*. 
  - CVM 2017
  - [[Paper](https://link.springer.com/article/10.1007/s41095-016-0071-3)][[Code](https://github.com/yixin26/Mesh-Segmentation)]
  - __`seg.`__  
- Yanpei Cao, Tao Ju, J. Xu, Shimin Hu. *"Extracting Sharp Features from RGB‐D Images"*. 
  - CGF 2017
  - [[Paper](https://www.cse.wustl.edu/~taoju/research/rgbdedge_self.pdf)]
  - __`seg.`__ __`pri.`__ 
- Truc Le, Ye Duan. *"A Primitive-based 3D Segmentation Algorithm for Mechanical CAD Models"*. 
  - GMP 2017
  - [[Paper](https://duanye.org/wp-content/uploads/2023/03/CAGD-2017-compressed.pdf)]
  - __`seg.`__ __`pri.`__ 
- Amirreza, Miandarhoie, Khalili Khalil, Mohammadinejad Hajimohammad. *"CAD mesh models segmentation into swept surfaces"*. 
  - International Journal of Advanced Manufacturing Technolog 2017
  - [[Paper](https://link.springer.com/article/10.1007/s00170-017-0437-4)]
  - __`seg.`__ __`pri.`__ 

# 2015
- Hao Pan, Yang Liu, Alla Sheffer, Nicholas Vining, Changjian Li, Wenping Wang. *"Flow Aligned Surfacing of Curve Networks"*. 
  - SIGGRAPH 2015
  - [[Paper](https://haopan.github.io/papers/sketch_surface.pdf)][[Project Page](https://haopan.github.io/curvenet_surfacing.html)][[Code](https://github.com/lingxiaoli94/SPFN)]
  - __`oth.`__ 
- István Kovács, Tamás Várady, Péter Salvi. *"Applying geometric constraints for perfecting CAD models in reverse engineering"*. 
  - GM 2015
  - [[Paper](https://www.sciencedirect.com/science/article/pii/S1524070315000211)]
  - __`oth.`__ 

# 2014
- M Bartoň, Helmut Pottmann, Johannes Wallner. *"Detection and reconstruction of freeform sweeps"*. 
  - CGF 2014
  - [[Paper](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.12287)]
  - __`seg.`__ __`fit.`__ __`pri.`__

# 2013
- Jun Wang, Dong-xiao Gu, Zhanheng Gao, Zeyun Yu, Changbai Tan, Laishui Zhou. *"Feature-Based Solid Model Reconstruction"*. 
  - Journal of Computing and Information Science in Engineering 2013
  - [[Paper](https://asmedigitalcollection.asme.org/computingengineering/article-abstract/13/1/011004/371405/Feature-Based-Solid-Model-Reconstruction?redirectedFrom=fulltext)]
  - __`com.`__ 

# 2012
- Jun Wang, Dong-xiao Gu, Zeyun Yu, Changbai Tan, Laishui Zhou. *"A framework for 3D model reconstruction in reverse engineering"*. 
  - Computers & Industrial Engineering 2012
  - [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0360835212001842)]
  - __`com.`__ 
- Dong-Ming Yan, Wenping Wang, Yang Liu, Zhouwang Yang. *"Variational Mesh Segmentation via Quadric Surface Fitting"*. 
  - CAD 2012
  - [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0010448512000887)]
  - __`seg.`__ __`fit.`__  

# 2011
- Yangyan Li, Xiaokun Wu, Yiorgos Chrysanthou, Andrei Sharf, Daniel Cohen-Or, Niloy Jyoti Mitra. *"GlobFit: consistently fitting primitives by discovering global relations"*. 
  - SIGGRAPH 2011
  - [[Paper](https://dl.acm.org/doi/10.1145/1964921.1964947)][[Code](https://github.com/yangyanli/globfit)]
  - __`oth.`__ 
- Jun Wang, Zeyun Yu. *"Surface feature based mesh segmentation"*. 
  - SMI 2011
  - [[Paper](https://www.sciencedirect.com/science/article/pii/S0097849311000550)]
  - __`seg.`__ __`pri.`__  

# 2008
- Kenichi Kanatani. *"Statistical optimization for geometric fitting: Theoretical accuracy bound and high order error analysis"*. 
  - IJCV 2008
  - [[Paper](https://iim.cs.tut.ac.jp/member/kanatani/papers/cvaccuracy.pdf)]
  - __`fit.`__
- Yuekun Lai, Shi-Min Hu, Ralph R. Martin, Paul L. Rosin. *"Fast Mesh Segmentation using Random Walks"*. 
  - SPM 2008
  - [[Paper](https://cg.cs.tsinghua.edu.cn/people/~laiyk/papers/spm08seg.pdf)]
  - __`seg.`__
- Marek Vančo, Bernd Hamann, Guido Brunnett. *"Surface reconstruction from unorganized point data with quadrics"*. 
  - CGF 2008
  - [[Paper](https://web.cs.ucdavis.edu/~hamann/VancoHamannBrunnettComputerGraphicsForumPaperRevision1_09252007.pdf)]
  - __`seg.`__ __`pri.`__

# 2007 
- Ruwen Schnabel, Roland Wahl, Reinhard Klein. *"Efficient ransac for point-cloud shape detection"*. 
  - CGF 2007
  - [[Paper](https://cg.cs.uni-bonn.de/backend/v1/files/publications/schnabel-2007-efficient.pdf)][[Code](https://github.com/alessandro-gentilini/Efficient-RANSAC-for-Point-Cloud-Shape-Detection)][[CGAL Document](https://doc.cgal.org/latest/Shape_detection/index.html)]
  - __`pri.`__ __`fit.`__ 

# 2006
- Tahir Rabbani, Frank Van Den Heuvel, George Vosselmann. *"Segmentation of point clouds using smoothness constraint."*.
  - ISPRS J. PhotoGramm. 2006
  - [[Paper](https://www.isprs.org/proceedings/XXXVI/part5/paper/RABB_639.pdf)][[PCL Document](https://pointclouds.org/documentation/classpcl_1_1_region_growing.html)]
  - __`seg.`__ 
- Marco Attene, Michela Spagnuolo, Bianca Falcidieno. *"Hierarchical Mesh Segmentation based on Fitting Primitives"*.
  - TVC 2006
  - [[Paper](https://link.springer.com/article/10.1007/s00371-006-0375-x)][[Software](https://efpisoft.sourceforge.net/)]
  - __`seg.`__ __`pri.`__  
- Dong-Ming Yan, Yang Liu, Wenping Wang. *"Quadric Surface Extraction by Variational Shape Approximation"*. 
  - GMP 2006
  - [[Paper](https://link.springer.com/chapter/10.1007/11802914_6)]
  - __`seg.`__ __`fit.`__  
- Tomohiro Mizoguchi, Hiroaki Date, Satoshi Kanai, Takeshi Kishinami. *"Segmentation of Scanned Mesh into Analytic Surfaces Based on Robust Curvature Estimation and Region Growing"*. 
  - GMP 2006
  - [[Paper](https://link.springer.com/chapter/10.1007/11802914_52)]
  - __`seg.`__ 

# 2005
- Michael Hofer, Boris Odehnal, Helmut Pottmann, Tibor Steiner, Johannes Wallner. *"3D shape recognition and reconstruction based on line element geometry"*. 
  - ICCV 2005
  - [[Paper](https://www.geometrie.tuwien.ac.at/geom/ig/publications/oldpub/2005/hopsw_line_05/paper_docs/line.pdf)]
  - __`seg.`__ __`fit.`__ __`pri.`__  
- Miguel Vieira, Kenji Shimada. *"Surface mesh segmentation and smooth surface extraction through region growing"*. 
  - CAGD 2005
  - [[Paper](https://www.sciencedirect.com/science/article/pii/S0167839605000282)]
  - __`seg.`__ 

# Before 2005
- Amir Helzer, Meir Barzohar, David Malah. *"Stable fitting of 2D curves and 3D surfaces by implicit polynomials"*. 
  - TPAMI 2004
  - [[Paper](https://ieeexplore.ieee.org/abstract/document/1323797)]
  - __`fit.`__
- Helmut Pottmann, Michael Hofer, Boris Odehnal, Johannes Wallner. *"Line geometry for 3D shape understanding and reconstruction"*. 
  - ECCV 2004
  - [[Paper](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=65e9461070d3a0f42c8f33636207a68d065888c2)]
  - __`seg.`__ __`fit.`__ __`pri.`__  
- Helmut Pottmann, Stefan Leopoldseder. *"A concept for parametric surface fitting which avoids the parametrization problem"*. 
  - CAGD 2003
  - [[Paper](http://sccg.sk/~chalmo/GM/cagd7-110304.pdf)]
  - __`fit.`__ 
- Pál Benkö, Géza Kós, Tamás Várady, László Andor, Ralph Robert Martin. *"Constrained fitting in reverse engineering"*. 
  - CAGD 2002
  - [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0167839601000851)]
  - __`fit.`__ 
- Pál Benkö, Ralph Robert Martin, Tamás Várady. *"Algorithms for reverse engineering boundary representation models"*. 
  - CAD 2001
  - [[Paper](https://orca.cardiff.ac.uk/id/eprint/1811/1/REalgorithms.pdf)]
  - __`com.`__ 
- A. David Marshall, Gábor Lukács, Ralph Robert Martin. *"Robust Segmentation of Primitives from Range Data in the Presence of Geometric Degeneracy"*. 
  - TPAMI 2001
  - [[Paper](https://ieeexplore.ieee.org/document/910883)]
  - __`seg.`__ __`fit.`__ __`pri.`__  
- Gabriel Taubin. *"An improved algorithm for algebraic curve and surface fitting"*. 
  - ICCV 1993
  - [[Paper](https://ieeexplore.ieee.org/abstract/document/378149/)]
  - __`fit.`__  

# Brep/CAD Dataset (including but not limited to)
- [ABC Dataset](https://deep-geometry.github.io/abc-dataset/)
- [Fusion 360 Gallery Dataset](https://github.com/AutodeskAILab/Fusion360GalleryDataset)
- [DeepCAD](https://www.cs.columbia.edu/cg/deepcad/)
- [WHUCAD](https://github.com/fazhihe/WHUCAD)
- [MFCAD](https://github.com/hducg/MFCAD)
- [MFCAD++](https://pure.qub.ac.uk/en/datasets/mfcad-dataset-dataset-for-paper-hierarchical-cadnet-learning-from)
- [TMCAD](https://github.com/Qiang-Zou/BRT)


# Useful Project (including but not limited to)
- [Open CASCADE Technology](https://dev.opencascade.org/)
- [pythonOCC](https://dev.opencascade.org/project/pythonocc)
- [Geometric Tools Engine](https://github.com/davideberly/GeometricTools)
- [Awesome Neural CAD](https://bunnysocrazy.com/)
- [EfPiSoft](https://efpisoft.sourceforge.net/)
- [OCC-QT-Demo](https://github.com/ajune-wang/OCC-QT-Demo)
- [OpenCASCADE中文学习笔记](https://github.com/KonXiong/OpenCASCADE)



