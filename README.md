# Code Overview

Compares multiple model architectures like vanilla nets, wide nets, deep nets and ResNets. For efficient loss landscape probing I used hessian eigenvalues, sharpness metrics and 2D visualizations. I also performed a mode connectivity analysis to visualize paths between different minima.

The experiments correlate sharpness with the generalization; architecture comparison to see how design affects landscape geometry; eigenvalue analysis using top-k hessian eigenvalues, eigenvalues are calculated efficiently in O(kn) instead of O(n^3).
