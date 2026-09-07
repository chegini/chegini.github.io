---
title: Publications
seo:
  title: Selected Publications | Fatemeh Chegini
  description: Selected publications by Fatemeh Chegini in cardiac electrophysiology, EMI simulation, domain decomposition, SDC time integration, and inverse problems.
---
{{< brick_wide >}}

## Selected publications

1. F. Göbel, N. M. M. Huynh, F. Chegini, L. F. Pavarino, M. Weiser, S. Scacchi, H. Anzt. **A BDDC Preconditioner for the Cardiac EMI Model in Three Dimensions**. SIAM Journal on Scientific Computing, 48(2), pp. A646-A667, 2026. [DOI](https://doi.org/10.1137/25M1733720), [arXiv](https://arxiv.org/abs/2502.07722).

2. J. Steyer, F. Chegini, T. Starý, M. Potse, M. Weiser, A. Loewe. **Electrograms in a Cardiac Cell-by-Cell Model**. Workshop Biosignals, 2024.

3. J. Steyer, F. Chegini, M. Potse, A. Loewe, M. Weiser. **Continuity of Microscopic Cardiac Conduction in a Computational Cell-by-Cell Model**. Computing in Cardiology, Vol. 50, 2023.

4. N. M. M. Huynh, F. Chegini, L. F. Pavarino, M. Weiser, S. Scacchi. **Convergence Analysis of BDDC Preconditioners for Hybrid DG Discretizations of the Cardiac Cell-by-Cell Model**. SIAM Journal on Scientific Computing, 45(6), pp. A2836-A2857, 2023.

5. F. Chegini, A. Froehly, N. M. M. Huynh, L. F. Pavarino, M. Potse, S. Scacchi, M. Weiser. **Efficient Numerical Methods for Simulating Cardiac Electrophysiology with Cellular Resolution**. 10th International Conference on Computational Methods for Coupled Problems in Science and Engineering, 2023.

6. M. Weiser, F. Chegini. **Adaptive Multirate Integration of Cardiac Electrophysiology with Spectral Deferred Correction Methods**. CMBE22 - 7th International Conference on Computational & Mathematical Biomedical Engineering, pp. 528-531, 2022.

7. F. Chegini, T. Steinke, M. Weiser. **Efficient Adaptivity for Simulating Cardiac Electrophysiology with Spectral Deferred Correction Methods**, 2022.

8. M. Weiser, F. Chegini. **Higher-Order Time Integration Using Spectral Deferred Correction Method in a Cell-by-Cell Discretization of Cardiac Excitation**, 2022. [RADAR dataset/code](https://radar.kit.edu/radar/en/dataset/TxuOjRFnpUVOMgyM), DOI: [10.35097/716](https://doi.org/10.35097/716).

9. F. Chegini. **Multilevel Optimization Algorithm for Inverse Problem in Electrocardiography**. [Project page](https://chegini.github.io/). PhD thesis, Università della Svizzera italiana, Lugano, 2022.

<div class="inverse-ecg-note">
  <h3>Thesis abstract</h3>
  <p>Detection and quantification of myocardial scars support the diagnosis of heart disease and the construction of personalized cardiac simulation models. Scar tissue is characterized by altered excitation conduction, and this inverse problem estimates conductivity-related parameters from endocardial mapping data. The estimation is performed by minimizing the mismatch between simulated and measured electrical activity on the endocardial surface, subject to the monodomain model and regularization.</p>
  <p>Because repeated monodomain simulations on fine discretizations are computationally expensive, the work accelerates the estimation with electrophysiology models of different complexity. It combines grid hierarchies and monodomain-eikonal model hierarchies within a recursive multilevel trust-region method, and compares optimization strategies based on adjoint-gradient computation, including steepest descent, limited-memory BFGS, and recursive multilevel approaches. The implementation extends <a href="https://bitbucket.org/FatemehChe/heart.git">heart</a> and <a href="https://github.com/libMesh/libmesh">libMesh</a>, and integrates the optimization workflow with <a href="https://bitbucket.org/zulianp/utopia/src/master/">Utopia</a>.</p>
  <p>The study evaluates overall performance, asymptotic convergence, and pre-asymptotic progress on representative examples. It shows how eikonal models can reduce computational cost while the more detailed monodomain model remains important for reliable scar reconstruction. The resulting workflow supports maximum-posterior estimation and patient-specific cardiac modeling.</p>
</div>

<div class="inverse-ecg-gallery" aria-label="Inverse electrocardiography reconstruction images">
  <figure>
    <img src="/uploads/research/solution_measured.png" alt="Reconstructed scar solution from measured electrocardiography data">
    <figcaption>Reconstructed solution from measured data.</figcaption>
  </figure>
  <figure>
    <img src="/uploads/research/target_measured.png" alt="Target scar region from measured electrocardiography data">
    <figcaption>Target scar region used for comparison.</figcaption>
  </figure>
</div>

10. F. Chegini, A. Kopaničáková, M. Weiser, R. Krause. **Quantitative Analysis of Nonlinear Multifidelity Optimization for Inverse Electrophysiology**. Domain Decomposition Methods in Science and Engineering XXVI, pp. 65-76, 2022.

11. F. Chegini, A. Kopaničáková, R. Krause, M. Weiser. **Efficient Identification of Scars Using Heterogeneous Model Hierarchies**. EP Europace, 23, pp. i113-i122, 2021.

{{< /brick_wide >}}
