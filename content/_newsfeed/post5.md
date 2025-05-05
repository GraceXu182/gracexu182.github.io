---
date: 2023-12-22
title: New Paper on "Temporal graph embedding with transformers"
subtitle: TransformerG2G - Adaptive Time-Stepping for Learning Temporal Graph Embeddings Using Transformers
description: Paper titled "TransformerG2G - Adaptive Time-Stepping for Learning Temporal Graph Embeddings Using Transformers" has been accepted by Neural Networks.
event_type: publication # primary type of the event, used to create the small, colored post callout
banner_image: assets/images/seminar_banner2.jpg # the item whose banner image will be adopted by this event
badges: # e.g. person=John_Doe, project=project1 (no spaces)
  # - publication=Hyperbolic_brainaging_2024
  # - project=project2
#   - person=Cole_Baker
  # - project=brain_aging_study
---
<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

<a href="../#latest-news"><b>&lt;&lt;All News</b></a>

We are excited to share our latest accepted paper, a collaboration with esteemed colleagues from <b>Brown University</b>.

**Title:** **<span style="color: darkred">TransformerG2G - Adaptive Time-Stepping for Learning Temporal Graph Embeddings Using Transformers</span>**  
**Authors:** **<span style="color: darkred">Alan John Varghese, Aniruddha Bora, Mengjia Xu\*, George Em Karniadakis</span>**  
**Links:**  [Download paper](https://www.sciencedirect.com/science/article/abs/pii/S0893608023007475)| [GitHub Code](https://github.com/alanjohnvarghese/TransformerG2G) | <a href="#" id="bibtex" onclick="navigator.clipboard.writeText('@article{varghese2024transformerg2g,\n  title={TransformerG2G: Adaptive time-stepping for learning temporal graph embeddings using transformers},\n  author={Varghese, Alan John and Bora, Aniruddha and Xu, Mengjia and Karniadakis, George Em},\n  journal={Neural Networks},\n  volume={172},\n  pages={106086},\n  year={2024},\n  publisher={Elsevier}}'); alert('BibTex copied to clipboard!');">BibTex</a>

---

#### Overview
<p align="justify">
Dynamic graph embedding has become a powerful approach for tackling various temporal graph analytics tasks, such as link prediction, node classification, recommender systems, anomaly detection, and graph generation. These tasks require addressing challenges like transient dynamics, varying time intervals, and evolving node features. In this paper, we propose TransformerG2G, a novel graph embedding model with uncertainty quantification. By leveraging a transformer encoder, TransformerG2G captures long-range dependencies from historical graph contexts and generates multivariate Gaussian embeddings for nodes. Experiments on diverse benchmarks demonstrate that TransformerG2G outperforms traditional methods and our prior work (<a href ="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9793727">DynG2G</a>) in link prediction accuracy and computational efficiency, particularly for graphs with high novelty (i.e., transient dynamics). Additionally, the model's attention weights provide interpretability, revealing temporal dependencies, adaptive time-stepping behavior, and key insights into graph evolution, such as the correlation between attention weights and node degree. These contributions enhance both the performance and explainability of dynamic graph embedding.
</p>

<div style="display: flex; margin-top:40px; margin-top:20px;justify-content: center; gap: 20px;">
  <div style="width: 35%; text-align: center; transition: transform 0.3s ease-in-out;" onmouseover="this.style.transform='scale(1.06)';" onmouseout="this.style.transform='scale(1)';">
    <img src="../../assets/images/projects/TEA.jpg" alt="tea plot" style="width: 100%; height: auto; font-size: 0.9em;">
    <p align="justify" style="font-size: 0.8em;">Fig. 1: Six different discrete-time temporal graph benchmarks along with their corresponding Temporal Edge Appearance (TEA) plots for effective characterization of evolutionary dynamics. (a)–(f) correspond to <b>SBM, Reality Mining, UCI, Bitcoin, Slashdot, and Autonomous Systems</b>, respectively. For each benchmark, the top row displays four distinct graph snapshots with the timestamp numbers, and the bottom row shows the TEA plot including the number of newly added edges (red bars) and the number of repeated edges (blue bars) over time. The index values corresponding to (a)–(f) are 0.0252, 0.0761, 0.7526, 0.9161, 0.9861, and 0.014, respectively.</p>
  </div>
  <div style="width: 35%; text-align: center; transition: transform 0.3s ease-in-out;" onmouseover="this.style.transform='scale(1.06)';" onmouseout="this.style.transform='scale(1)';">
    <img src="../../assets/images/projects/transformerG2G.jpg" alt="TransformerG2G" style="width: 100%; height: auto;">
    <p align="justify" style="font-size: 0.8em;">Fig. 2: Illustration of our proposed TransformerG2G model architecture. The attention mechanism of the transformer enables the model to capture long-term context in the dynamics of the graph. The model’s input is the history of a node over several steps, from timestamps \(t_1\) to \(t_n\) and outputs the embedding vectors at timestamp \(t_n\) of that particular node. Here, the lookback \(l\) is a hyperparameter and different values of \(l\) are considered in our experiments.
    </p>
  </div>
  <div style="width: 35%; text-align: center; transition: transform 0.3s ease-in-out;" onmouseover="this.style.transform='scale(1.06)';" onmouseout="this.style.transform='scale(1)';">
    <img src="../../assets/images/projects/MAP_lp.jpg" alt="lp_map" style="width: 100%; height: auto;">
    <p align="justify" style="font-size: 0.8em;">Fig. 3: MAP values for temporal link prediction based on node embeddings learned with our proposed TransformerG2G model across six dynamic graph datasets, where higher MAP values indicate better link prediction performance. The datasets corresponding to (a)–(f) are SBM, Reality Mining, UCI, Bitcoin, Slashdot, and Autonomous Systems, respectively. The blue bars display the MAP values achieved by DynG2G, while the yellow bars present the MAP values obtained by our TransformerG2G model with different lookbacks \(l = 1,2,3,4,5\).
    </p>
  </div>
</div>

<div style="display: flex;  justify-content: center;">
  <div style="width: 50%; text-align: center; transition: transform 0.3s ease-in-out;" onmouseover="this.style.transform='scale(1.06)';" onmouseout="this.style.transform='scale(1)';">
    <img src="../../assets/images/projects/weights_attention.jpg" alt="new image" style="width: 100%; height: auto; object-fit: cover; object-position: top; height: 55%;">
  </div>
  <div style="width: 50%; text-align: center; transition: transform 0.3s ease-in-out;" onmouseover="this.style.transform='scale(1.06)';" onmouseout="this.style.transform='scale(1)';">
    <img src="../../assets/images/projects/weights_attention.jpg" alt="new image" style="width: 100%; height: auto; object-fit: cover; object-position: bottom; height: 45%;">
  </div>
</div>
<p align="justify" style="font-size: 0.8em; ">Fig. 4: The attention matrix of TransformerG2G for a randomly selected node (ID No. 6) in Reality Mining is visualized at different time stamps in (a). The attention matrix shows the importance given to the current state and previous context while generating the graph embeddings. (b) shows the node degree of the current state and previous context. Interestingly, we see that the learned model assigns more significance to time stamps where the node has a higher degree, indicating that the model recognized the importance of nodes with greater connectivity.</p>


<div style="width: 100%; padding: 10px; border: 1px solid #ccc; background-color: #f8f8f8;">
  <div style="display: flex; justify-content: space-between;">
    <a href="../post4/">&lt;&lt;Previous News</a>
    <a href="../post6/">Next News&gt;&gt;</a>
  </div>
</div>