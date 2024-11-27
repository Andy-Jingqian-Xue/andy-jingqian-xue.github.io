---
layout: single
permalink: /ui/uc/intro/
author_profile: false
sidebar:
  nav: "ui"
title: "Urban Complexity"
excerpt: "<em>“Cities, then, are of an **organized complexity**.” — Jane Jacobs (1961), The Death and Life of Great American Cities <em>"
header:
  overlay_image: /assets/images/headeruc.jpg
  overlay_filter: linear-gradient(rgba(231, 100, 100, 0.5), rgba(0, 255, 255, 0.5))
---

# Urban Informatics for both Understanding and Creating Complexity
<div class="author-info">
  Andy Jingqian Xue<br>
  UGOD Thrust, HKUST(GZ)<br>
  Published: 01 December 2024
</div>

Urban spaces are complex, characterized not by linearity but by hierarchical levels of scale. Traditional Gaussian models, with their focus on mean values and standard deviations, fall short in capturing this complexity of geographic features. Instead, urban spaces often exhibit patterns better described by long-tailed distributions and fractal geometry. For instance, the distribution of city sizes can follow a long-tailed distribution or Zipf’s law (Zipf 1949), where there are far more small cities than large ones in the whole world. Similarly, the layout of urban road networks often demonstrates fractal geometry, reflecting complexity across all scales or hierarchy, from major highways to minor streets. Those urban roads could be simply recognized as fractal because they follow the pattern of far more less-connected and short roads than well-connected and long ones (Jiang and Yin 2014). This essay explores urban analysis through the perspective of complexity, challenging conventional approaches using two examples and offering new insights. 

Geographic features in urban spaces are quantitatively shaped by two contrasting distributions from a statistical perspective: the Gaussian distribution and the long-tailed distribution. Gaussian distribution, depicted in histograms as symmetrical bell curves, emphasizes outcomes clustering around a mean. This suggests a level of predictability in certain urban metrics, illustrating that many aspects of urban life can be expected to fall within a normative range. However, geographic features often adhere to long-tailed distribution (Jiang 2015a), visualized as 'L' shape with a long tail which is nonlinear in rank-size plots. These demonstrate how a few cities or individuals can dominate in terms of size and wealth, significantly overshadowing the vast majority. The long-tailed distribution serves as a statistical description of hierarchy within urban phenomena, where hierarchy is a core concept of complexity (Simon 1962). This distinction underscores the complex and uneven nature of urban development, advocating for the use of analytical models that capture the diversity and extremes inherent in urban settings. 

The depiction of urban structure has traditionally relied on Euclidean geometrical concepts, using basic shapes like points, lines, and polygons to represent geographic features. However, Euclidean geometry falls short in accurately describing complex and rough geographic features because it only focuses on individual scales (Jiang 2015b). For example, the length of the UK coastline, as measured, depends on the scale used: the more detailed the scale, the longer the boundary appears (Mandelbrot 1967). This illustrates a fractal characteristic—across scales, there are far more small segments than large ones. Fractal geometry, by capturing patterns that recur at various scales, offers a richer understanding of the complex and irregular designs found in urban and natural landscapes. It aligns with the concept of long-tailed distributions, statistically illustrates the prevalence of many small occurrences over a few large ones, highlighting the inherent complexity of geographic patterns in urban spaces.

In the following two paragraphs, we will further elaborate the long-tailed and fractal perspective with examples from fractal geometry and theories in urban design. Koch curve is a highly self-similar curve generated through multiple iterations. Begin with a single straight line, it is divided into three parts and the middle part is replaced with two equivalent segments, which finally leads to four new segments in an iteration. Each iteration results in a new scale, which are 1/3, 1/9, and 1/27 of the original line, respectively. These scales form a scaling hierarchy, implying that there are far more small-scale segments than large-scale segments in the Koch curve, corresponding to the number of 4, 16, and 64. The Koch curve exemplifies a simple yet standard model that captures statistical and collective complexity, essentially embodying long-tailed distributions and fractal geometry. This relationship, following the power law (Clauset et al. 2009) or scaling law (Jiang 2015a), illustrates how the curve's structure becomes increasingly intricate and aesthetically pleasing with each level of hierarchy, showcasing the fundamental principles of complexity and system sensitivity within a mathematically elegant framework.

The Central Place Theory (CPT) is a typical representation of the concepts of hierarchy in urban science. It seeks to find the optimal spatial configuration of cities based on their quantity, size, and location (Christaller 1933, 1966). A rigorous mathematics model of CPT is that each central place is represented by a regular hexagon and serves six smaller cities, then a smaller city serves six even smaller cities. The city scales are defined as 1, 1/2, and 1/4 from the largest to smallest, corresponding to amounts of 1, 6, and 36 cities. This distribution represents the notion of the long tail as well, suggesting that there are far more small cities than largest cities in a well-organized region or country. This pattern mirrors fractal geometry, where the quantity and scale of cities exhibit self-similar characteristics across different levels of urban organization, reflecting a natural, hierarchical structure in urban planning and development. 

However, the Koch curve and the CPT model are still too restricted for geographic features since a line must be divided into four smaller segments and a city must be surrounded by a certain number of smaller cities. This rigorous definition prevents them from becoming useful models in reality, just as the Koch curve cannot represent the UK coastline since the coastline does not adhere to a fixed scale of change (Jiang 2020). Similarly, many geographical features are not considered fractal due to the strict definition of fractal, despite having fractal characteristics such as irregularity, roughness, and complex shapes. The statistical counterpart is to address the randomness and complexity issue of geographic features in urban spaces. It introduces variability in the scaling ratio of segments of the Koch curve and the number of cities each central place supports in the CPT model, reflecting a more randomized or topological representation of geometry and urban structures. This also highlights the need for more refined and robust models in urban analysis, to deeply understand the statistical long-tailed distributions and the fractal geometry of city composition and structure, thereby effectively addressing the complexity and hierarchy of urban geographical features.


## References
- Christaller W. (1933, 1966), Central Places in Southern Germany, Prentice Hall: Englewood Cliffs, N. J.
- Clauset A., Shalizi C. R., and Newman M. E. J. (2009), Power-law distributions in empirical data, SIAM Review, 51, 661-703.
- Jiang B. and Yin J. (2014), Ht-index for quantifying the fractal or scaling structure of geographic features, Annals of the Association of American Geographers, 104(3), 530-540.<br>
- Jiang B. (2015a), Geospatial analysis requires a different way of thinking: The problem of spatial heterogeneity, GeoJournal, 80(1), 1–13.
- Jiang, B. (2015b), The fractal nature of maps and mapping, International Journal of Geographical Information Science, 29(1), 159–174.
- Jiang B. (2020), Alexander's wholeness as the scientific foundation of sustainable urban design and planning, New Design Ideas, 3(2), 81–98.
- Mandelbrot B. (1967), How long is the coast of Britain? Statistical self-similarity and fractional dimension, Science, 156(3775), 636–638.
- Simon H. A. (1962), The architecture of complexity, Proceedings of the American Philosophical Society, 106(6), 467–482.
- Zipf G. K. (1949), Human Behaviour and the Principles of Least Effort, Addison Wesley: Cambridge, MA.
