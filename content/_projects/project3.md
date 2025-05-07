---
title: Hyperbolic Graph Embedding of MEG Brain Networks to Study Brain Alterations in Individuals With Subjective Cognitive Decline
subtitle: (Cole Baker, Isabel Suárez-Méndez , Grace Smith, Elisabeth B. Marsh, Michael Funke, John C. Mosher, Fernando Maestu, Mengjia Xu*, and Dimitrios Pantazis*)
description: This study develops a hyperbolic MEG brain network embedding framework to analyze early Alzheimer’s disease (SCD stage) by mapping brain networks into low-dimensional hyperbolic space. The model reveals hierarchical differences in key subnetworks and their correlation with cognitive decline, offering new insights for early diagnosis.
order: 3
active: false
card_image: "/assets/images/SCD_project.jpg"
# card_image: "assets/images/SCD_project.jpg"
card_title:  # used if card_image is null; defaults to title
categories: 
    - Alzheimer’s disease
    - MEG Brain Networks
    - Hyperbolic Geometry
---

<div style="width: 100%; padding: 10px; ; background-color: #f8f8f8;">
    <div style="display: flex; justify-content: space-between;">
        <a href="../project2">&lt;&lt;Previous Project</a>
        <a href="../project3">Next Project&gt;&gt;</a>
    </div>
</div>

### Overview

<p align="justify">
An expansive area of research focuses on discerning patterns of alterations in functional brain networks from the early stages of Alzheimer’s disease, even at the subjective cognitive decline (SCD) stage. Here, we developed a novel hyperbolic MEG brain network embedding framework for transforming high-dimensional complex MEG brain networks into lower-dimensional hyperbolic representations. Using this model, we computed hyperbolic embeddings of the MEG brain networks of two distinct participant groups: individuals with SCD and healthy controls. We demonstrated that these embeddings preserve both local and global geometric information, presenting reduced distortion compared to rival models, even when brain networks are mapped into low-dimensional spaces. In addition, our findings showed that the hyperbolic embeddings encompass unique SCD-related information that improves the discriminatory power above and beyond that of connectivity features alone. Notably, we introduced a unique metric–the radius of the node embeddings–which effectively proxies the hierarchical organization of the brain. Using this metric, we identified subtle hierarchy organizational differences between the two participant groups, suggesting increased hierarchy in the dorsal attention, frontoparietal, and ventral attention subnetworks among the SCD group. Last, we assessed the correlation between these hierarchical variations and cognitive assessment scores, revealing associations with diminished performance across multiple cognitive evaluations in the SCD group. Overall, this study presents the first evaluation of hyperbolic embeddings of MEG brain networks, offering novel insights into brain organization, cognitive decline, and potential diagnostic avenues of Alzheimer’s disease.
</p>
**Keywords:** Alzheimer’s disease, subjective cognitive decline, magnetoencephalography, brain networks, hyperbolic space, graph embedding

<p align="center">
    <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10564006">Paper link</a> | 
    <a href="https://github.com/ColeSBaker/hyperBrain">GitHub link</a>|
    <a href="#citation">Citation</a> 
</p>

### **Methodology**
<p align = 'justify'>
Main workflow of our proposed hyperbolic embedding framework for MEG brain networks is shown in the figure below. It contains four main components: (a) MEG functional connectivity matrix calculated based on phase locking values across all 90 regions of the AAL brain atlas. (b) Illustrative visualization of the binary MEG brain network on the cortex, after applying a threshold of 0.329 to the phase locking values. Node attributes incorporate one-hot identity vectors. (c) A two-layer hyperbolic graph convolutional network (HGCN) model performs feature transformation and neighborhood aggregation, followed by the SELU activation function. (d) Example hyperbolic embeddings of brain regions in the 2-dimensional space. Subnetwork and hemisphere are indicated by color and shape, respectively.
</p>
<img src="{{ '/assets/images/projects/SCD_method.png' | relative_url }}" alt="main framework for SCD prediction">

### **Results**

<p align = 'justify'>
The hyperbolic embedding model for MEG brain networks was initally evaluated by performing link prediction task with different embedding sizes (D), see results in Table II. According to the obtained MEG brain network embeddings, subjective cognitive decline (SCD) classification results are illustrated in Fig. 5. Additionally, Figures 6 and 7 depict the hierarchical changes of 8 subnetworks between normal controls and individuals with subjective cognitive decline, based on the cluster radius metric derived from the corresponding hyperbolic MEG brain network embeddings.
</p>

<img src="{{ '/assets/images/projects/SCD_results_all.png' | relative_url }}" alt="main framework for SCD prediction">


#### Aknowlegement

> <p align="justify"> This work was supported by a Jameel Clinic at MIT grant award (to DP); the National Institute on Aging of the National Institutes of Health under award numbers RF1AG074204 (to MF, JCM, MF, FM, and DP) and RF1AG079324 (to EBM, MF, JCM, MF, FM, and DP); and was partially supported by the DOE SEA-CROGS project (DE-SC0023191) to MX. 

#### Citation

```bibtex
@article{baker2024hyperbolic,
  title={Hyperbolic graph embedding of MEG brain networks to study brain alterations in individuals with subjective cognitive decline},
  author={Baker, Cole and Su{\'a}rez-M{\'e}ndez, Isabel and Smith, Grace and Marsh, Elisabeth B and Funke, Michael and Mosher, John C and Maest{\'u}, Fernando and Xu, Mengjia and Pantazis, Dimitrios},
  journal={IEEE Journal of Biomedical and Health Informatics},
  year={2024},
  publisher={IEEE}
}
```


<!-- This is an example of a PubMed citation {% include citation.html search="njit" %}. -->

<!-- {% include figure.html  
    image="assets/images/chemical-reaction-science-chemistry.jpg"
    title="This is the 'title' provided to figure.html."
    caption="This is the text in the 'caption' provided to figure.html."
%} -->
