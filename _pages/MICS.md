---
layout: archive
title: ""
permalink: /MICS/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
# Multiphoton Imaging with Computational Specificity (MICS): 
# AI tools for detecting inflammation in label-free multiphoton images


## Conventional pathology: 
Autoimmune diseases, particularly inflammatory bowel diseases (IBD), are a growing global health challenge. These conditions involve complex immune system dysfunctions that damage healthy tissues, leading to chronic inflammation. Diagnosing and understanding these diseases often requires invasive biopsies and labor-intensive processes, which delay timely diagnosis and research. Traditional methods use chemical stains to highlight specific tissue structures, but these processes are slow, costly, and unsuitable for real-time, in vivo analysis.

### Conventional staining:
 
<i class="fa-solid fa-bacteria fa-2xl"></i> + <i class="fa-solid fa-flask-vial fa-2xl"></i> <i class="fa-solid fa-arrow-right"></i> <i class="fa-solid fa-bacteria fa-2xl" style="color: #00ff00;"></i> <i class="fa-solid fa-arrow-right"></i> <i class="fa-solid fa-microscope fa-2xl"></i> 

### Classification by pathologists:
 
<i class="fa-solid fa-lungs fa-2xl"></i>  + <i class="fa-solid fa-flask-vial fa-2xl"></i> <i class="fa-solid fa-arrow-right"></i>  <i class="fa-solid fa-microscope fa-2xl"></i> <i class="fa-solid fa-arrow-right"></i> <i class="fa-solid fa-user-doctor fa-2xl"></i>  <i class="fa-solid fa-arrow-right"></i> <i class="fa-solid fa-check fa-xl" style="color: #008000;"></i>
 
<i class="fa-solid fa-lungs-virus fa-2xl"></i>  + <i class="fa-solid fa-flask-vial fa-2xl"></i> <i class="fa-solid fa-arrow-right"></i>  <i class="fa-solid fa-microscope fa-2xl"></i> <i class="fa-solid fa-arrow-right"></i> <i class="fa-solid fa-user-doctor fa-2xl"></i>  <i class="fa-solid fa-arrow-right"></i> <i class="fa-solid fa-x fa-xl" style="color: #800040;"></i>



## Pathology detection based on label-free imaging and AI support:

The MICS project – Multiphoton Imaging with Computational Specificity is designed to overcome these limitations by combining high-resolution label-free multiphoton microscopy (MPM) with the power of artificial intelligence (AI). Specifically, the project uses deep neural networks to enhance the specificity of MPM images, enabling them to function like traditional stained images while retaining the advantages of being label-free and non-invasive.
Deep neural networks are advanced computational models inspired by how the human brain processes information. These networks consist of multiple layers of interconnected "neurons" that transform input data, such as images, into meaningful outputs, like classifications or predictions. To train a neural network on image data, it is shown thousands of labeled examples, such as images of healthy tissue and inflamed tissue. The network learns patterns by adjusting its internal connections through a process called training, which uses algorithms to minimize errors between its predictions and the known annotations. Over time, the network becomes highly skilled at recognizing features in unseen images. In many AI applications, the limiting factor is to actually obtain these large data sets of high-quality and well-trusted annotations.
By combining previously trained deep neural networks with label-free multiphoton imaging, MICS will be able to directly image samples from many autoimmune diseases without any labor-intensive processing of biopsies and then to digitally augment the readout. This approach offers a faster, non-invasive alternative to conventional histological analysis and has a great potential to advance research into autoimmune diseases and pave the way for new diagnostic tools.

 
### Digital staining: 
 
<i class="fa-solid fa-bacteria fa-2xl"></i> <i class="fa-solid fa-arrow-right"></i> <i class="fa-solid fa-microscope fa-2xl"></i> <i class="fa-solid fa-arrow-right"></i> <i class="fa-solid fa-microchip fa-2xl"></i> <i class="fa-solid fa-arrow-right"></i> <i class="fa-solid fa-bacteria fa-2xl" style="color: #00ff00;"></i>  <br /> 

The MICS project focuses on advancing a cutting-edge AI technique called Digital Staining to enhance the capabilities of label-free multiphoton microscopy (MPM). Digital Staining is an emerging concept in computational microscopy where images from one domain, such as label-free images, are transformed into another domain, like those of specific biomolecular stains. This approach allows researchers to extract the specificity of traditional staining without physically staining the samples.
One of the first major achievements of MICS was the publication of a comprehensive review article on Digital Staining in the high-impact journal PhotoniX [Kreiss, Lucas, et al., 2023](https://doi.org/10.1186/s43074-023-00113-4). This review highlighted the transformative potential of DS and discussed its advantages in addressing key limitations of traditional and label-free imaging methods.
Digital Staining pairs images from label-free modalities, such as MPM autofluorescence, with chemically stained reference images from the same sample. This bypasses two major obstacles:
1.	For training, DS eliminates the need for labor-intensive manual annotations because the ground truth is directly derived from the paired imaging procedure.
2.	After deployment, trained DS models can digitally infer specific staining without requiring the tedious and time-consuming processes of sample preparation, sectioning, and staining.
The PhotoniX review also underscored a critical gap: while computational specificity for common optical modalities like phase contrast or single-photon autofluorescence is well-developed, applications for advanced nonlinear optical imaging techniques like MPM remain underexplored.
Building on these findings, MICS is now developing Digital Staining methods specifically tailored to MPM autofluorescence for immune cells. Preliminary results have been presented at the SPIE Photonics West Conference, the [Duke AI Day 2024](https://otc.duke.edu/event/duke-ai-day/) and [on Youtube](https://www.youtube.com/watch?v=vQGPr9gr9TY).

### Automated detection of inflammation: 

In parallel, MICS is utilizing an annotated database of 3D MPM images from inflammatory bowel disease (IBD) tissues to train a deep neural network for automated disease analysis. This network aims to predict the presence of IBD, identify the type of inflammation, and assess disease severity.
Through these achievements, MICS is pioneering AI-driven solutions to overcome key limitations in label-free imaging, with the potential to revolutionize how we study and diagnose autoimmune diseases.


<i class="fa-solid fa-lungs fa-2xl"></i> <i class="fa-solid fa-arrow-right"></i>  <i class="fa-solid fa-microscope fa-2xl"></i> <i class="fa-solid fa-arrow-right"></i> <i class="fa-solid fa-microchip fa-2xl"></i>  <i class="fa-solid fa-arrow-right"></i> <i class="fa-solid fa-check fa-xl" style="color: #008000;"></i>
 
<i class="fa-solid fa-lungs-virus fa-2xl"></i> <i class="fa-solid fa-arrow-right"></i>  <i class="fa-solid fa-microscope fa-2xl"></i> <i class="fa-solid fa-arrow-right"></i> <i class="fa-solid fa-microchip fa-2xl"></i> <i class="fa-solid fa-arrow-right"></i> <i class="fa-solid fa-x fa-xl" style="color: #800040;"></i>

"Staining tissues enhances visualisation and helps scientists identify potential pathologies. Thereby, biochemical contrast agents bind to target molecules, which provides the desired specificity. Label-free multiphoton microscopy on the other hand, is a powerful imaging technique to generate high-resolution, 3D images in living tissue without use of stains or dyes. Modern AI tools can link the information in these label-free images to a given type of cell or tissue to generate computational specificity. With the support of the Marie Skłodowska-Curie Actions programme, the MICS project will develop such AI tools for digital staining of immune cells and automated classification of mucosal inflammation in multiphoton microscopy images. This will allow direct investigation of specific immune cell localisation and global tissue alteration." (cited from the  <br />  
 
 
If you want to know how multiphoton microscopy works or why it is relevant for autoimmune diseases, like Crohn's Disease or Ulcerative colitis, check out [this page](https://lucaskreiss.github.io//research/). Our review article on digital staining for optical microscopy is [here](https://doi.org/10.1186/s43074-023-00113-4). 



   
## About this Project

<br/><img src='/images/World_map_MICS.png' style="width:450px">
 
This project is funded by a Global fellowship of EU HORIZON 2022's Marie Skłodowska-Curie Actions programme. It is an international and interdisciplinary collaboration between the Friedrich-Alexander University (FAU) in Erlangen, Germany and the Duke University in Durham, North Carolina, USA. More information can also be found at the project description of the [EU page of this project](https://doi.org/10.3030/101103200).


  
## ________________________________________________

<br/><img src='/images/EU_flag.jpg' style="width:150px">

This project has received funding from the European Union’s Horizon 2022 Marie Skłodowska-Curie Action under grant agreements 101103200 (project MICS). Views and opinions expressed are however those of the author(s) only and do not necessarily reflect those of the European Union. Neither the European Union nor the granting authority can be held responsible for them.
