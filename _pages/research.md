---
layout: archive
permalink: /research/
title: "Research"
author_profile: true
---

## Single View Refractive Index Tomography with Neural Fields
***

<div class='img' style='width: 80%;'>
  <img class='img_responsive' src='/images/teaser.png' />
</div>

<div class='text' style='width: 80%;'>
  Refractive Index Tomography is an inverse problem in which we seek to reconstruct a scene's 3D refractive field from 2D projected image measurements. The refractive field is not visible itself, but instead affects how the path of a light ray is continuously curved as it travels through space. Refractive fields appear across a wide variety of scientific applications, from translucent cell samples in microscopy to fields of dark matter bending light from faraway galaxies. This problem poses a unique challenge because the refractive field directly affects the path that light takes, making its recovery a non-linear problem. In addition, in contrast with traditional tomography, we seek to recover the refractive field using a projected image from only a single viewpoint by leveraging knowledge of light sources scattered throughout the medium. In this work, we introduce a method that uses a coordinate-based neural network to model the underlying continuous refractive field in a scene. We then use explicit modeling of rays' 3D spatial curvature to optimize the parameters of this network, reconstructing refractive fields with an analysis-by-synthesis approach. The efficacy of our approach is demonstrated by recovering refractive fields in simulation, and analyzing how recovery is affected by the light source distribution. We then test our method on a simulated dark matter mapping problem, where we recover the refractive field underlying a realistic simulated dark matter distribution.
</div>

[arXiv link](https://arxiv.org/abs/2309.04437)

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

## This Looks Like Those: Illuminating Prototypical Concepts Using Multiple Visualizations
***

<div class='img' style='float: right; width: 15%;'>
  <img class='img_responsive' src='/images/birds.png' />
</div>

<div class='text' style='width: 80%;'>
  ProtoConcepts is a method for interpretable image classification combining deep learning and case-based reasoning using prototypical parts. Existing work in prototype-based image classification uses a ``this looks like that'' reasoning process, which dissects a test image by finding prototypical parts and combining evidence from these prototypes to make a final classification. However, all of the existing prototypical part-based image classifiers provide only one-to-one comparisons, where a single training image patch serves as a prototype to compare with a part of our test image. With these single-image comparisons, it can often be difficult to identify the underlying concept being compared (e.g., ``is it comparing the color or the shape?''). Our proposed method modifies the architecture of prototype-based networks to instead learn prototypical concepts which are visualized using multiple image patches. Having multiple visualizations of the same prototype allows us to more easily identify the concept captured by that prototype (e.g., ``the test image and the related training patches are all the same shade of blue''), and allows our model to create richer, more interpretable visual explanations. Our experiments show that our ``this looks like those'' reasoning process can be applied as a modification to a wide range of existing prototypical image classification networks while achieving comparable accuracy on benchmark datasets. 

  This work was recently accepted at NeurIPS 2023. 
</div>

[arXiv link](https://arxiv.org/abs/2310.18589)

## Epidemics on Random Graphs
***

<div class='img'>
  <img class='img_responsive' style='float: right;' src='/images/EpidemicTree.png' />
</div>

Studied asymptotics of the contact process on random periodic trees. In particular, I helped to derive bounds for critical values of phase transitions for the contact process on \\((1,n)\\) trees as well as \\((a,b,c)\\) trees. This work was the result of a group project advised by Professors Rick Durrett and Matthew Junge at Duke as part of the DoMath program. 

[arXiv link](https://arxiv.org/pdf/1808.01863)

Jiang, Y., Kassem, R., York, G., Zhao, B., Huang, X., Junge, M., & Durrett, R. (2018) "The contact process on periodic trees." <i>arXiv preprint arXiv:1808.01863.</i>