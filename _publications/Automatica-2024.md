---
title: "Provable Bounds on the Hessian of Neural Networks: Derivative-Preserving Reachability Analysis"
collection: publications
category: preprints
permalink: /publication/Automatica-2024
excerpt: 'This paper proposes a novel reachability analysis method tailored for neural networks with differentiable activations using first-order Taylor expansion.'
date: 2024/01
venue: 'Under Review'
# slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/pdf/2406.04476?'
# bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
We propose a novel reachability analysis method
tailored for neural networks with differentiable activations. Our
idea hinges on a sound abstraction of the neural network
map based on first-order Taylor expansion and bounding the
remainder. To this end, we propose a method to compute
analytical bounds on the network’s first derivative (gradient)
and second derivative (Hessian). A key aspect of our method is
loop transformation on the activation functions to exploit their
monotonicity effectively. The resulting end-to-end abstraction
locally preserves the derivative information, yielding accurate
bounds on small input sets. Finally, we employ a branch and
bound framework for larger input sets to refine the abstraction
recursively. We evaluate our method numerically via different
examples and compare the results with relevant state-of-the-art
methods.
