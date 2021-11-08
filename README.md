<!-- ## Welcome to Mengjia Xu's Pages -->
<!--     [Main architecture](https://github.com/GraceXu182/gracexu182.github.io/blob/main/images/DynG2G_workflow.png#50*20) -->   
<!-- > Dynamic graph embedding has gained great attention recently due to its capability of learning low-dimensional and meaningful graph representations for complex temporal graphs with high accuracy. However, recent advances mostly focus on learning node embeddings as *deterministic "vectors"* for *static* graphs, hence disregarding the key graph temporal dynamics and the evolving uncertainties associated with node embedding in the latent space. In this work, we propose an efficient stochastic dynamic graph embedding method (DynG2G) that applies an inductive feed-forward encoder trained with node triplet energy-based ranking loss. Every node per timestamp is encoded as a time-dependent *probabilistic multivariate Gaussian distribution* in the latent space, hence we are able to quantify the node embedding uncertainty on-the-fly. We have considered eight different benchmarks that represent diversity in size (from 96 nodes to 87,626 and from 13,398 edges to 4,870,863) as well as diversity in dynamics, from slowly changing temporal evolution to rapidly varying multi-rate dynamics. We demonstrate through extensive experiments based on these eight dynamic graph benchmarks that DynG2G achieves new state-of-the-art performance in capturing the underlying temporal node embeddings. We also demonstrate that DynG2G can simultaneously predict the evolving node embedding uncertainty, which plays a crucial role in quantifying the *intrinsic dimensionality* of the dynamical system over time. In particular, we obtain a "universal" relation of the optimal embedding dimension, ![$L_o$](https://latex.codecogs.com/svg.image?L_o), versus the effective dimensionality of uncertainty, ![$D_u$](https://latex.codecogs.com/svg.image?D_u), and we infer that ![$L_o=D_u$](https://latex.codecogs.com/svg.image?L_o%20=%20D_u) for all cases; see Table III. This, in turn, implies that the uncertainty quantification approach we employ in the DynG2G algorithm correctly captures the intrinsic dimensionality of the dynamics of such evolving graphs despite the diverse nature and composition of the graphs at each timestamp. In addition, this ![$L_o - D_u$](https://latex.codecogs.com/svg.image?L_o&space;-&space;D_u) correlation provides a clear path to selecting adaptively the optimum embedding size at each timestamp by setting ![$L \ge D_u$](https://latex.codecogs.com/svg.image?L&space;\ge&space;D_u) -->

<!--  above not used!!!-->

I am a Postdoctoral Associate at the [Center for Brains, Minds and Machines](https://cbmm.mit.edu/), [McGovern Insitute for Brain Research](https://mcgovern.mit.edu/) at MIT, where I am advised by [Prof. Tomaso Poggio](https://poggio-lab.mit.edu/people/tomaso-poggio) and [Prof. George Karnidakis](https://scholar.google.com/citations?user=yZ0-ywkAAAAJ&hl=en) in the Division of Applied Mathematics, Brown University. I also collaborate with Dr. Dimitrios Pantazis from the MEG lab at MIT and Prof. Quanzheng Li from MGH, Havrard Medical School on functional neuroimaging data analysis for Alzheimer's disease early-stage prediction. I obtained my PhD degree from the Department of Computer Science, Northeastern University in Shenyang, China and spent two years as a joint PhD student in the Division of Applied Mathematics, Brown University in Providence, RI. During my PhD training, I spent the first two years working at Neusoft Research Institute on developing effective medical image analysis tools for human brain MRI imaging data analysis.

My research interests mainly focus on the **optimization of deep neural networks**, **spatio-temporal graph representation learning**, **uncertainty quantification** and **multimodal biomedical imaging data analysis for diverse applications** (e.g., [microscopy red blood cell image segmentation and classifciation](), [diabetics retinal microaneurysm detection using AOSLO imaging](), [fMRI and MEG neuroimaging data analysis for Alzheimer's disease progression prediction and non-pharmacological cognitive training effect assessment]().)

### Recent Publications (* Co-first author)

- **[DynG2G: An Efficient Stochastic Graph Embedding Method for Temporal Graphs](https://arxiv.org/pdf/2109.13441.pdf)**

    **Mengjia Xu**, Apoorva Vikram Singh, George Em Karniadakis
    
    _Under review, submitted to TNNLS, 2021_

- **[AOSLO-net: A deep learning-based method for automatic segmentation of retinal microaneurysms from adaptive optics scanning laser ophthalmoscope images](https://arxiv.org/pdf/2106.02800.pdf)**

   Qian Zhang*, Konstantina Sampani*, **Mengjia Xu***, Shengze Cai, Yixiang Deng, He Li, Jennifer K Sun, George Em Karniadakis
   
   _Under Review, submitted to JBHI, 2021_

- **[Dynamics and Neural Collapse in Deep Classifiers trained with the Square Loss](https://cbmm.mit.edu/sites/default/files/publications/JMLR__2021-22.pdf)[[Code](https://github.com/GraceXu182/binaryclassifiers_squareloss)]**

   Akshay Rangamani, **Mengjia Xu**, Andrzej Banburski, Qianli Liao, Tomaso Poggio

   _CBMM, memo 117, 2021_

- **[Understanding graph embedding methods and their applications](https://epubs.siam.org/doi/abs/10.1137/20M1386062)**

   **Mengjia Xu**

   _SIAM Review, 63(4), 825–853, 2021._
   
- **[A Graph Gaussian Embedding Method for Predicting Alzheimer's Disease Progression With MEG Brain Networks](https://epubs.siam.org/doi/abs/10.1137/20M1386062)**

   **Mengjia Xu**, David Lopez Sanz, Pilar Garces, Fernando Maestu, Quanzheng Li, Dimitrios Pantazis
   
   _IEEE Transactions on Biomedical Engineering, 68(5), 1579-1588, 2021._
   
- **[A new Graph Gaussian embedding method for analyzing the effects of cognitive training](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1008186)**

   **Mengjia Xu**, Zhijiang Wang, Haifeng Zhang, Dimitrios Pantazis, Huali Wang, Quanzheng Li
   
   _PLoS computational biology 16 (9), e1008186, 2020._
   
- **[Automated semantic segmentation of red blood cells for sickle cell disease](https://ieeexplore.ieee.org/abstract/document/9122550)**
     
   Mo Zhang*, Xiang Li*, **Mengjia Xu**, Quanzheng Li
   
   _IEEE Journal of Biomedical and Health Informatics 24 (11), 3095-3102, 2020_
   
- **[RBC semantic segmentation for sickle cell disease based on deformable U-Net](https://link.springer.com/chapter/10.1007/978-3-030-00937-3_79)**

   Mo Zhang*, Xiang Li*, **Mengjia Xu***, Quanzheng Li
   
   _International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI), 695-702, 2018_
    
- **[A deep convolutional neural network for classification of red blood cells in sickle cell anemia](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005746)**

   **Mengjia Xu**, Dimitrios P Papageorgiou, Sabia Z Abidi, Ming Dao, Hong Zhao, George Em Karniadakis
   
   _PLoS computational biology 13 (10), e1005746, 2017_

- **[An image-enhancement method based on variable-order fractional differential operators](https://content.iospress.com/articles/bio-medical-materials-and-engineering/bme1430)**

   **Mengjia Xu**, Jinzhu Yang, Dazhe Zhao, Hong Zhao
   
   _Bio-medical materials and engineering, 26 (s1), S1325-S1333, 2015_

For more publications see [My Google Scholar](https://scholar.google.com/citations?user=Ok1giekAAAAJ&hl=en).

### Services

Reviewers for the Medical Image Analysis, SIAM Journal on Mathematics of Data Science, PLoS One, Computers in Biology and Medicine, Journal of Computational Physics, etc.

### Mentoring Jobs

* (2021.09 ~ present): Master student ([Cole S Baker](https://www.linkedin.com/in/cole-baker-724573130/), Master of EECS, MIT) on the project – “Hyperbolic Knowledge Graph Embedding with Multiomics data for Alzheimer’s Disease Progression Prediction” (Collaborated with [Dr. Dimitrios Pantazis](https://scholar.google.com/citations?user=uz8P5hYAAAAJ&hl=en) at MIT and [Prof. Fernando Maestú](http://meg.ctb.upm.es/members/director/maestu/) at Department of Experimental Psychology, Complutense University of Madrid)

* (Fall 2021):  Mentoring two senior undergraduate students ([Habeeb Salau](https://www.linkedin.com/in/habeeb-salau/) & [Faduma Khalif]()) from EECS and BCS at MIT on the project - “Hyperbolic Graph Embedding for MEG Brain Network Analysis” in the MIT 9.58 course. (Course instructor: Prof. Tomaso Poggio). 



### Contact

mengjia@mit.edu

