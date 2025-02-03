---
title:  Fully Hyperbolic Neural Networks - A Novel Approach to Studying Aging Trajectories
subtitle: (Hugo Ramirez, Davide Tabarelli, Arianna Brancaccio, Paolo Belardinelli, Elisabeth B. Marsh, Michael Funke, John C. Mosher, Fernando Maestu, Mengjia Xu*, and Dimitrios Pantazis*)
description: This study uses a Fully Hyperbolic Neural Network (FHNN) to embed MEG brain networks, uncovering age-related hierarchical changes and highlighting the superiority of hyperbolic features in aging analysis.
order: 2
active: true
card_image: "/assets/images/brainimage.jpg"
card_title: null # used if card_image is null; defaults to title
categories: 
    - MEG Neuroimaging
    - Graph Neural Networks
    - Hyperbolic Geometry
    - Human Brain Aging
---

<!-- This is complete description of my third project. -->

<div style="width: 100%; padding: 10px; ; background-color: #f8f8f8;">
    <div style="display: flex; justify-content: space-between;">
        <a href="../project1">&lt;&lt;Previous Project</a>
        <a href="../project3">Next Project&gt;&gt;</a>
    </div>
</div>

### Overview
<p align = 'justify'>
Characterizing age-related alterations in brain networks is crucial for understanding aging trajectories and identifying deviations indicative of neurodegenerative disorders, such as Alzheimer’s disease. In this study, we developed a Fully Hyperbolic Neural Network (FHNN) to embed functional brain connectivity graphs derived from magnetoencephalography (MEG) data into low dimensions on a Lorentz model of hyperbolic space. Using this model, we computed hyperbolic embeddings of the MEG brain networks of 587 individuals from the Cambridge Centre for Ageing and Neuroscience (Cam-CAN) dataset. Notably, we leveraged a unique metric—the radius of the node embeddings—which effectively captures the hierarchical organization of the brain, to characterize subtle hierarchical organizational changes in various brain subnetworks attributed to the aging process. Our findings revealed that a considerable number of subnetworks exhibited a reduction in hierarchy during aging, with some showing gradual changes and others undergoing rapid transformations in the elderly. Moreover, we demonstrated that hyperbolic features outperform traditional graph-theoretic measures in capturing age-related information in brain networks. Overall, our study represents the first evaluation of hyperbolic embeddings in MEG brain networks for studying aging trajectories, shedding light on critical regions undergoing significant age-related alterations in the large cohort of the Cam-CAN dataset.
</p>

**Keywords:** Aging trajectories, Alzheimer’s disease, age prediction, magnetoencephalography, brain networks, hyperbolic space, graph embedding.

<p align="center">
    <a href="https://www.biorxiv.org/content/10.1101/2024.10.01.616153v1.full.pdf">Paper link</a> | 
    <a href="https://github.com/Hramir/age_prediction">GitHub link</a>|
    <a href="#citation">Citation</a> 
</p>

### **Methodology**

<p align = 'justify'>
The FHNNs contain three main components: feature transformation, neighborhood aggregation, and non-linear activation. The feature transformation corresponds to a Lorentz linear layer, while the closed-form centroid of neighboring node features defined before is used for neighborhood aggregation. Non-linearity is integrated into the Lorentz linear layer without the need for an explicit non-linear activation function. 
</p>

<img src="{{ '/assets/images/projects/brain_aging_FHNN.png' | relative_url }}" alt="FHNN Model for Age Prediction">

### **Results**

#### A. Alterations of brain network hierarchy across age

<p align="justify">
We estimated the average hyperbolic radius for brain regions within 22 brain subnetworks across participants of the same decade (Table I, Fig. 4). The results show a consistent increase in hyperbolic radius over time, indicating a diminishing hierarchical significance. Some subnetworks exhibit more rapid changes than others.
</p>
<img src="{{ '/assets/images/projects/slope_radius_subnets.png' | relative_url }}" alt="slope_radius_subnets">

<div style="display: flex; justify-content: space-between;">
    <img src="{{ '/assets/images/projects/hyperbolic_slope_brain_visualization.png' | relative_url }}" alt="Age Prediction" style="width: 48%; height: 70%">
    <img src="{{ '/assets/images/projects/subnet_comparison.png' | relative_url }}" alt="Age Prediction" style="width: 48%;">
</div>


#### B. Age prediction with hyperbolic radius

<p align="justify">
We utilized the hyperbolic radius of node embeddings as a new feature for predicting the age of individuals. Our model outperformed traditional graph-theoretic measures, showcasing the potential of hyperbolic features in capturing age-related information. The table below depicts the mean average error (MAE) of age predictions using hyperbolic radius compared to other methods.
</p>

 <img src="{{ '/assets/images/projects/age_prediction.png' | relative_url }}" alt="Age Prediction">

#### Aknowlegement

> <p align="justify">This work was supported by a Jameel Clinic at MIT grant award (to DP); the National Institute on Aging of the National Institutes of Health under award numbers RF1AG074204 (to MF, JCM, MF, FM, and DP) and RF1AG079324 (to EBM, MF, JCM, MF, FM, and DP); and was partially supported by the DOE SEA-CROGS project (DE-SC0023191) to MX. 

#### Citation

```bibtex
@article{ramirez2024fully,
    title={Fully Hyperbolic Neural Networks: A Novel Approach to Studying Aging Trajectories},
    author={Ramirez, Hugo and Tabarelli, Davide and Brancaccio, Arianna and Belardinelli, Paolo and Marsh, Elisabeth B and Funke, Michael and Mosher, John and Maestu, Fernando and Xu, Mengjia and Pantazis, Dimitrios},
    journal={bioRxiv},
    pages={2024--10},
    year={2024},
    publisher={Cold Spring Harbor Laboratory}
}
```


