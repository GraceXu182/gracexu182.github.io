<!-- ## Welcome to Mengjia Xu's Pages -->

<!-- <div style="text-align: justify">  -->
I am a Postdoctoral Associate at the [Center for Brains, Minds and Machines](https://cbmm.mit.edu/), [McGovern Insitute for Brain Research](https://mcgovern.mit.edu/) at MIT, I am supervised by [Prof. Tomaso Poggio](https://poggio-lab.mit.edu/people/tomaso-poggio) and [Prof. George Karnidakis](https://scholar.google.com/citations?user=yZ0-ywkAAAAJ&hl=en) in the Division of Applied Mathematics, Brown University. I obtained my PhD degree from the Department of Computer Science, Northeastern University at Shenyang, China and spent two years as a visiting PhD in the Division of Applied Mathematics, Brown University in Providence, RI. My research interests mainly focus on the **optimization of deep neural networks**, **spatio-temporal graph representation learning**, **uncertainty quantification** and **multimodal biomedical imaging data analysis for diverse applications** (e.g., [microscopy red blood cell image segmentation and classifciation](), [diabetics retinal microaneurysm detection using AOSLO imaging](), [fMRI and MEG neuroimaging data analysis for Alzheimer's disease progression prediction and non-pharmacological cognitive training effect assessment]().)
<!-- </div> -->
### Recent Projects
1. DynG2G: An Efficient Stochastic Graph Embedding Method for Temporal Graphs
- Abstract: Dynamic graph embedding has gained great attention recently due to its capability of learning low-dimensional and meaningful graph representations for complex temporal graphs with high accuracy. However, recent advances mostly focus on learning node embeddings as *deterministic ``vectors''* for **static** graphs, hence disregarding the key graph temporal dynamics and the evolving uncertainties associated with node embedding in the latent space. In this work, we propose an efficient stochastic dynamic graph embedding method (DynG2G) that applies an inductive feed-forward encoder trained with node triplet energy-based ranking loss. Every node per timestamp is encoded as a time-dependent _probabilistic multivariate Gaussian distribution_ in the latent space, hence
we are able to quantify the node embedding uncertainty on-the-fly. We have considered eight different benchmarks that represent diversity in size (from 96 nodes to 87,626 and from 13,398 edges to 4,870,863) as well as diversity in dynamics, from slowly changing temporal evolution to rapidly varying multi-rate dynamics. 
We demonstrate through extensive experiments based on these eight dynamic graph benchmarks that DynG2G achieves new state-of-the-art performance in capturing the underlying temporal node embeddings. We also demonstrate that DynG2G can simultaneously predict the evolving node embedding uncertainty, which plays a crucial role in quantifying the **intrinsic dimensionality** of the dynamical system over time. In particular, we obtain a ``universal" relation of the optimal embedding dimension, $L_o$, versus the effective dimensionality of uncertainty, $D_u$, and we infer that $L_o=D_u$ for all cases; see Table III. This, in turn, implies that the uncertainty quantification approach we employ in the DynG2G algorithm correctly captures the **intrinsic dimensionality** of the dynamics of such evolving graphs despite the diverse nature and composition of the graphs at each timestamp. In addition, this $L_o - D_u$ correlation provides a clear path to selecting adaptively the optimum embedding size at each timestamp by setting $L \ge D_u$.
<!-- ![image]() -->

3. AOSLO-net: A deep learning-based method for automatic segmentation of retinal microaneurysms from adaptive optics scanning laser ophthalmoscope images

5. Dynamics and Neural Collapse in Deep Classifiers trained with the Square Loss


**Bold** and _Italic_ and `Code` text


For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Publications

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/GraceXu182/gracexu182.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
