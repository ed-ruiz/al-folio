---
layout: page
title: 3D Scene saliency
description: Multiple-affordance detection using deep 3D scene saliency
img: /assets/img/saliency_img.jpg
importance: 1
---

<strong>Geometric Affordance Perception: Leveraging Deep 3D Saliency With the Interaction Tensor</strong>

<a href="ed-ruiz.github.io/">Eduardo Ruiz </a> and <a href="http://people.cs.bris.ac.uk/~wmayol/"> Walterio Mayol-Cuevas</a>

<b>Abstract</b>

Agents that need to act on their surroundings can significantly benefit from the perception of their interaction possibilities or affordances. In this paper we combine the benefits of the Interaction Tensor, a straight-forward geometrical representation that captures multiple object-scene interactions, with deep learning saliency for fast parsing of affordances in the environment. Our approach works with visually perceived 3D pointclouds and enables to query a 3D scene for locations that support affordances such as sitting or riding, as well as interactions for everyday objects like the where to hang an umbrella or place a mug. Crucially, the nature of the interaction description exhibits one-shot generalization. Experiments with numerous synthetic and real RGB-D scenes and validated by human subjects, show that the representation enables the prediction of affordance candidate locations in novel environments from a single training example. The approach also allows for a highly parallelizable, multiple-affordance representation, and works at fast rates. The combination of the deep neural network that learns to estimate scene saliency with the one-shot geometric representation aligns well with the expectation that computational models for affordance estimation should be perceptually direct and economical.

<iframe src="https://drive.google.com/file/d/1DSZjZndRudLFJgS3TXXe9Y8AmsMrd2my/preview" width="640" height="480"></iframe>


Paper (open access): <a href="https://www.frontiersin.org/articles/10.3389/fnbot.2020.00045/full"> https://www.frontiersin.org/articles/10.3389/fnbot.2020.00045/full </a>

If you use our code or method in your work, please cite the following:

```markdown
@article{Ruiz-Mayol2020,
author={Ruiz, Eduardo and Mayol-Cuevas, Walterio},   	 
title={Geometric Affordance Perception: Leveraging Deep 3D Saliency With the Interaction Tensor},      
journal={Frontiers in Neurorobotics},      
volume={14},      
pages={45},     
year={2020},             
doi={10.3389/fnbot.2020.00045},      	
issn={1662-5218},
```

<strong>Code and Data</strong>

Please visit our main project repository for more information and access to code and data:

<a href="https://github.com/eduard626/interaction-tensor-affordances"> https://github.com/eduard626/interaction-tensor-affordances </a>
