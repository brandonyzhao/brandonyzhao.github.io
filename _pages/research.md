---
layout: archive
permalink: /research/
title: "Research"
author_profile: true
---

## Content-Based Classification of Mars Exploration Rover Pancam Images
***

<div class='img' style='float: right; width: 15%;'>
  <img class='img_responsive' src='/images/rover.jpg' />
</div>

<div class='text' style='width: 80%;'>
  NASA has acquired more than 4.3 million detailed panoramic images of Mars' surface through the Pancam
  instrument mounted on the Spirit and Opportunity rovers. These images were previously labeled only with metadata parameters such as image wavelength, position code and date, and lacked content-based labels, such as
  which geological features or rover parts specific images may contain. Thus, to enable scientists and engineers to quickly find images of interest, a convolutional neural network-based classification algorithm was developed to create these labels and support an online searchable catalog of Pancam products via features of interest. <br>
  This project was done under the mentorship of Steven Lu and Kiri Wagstaff at JPL, in collaboration with Shoshanna Cole and Kevin Grimes.
  <ul>
    <li>
      Automatically generated Pancam labels are now available via the <a href='https://pds-imaging.jpl.nasa.gov/search/?fq=-ATLAS_THUMBNAIL_URL%3Abrwsnotavail.jpg&q=*%3A*'>PDS Image Atlas</a> (On the left toolbar, filter by 'MER Image Content'). 
    </li>
    <li>
     In addition, this work was published as a <a href='https://lpsc2021.ipostersessions.com/Default.aspx?s=38-65-0C-51-56-E4-60-59-97-07-F8-A4-F9-0B-53-D4'>poster</a> in LPSC 2021, as well as mentioned in <a href='https://ojs.aaai.org/index.php/AAAI/article/view/17784'>this paper</a> about recent NASA deployments and advances in Mars Image Content Classification. 
    </li>
    <li>
      To train the network, we created a labelled Mars Pancam image dataset available <a href='https://zenodo.org/record/4302760'>here</a>.
    </li>
  </ul>
 
</div>

## Improving Prototype-based Neural Networks for Interpretable Fine-grained Image Classification
***

<div class='img' style='float: right; width: 15%;'>
  <img class='img_responsive' src='/images/birds.png' />
</div>

<div class='text' style='width: 80%;'>
  When evaluating the interpretability of an image classification network, it is important
  to consider not only the model’s capability to explain its reasoning process, but also the
  quality of its explanations. Existing prototypical image classification models have an interpretable
  reasoning process which uses similarity to prototypical image patches to explain a given
  decision, but may suffer from decisions based on prototypes with spurious connections to
  actual semantic concepts. 

  I am investigating ways to modify the architecture and training processes of these networks to better represent rich underlying relationships between prototypical parts and fine-grained image classes 
  through a learned class assignment.

  This project is being done in collaboration with Prof. Cynthia Rudin and the Prediction Analysis lab at Duke. 
</div>

## Epidemics on Random Graphs
***

<div class='img'>
  <img class='img_responsive' style='float: right;' src='/images/EpidemicTree.png' />
</div>

Studied asymptotics of the contact process on random periodic trees. In particular, I helped to derive bounds for critical values of phase transitions for the contact process on \\((1,n)\\) trees as well as \\((a,b,c)\\) trees. This work was the result of a group project advised by Professors Rick Durrett and Matthew Junge at Duke as part of the DoMath program. 

[Download paper here](https://arxiv.org/pdf/1808.01863.pdf)

Jiang, Y., Kassem, R., York, G., Zhao, B., Huang, X., Junge, M., & Durrett, R. (2018) "The contact process on periodic trees." <i>arXiv preprint arXiv:1808.01863.</i>