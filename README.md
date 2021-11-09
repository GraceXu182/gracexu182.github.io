<!-- ## Welcome to Mengjia Xu's Pages -->
<!--     [Main architecture](https://github.com/GraceXu182/gracexu182.github.io/blob/main/images/DynG2G_workflow.png#50*20) -->   
<!-- > Dynamic graph embedding has gained great attention recently due to its capability of learning low-dimensional and meaningful graph representations for complex temporal graphs with high accuracy. However, recent advances mostly focus on learning node embeddings as *deterministic "vectors"* for *static* graphs, hence disregarding the key graph temporal dynamics and the evolving uncertainties associated with node embedding in the latent space. In this work, we propose an efficient stochastic dynamic graph embedding method (DynG2G) that applies an inductive feed-forward encoder trained with node triplet energy-based ranking loss. Every node per timestamp is encoded as a time-dependent *probabilistic multivariate Gaussian distribution* in the latent space, hence we are able to quantify the node embedding uncertainty on-the-fly. We have considered eight different benchmarks that represent diversity in size (from 96 nodes to 87,626 and from 13,398 edges to 4,870,863) as well as diversity in dynamics, from slowly changing temporal evolution to rapidly varying multi-rate dynamics. We demonstrate through extensive experiments based on these eight dynamic graph benchmarks that DynG2G achieves new state-of-the-art performance in capturing the underlying temporal node embeddings. We also demonstrate that DynG2G can simultaneously predict the evolving node embedding uncertainty, which plays a crucial role in quantifying the *intrinsic dimensionality* of the dynamical system over time. In particular, we obtain a "universal" relation of the optimal embedding dimension, ![$L_o$](https://latex.codecogs.com/svg.image?L_o), versus the effective dimensionality of uncertainty, ![$D_u$](https://latex.codecogs.com/svg.image?D_u), and we infer that ![$L_o=D_u$](https://latex.codecogs.com/svg.image?L_o%20=%20D_u) for all cases; see Table III. This, in turn, implies that the uncertainty quantification approach we employ in the DynG2G algorithm correctly captures the intrinsic dimensionality of the dynamics of such evolving graphs despite the diverse nature and composition of the graphs at each timestamp. In addition, this ![$L_o - D_u$](https://latex.codecogs.com/svg.image?L_o&space;-&space;D_u) correlation provides a clear path to selecting adaptively the optimum embedding size at each timestamp by setting ![$L \ge D_u$](https://latex.codecogs.com/svg.image?L&space;\ge&space;D_u) -->

<!--  above not used!!!-->
<!-- # Biography -->
I am a Postdoctoral Associate at the [Center for Brains, Minds and Machines](https://cbmm.mit.edu/), [McGovern Insitute for Brain Research](https://mcgovern.mit.edu/) at MIT, where I am advised by [Prof. Tomaso Poggio](https://poggio-lab.mit.edu/people/tomaso-poggio) and [Prof. George Karnidakis](https://scholar.google.com/citations?user=yZ0-ywkAAAAJ&hl=en) in the Division of Applied Mathematics, [Brown University](https://www.brown.edu/) in Providence, RI. I also collaborate with [Dr. Dimitrios Pantazis](https://scholar.google.com/citations?user=uz8P5hYAAAAJ&hl=en) from [the MEG lab (part of the Athinoula A. Martinos Imaging Center) at MIT](http://www.pantazislab.org/) and [Prof. Quanzheng Li](https://gordon.mgh.harvard.edu/gc/people/faculty/quanzheng-li/) from [Massachusetts Gerneral Hospital, Havrard Medical School (Boston, MA, US)](https://hms.harvard.edu/affiliates/massachusetts-general-hospital) on functional neuroimaging data analysis for Alzheimer's disease early-stage prediction. I obtained my PhD degree from the Department of Computer Science, [Northeastern University](http://english.neu.edu.cn/3551/list.htm) in Shenyang, China (My advisor is Prof. Hong Zhao, Co-founder of the [Neusoft Corporation](https://www.neusoft.com/)) and spent _two years_ as _a joint PhD_ in the Division of Applied Mathematics, [Brown University](https://www.brown.edu/) in Providence, RI. During my PhD training, I spent the first two years working at [Neusoft Research Institute](https://www.neusoft.com/) on developing effective medical image analysis tools for human brain MRI imaging data analysis. 

My research interests mainly focus on the **optimization of deep neural networks**, **spatio-temporal graph representation learning**, **uncertainty quantification** and **multimodal biomedical imaging data analysis for diverse applications** (e.g., [microscopy red blood cell image segmentation and classifciation](), [diabetics retinal microaneurysm detection using AOSLO imaging](), [fMRI and MEG neuroimaging data analysis for Alzheimer's disease progression prediction and non-pharmacological cognitive training effect assessment]().)

## Recent Publications (* Co-first author)

> **2021**

- **[Understanding graph embedding methods and their applications](https://epubs.siam.org/doi/abs/10.1137/20M1386062)**

   **Mengjia Xu**

   _SIAM Review, 63(4), 825–853, 2021._ [[Paper](Papers/2021_SIREV.pdf)], [[Bibtex]()]

- **[DynG2G: An Efficient Stochastic Graph Embedding Method for Temporal Graphs](https://arxiv.org/pdf/2109.13441.pdf)**

    **Mengjia Xu**, Apoorva Vikram Singh, George Em Karniadakis 
    
    _Under review, submitted to TNNLS, 2021._ [[Paper](Papers/2021_DynG2G.pdf)], [[Bibtex]()]

- **[AOSLO-net: A deep learning-based method for automatic segmentation of retinal microaneurysms from adaptive optics scanning laser ophthalmoscope images](https://arxiv.org/pdf/2106.02800.pdf)**

   Qian Zhang*, Konstantina Sampani*, **Mengjia Xu***, Shengze Cai, Yixiang Deng, He Li, Jennifer K Sun, George Em Karniadakis
   
   _Under Review, submitted to JBHI, 2021._ [[Paper](Papers/2021_AOSLOnet.pdf)], [[Bibtex]()]

- **[Dynamics and Neural Collapse in Deep Classifiers trained with the Square Loss](https://cbmm.mit.edu/sites/default/files/publications/JMLR__2021-22.pdf)**

   Akshay Rangamani, **Mengjia Xu**, Andrzej Banburski, Qianli Liao, Tomaso Poggio

   _CBMM, memo 117, 2021._ [[Paper](Papers/2021_NC_dynamics_binary_CIFAR10.pdf)], [[Bibtex]()], [[Code](https://github.com/GraceXu182/binaryclassifiers_squareloss)]
   
- **[A Graph Gaussian Embedding Method for Predicting Alzheimer's Disease Progression With MEG Brain Networks](https://epubs.siam.org/doi/abs/10.1137/20M1386062)**

   **Mengjia Xu**, David Lopez Sanz, Pilar Garces, Fernando Maestu, Quanzheng Li, Dimitrios Pantazis
   
   _IEEE Transactions on Biomedical Engineering, 68(5), 1579-1588, 2021._ [[Paper](Papers/2021_MEG_AD_progression.pdf)], [[Bibtex]()], [[Code](https://github.com/GraceXu182/BrainNetEmb)]
  
 > **2020**
 
- **[A new Graph Gaussian embedding method for analyzing the effects of cognitive training](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1008186)**

   **Mengjia Xu**, Zhijiang Wang, Haifeng Zhang, Dimitrios Pantazis, Huali Wang, Quanzheng Li
   
   _PLoS computational biology 16 (9), e1008186, 2020._ [[Paper](Papers/2021_fMRI_AD.pdf)], [[Bibtex]()]
   
- **[Automated semantic segmentation of red blood cells for sickle cell disease](https://ieeexplore.ieee.org/abstract/document/9122550)**
     
   Mo Zhang*, Xiang Li*, **Mengjia Xu**, Quanzheng Li
   
   _IEEE Journal of Biomedical and Health Informatics 24 (11), 3095-3102, 2020._ [[Paper](Papers/2020_RBC_JBHI.pdf)], [[Bibtex]()], [[Code](https://github.com/moliqingcha/Deformable-U-Net)]
   
- **[ Multi-label detection and classification of red blood cells in microscopic images](https://ieeexplore.ieee.org/abstract/document/9122550)**
     
   Wei Qiu, Jiaming Guo, Xiang Li, **Mengjia Xu**, Mo Zhang, Ning Guo, Quanzheng Li
   
   _IEEE International Conference on Big Data (Big Data) 24 (11), 4257-4263, 2020._ [[Paper](Papers/2020_RBC_BIGDATA.pdf)], [[Bibtex]()]
   
- **[RBC semantic segmentation for sickle cell disease based on deformable U-Net](https://link.springer.com/chapter/10.1007/978-3-030-00937-3_79)**

   Mo Zhang*, Xiang Li*, **Mengjia Xu***, Quanzheng Li
   
   _International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI), 695-702, 2018._ [[Paper](Papers/2018_MICCAI_RBC.pdf)], [[Bibtex]()], [[Code]()]
    
- **[A deep convolutional neural network for classification of red blood cells in sickle cell anemia](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005746)** 

   **Mengjia Xu**, Dimitrios P Papageorgiou, Sabia Z Abidi, Ming Dao, Hong Zhao, George Em Karniadakis 
   
   _PLoS computational biology 13 (10), e1005746, 2017._ [[Paper](Papers/2017_PLOS_RBC.pdf)], [[Bibtex]()], [[News](https://phys.org/news/2017-10-machine-automatically-red-blood-cells.html)][[News](https://www.medindia.net/news/new-system-developed-to-identify-shapes-of-red-blood-cells-173976-1.htm)]

- **[An image-enhancement method based on variable-order fractional differential operators](https://content.iospress.com/articles/bio-medical-materials-and-engineering/bme1430)**

   **Mengjia Xu**, Jinzhu Yang, Dazhe Zhao, Hong Zhao
   
   _Bio-medical materials and engineering, 26 (s1), S1325-S1333, 2015._ [[Paper](Papers/2015_fractional.pdf)], [[Bibtex]()]

(Please find more of my publications from [`Google Scholar`](https://scholar.google.com/citations?user=Ok1giekAAAAJ&hl=en).)

## Presentations & Talks

> **2021**
> 
> - 2021.9.20, present “Hyperbolic cognitive knowledge graph embedding for MEG brain network analysis with multimomics dataset” in the MIT 9.58 course (Instructor:   Prof. Tomaso Poggio). 
> - 2021.9.16, attended the [“Stanford Graph Learning Workshop 2021”](https://snap.stanford.edu/graphlearning-workshop/index.html). (Virtual) 
> - 2021.4.20-21, attended the [“TOPML 2021 Workshop on the Theory of Overparameterized Machine Learning”](https://topml.rice.edu/), our work “Dynamics and Neural Collapse in Deep Classifiers with the Square Loss” being presented by Prof. Tomaso Poggio. (Virtual)
> - 2021.2.13, gave a plenary talk on “A new stochastic graph embedding method for Alzheimer’s disease early‐stage prediction and intervention evaluation” in the [IEEE EMBS Grand Challenges Forum: Data Science and Engineering in Healthcare](https://grand-challenges.embs.org/2021datascience/). (Virtual)
> - 2021.1.15, presented “nnU-Net: a self-configuring method for deep learning-based biomedical image segmentation” at the [“Machine Learning +X” Crunch Seminar](https://www.brown.edu/research/projects/crunch/machine-learning-x-seminars), invited by Prof. George Em Karniadakis at Brown University. (Virtual)  
 
> **2020**
>
> - 2020.9.9, presented “Learning graph embeddings for network analysis” in the MIT 9.58 course (Fall 2020) for the projects in Science of Intelligence. (Virtual)
> - 2020.7.31, presented “Understanding deep neural network-based Graph Embedding Methods” in MGH CAMCA group meeting (virtual), invited by Prof. Quanzheng Li from Harvard Medical School.
> - 2020.7.28, presented a poster “A New Stochastic Graph Embedding Method for Alzheimer’s Disease Early-Stage Prediction and Intervention Evaluation” in the AAIC 2020 (Virtual Conference)
> - 2020.6.12, presented “Overview of self-supervised learning” in MGH CAMCA group meeting (virtual), invited by Prof. Quanzheng Li at Harvard Medical School
> - 2020.3.30, presented the work “A deep learning-based graph embedding method for the analysis of brain networks” in CBCL group meeting, invited by Prof. Tomaso Poggio at MIT (Cambridge, MA, USA)
> - 2020.3.19, presented the work “MEG brain network Gaussian embeddings for predicting Alzheimer’s disease progression” in the online OHBMx Twitter conference (Cambridge, MA, USA)
> - 2020.1.24, presented the work “A deep learning-based graph gaussian embedding method for the analysis of brain networks” in the Computation in Mind and Brain Seminar Series of Carney Institute for Brain Science at Brown University, hosted by Prof. Stephanie Jones. (Providence, RI, USA)

> **2019**
>
> - 2019.11.18, presented the work “A novel multiple graph Gaussian embedding method to predict Alzheimer’s disease progression with MEG brain networks” in the MEG North America Workshop at NIH. (Bethesda, MD, USA)
> - 2019.06.19, presented the work “Graph Embedding Method for Network Data Analysis” at AUV lab at MIT Sea Grant hosted by Prof. Chrys Chryssostomidis. (Cambridge, MA, USA)
> - 2019.06.07, presented the work “Deep Learning-based Graph Gaussian Embedding Method” at Crunch Machine Learning Seminar, Division of Applied Mathematics, Brown University hosted by Prof. George Em Karniadakis. (Providence, RI, USA)

> **2017**
> 
> - 2017.04.14, presented the work “Multiscale Imaging Analysis” at Massachusetts General Hospital invited by Prof. Quanzheng Li. (Boston, MA, USA)
> - 2017.04.10-2017.04.12, present the work on “Automated, High-Throughput, ex-vivo Sickle Red Blood Cell Screening Assay Based on Deep Convolutional Neural Networks” in the 8th International Conference on Computational and Mathematical Biomedical Engineering (CMBE2017). (Pittsburgh, PA, USA)


## Student Mentoring

* (2021.09 ~ present): Master student ([Cole S Baker](https://www.linkedin.com/in/cole-baker-724573130/), Master of EECS, MIT) on the project – _“Hyperbolic Knowledge Graph Embedding with Multiomics data for Alzheimer’s Disease Progression Prediction”_ (Collaborated with [Dr. Dimitrios Pantazis](https://scholar.google.com/citations?user=uz8P5hYAAAAJ&hl=en) at MIT and [Prof. Fernando Maestú](http://meg.ctb.upm.es/members/director/maestu/) at Department of Experimental Psychology, Complutense University of Madrid)

* (Fall 2021):  Mentoring two senior undergraduate students ([Habeeb Salau](https://www.linkedin.com/in/habeeb-salau/) & [Faduma Khalif]()) from EECS and BCS at MIT on the project - _“Hyperbolic Graph Embedding for MEG Brain Network Analysis”_ in the [**MIT 9.58 course**](https://cbmm.mit.edu/9-58/2020/projects). (Course instructor: Prof. Tomaso Poggio). 

* (Fall 2020):  Mentoring two senior undergraduate students ([Jasmine F Zou](https://www.linkedin.com/in/jasmine-zou-058913158/) & [Mona M Abdelrahman](https://bcs.mit.edu/directory/mona-abdelrahman)) from EECS and BCS at MIT on the project - _“Learning Stochastic Graph Embeddings for Graph Analysis”_ in the [**MIT 9.58 course**](https://cbmm.mit.edu/9-58/2020/projects). (Course instructor: Prof. Tomaso Poggio). 

* (2020.03 ~ present) : Mentoring one first year PhD student ([Qian Zhang](https://appliedmath.brown.edu/people/qian-zhang), Division of Applied Mathematics at Brown University) on the project - _"AOSLO-net: A deep learning-based method for automatic segmentation of retinal microaneurysms from adaptive optics scanning laser ophthalmoscope images”_ (Duration: 2020.01~2021.06, Paper submitted to JBHI) 

* (2020.12~present):  Mentoring one senior undergraduate intern ([Apoorva Vikram Singh](https://apoorvavsingh.github.io/), National Institute of Technology, Silchar) on the project - _“DynG2G: An Efficient Stochastic Graph Embedding Method for Temporal Graphs”_ (paper submitted to TNNLS 2021) and another ongoing work – _“Dynamic Hyperbolic Graph Embedding (DynHypG2G)”_.

* (2014.12~2016.06): mentoring one high school student intern (_Jacob Aranda_) from the [MET high school](http://www.themethighschool.org/) (Providence, RI, USA) on the project - _“Microscopic red blood cell image preprocessing and segmentation”_ with Python programming.

## Professional Services

Reviewers of the Medical Image Analysis, SIAM Journal on Mathematics of Data Science, PLoS One, Computers in Biology and Medicine, Journal of Computational Physics, etc.


## Contact

Address: [43 Vassar St, Cambridge, MA 02139, USA](https://www.google.com/maps/place/Brain+and+Cognitive+Sciences+Complex,+43+Vassar+St,+Cambridge,+MA+02139/@42.3623024,-71.0939546,17z/data=!3m1!4b1!4m5!3m4!1s0x89e370abfd23371f:0x6de0e79d1bce9bf7!8m2!3d42.3623024!4d-71.0917659)

Email: mengjia@mit.edu

