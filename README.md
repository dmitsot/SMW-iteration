# An iterative method based on Sherman-Morrison-Woodbury regular splitting for nearly circulant matrices

This contains a Python implementation of an iterative method for the numerical solution of linear systems with nearly circulant matrices based on the Sherman-Morrison-Woodbury regular splitting.

A nearly circulant matrix $A$ is a matrix that can be written in the form $A=M-N$ where $M$ is circulant and $N$ such that $\rho( M^{-1}N)<1$.

The SMW iteration is 
$$x^{(k+1)}=M^{-1}(Nx^{(k)}+b)$$
for $k=0,1,\dots$.

For more information please see my website or the preprint https://arxiv.org/abs/2305.10968.
