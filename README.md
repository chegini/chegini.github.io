# Modeling and Simulation of Complex Processes

#### Technical Skills: C++, Python, FEM, Inverse problem, regularization, PDF constraints optimization, Preconditioner, Multilevel Nonlinear Solver, MPI 

## Education
- Ph.D., computational science | USI Università della Svizzera italiana in Switzerland (_2022_)            		
- M.S., Intelligent Systems	| USI Università della Svizzera italiana in Switzerland (_2015_)
- B.S., Computer Science | USI Università della Svizzera italiana in Switzerland (_2013_)
- B.S., Electronic Engineer | Islamic Azad University (_2002_)
  
## Thesis Title

  - Ph.D.  Multilevel Optimization Algorithm for Inverse Problem in Electrocardiography (written in C++), 
  - B.S. A Spectral Approach to Cross-Modal Information Retrieval (Written in Matlab)
  - B.S. A GLR parser generator for arbitrary context-free grammars (written in java)
  - B.S. Soft Starter for Induction Motors

## Work Experience
**Postdoctoral Research Fellow @ ZUse Institute Belin (_April 2021 - Present_)**
- participate in the #MICROCARD project funded by the EU Joint Undertaking HPC and BMB, developing numerical software to simulate cardiac excitation with a cellular resolution at organ scale on advanced HPC exascale systems. [MICROCARD project](https://microcard.eu/index-en.html)
- FEM discretization of a Cadidac model at the cellar level (EMI model)
- Higher order time integration method
- domain decomposition method(BDDC)
- data compression + MPI in BDDC 
- developing the EMI model in [openCarp](https://opencarp.org/)

![measured data](/assets/img/gonzo.png)
  
**Electronic Engineer (_2006 - 2010)**
- Designing and programming of control systems (PLC) used in CNC Machines:
- Repairing electronic boards and power supplies
- Designing and manufacturing of industrial electrical panels

**Electronic Engineer @TAK YAB ASIA in Tehran, Iran (_2004 - 2006)**
- The company was an agency of the DMG company from Germany in Iran that imported the next generation of CNC machines from DMG Germany; I was working as an electronic engineer focused on control systems.

**Electronic Engineer @ ALMASE SAZ CO. (_2002 - 2003)**
- To Maintenance and repair system controllers/drivers such as Siemens, HEIDENHAIN, Deckle, and ABB used in CNC machines.

## Online Certificate
 - Deep Learning Nanodegree Udacity (2021)
 - NLP Nanodegree Udacity (2021)

## Projects
### Multilevel optimization algorithm for Inverse Problem in Electrocardiography
Detection and quantification of myocardial scars are helpful for the diagnosis of heart diseases and for personalized simulation models. Scar tissue is generally characterized by different conduction of excitation. We aim at estimating conductivity-related parameters from endocardial mapping data. Solving this inverse problem requires computationally expensive monodomain simulations on fine discretizations. We aim at accelerating the estimation by combining electrophysiology models of different complexity. Distributed parameter estimation is performed by minimizing the misfit between simulated and measured electrical activity on the endocardial surface, subject to the monodomain model and regularization. We formulate this optimization problem, including the modeling of scar tissue and different regularizations, and design an efficient solver. We consider grid hierarchies and monodomain–eikonal model hierarchies in a recursive multilevel trust-region method. In several situations, scar reconstruction based on eikonal and monodomain models differ significantly, suggesting the use of the more involved monodomain model for this purpose. Eikonal models can accelerate the computations considerably, enabling the use of complex electrophysiology models for estimating myocardial scars from endocardial mapping data. For computing a maximum posterior estimate, we investigate different optimization approaches based on adjoint gradient computation: steepest descent, limited memory BFGS, and recursive multilevel trust region methods using mesh hierarchies or heterogeneous model- hierarchies. We compare overall performance, asymptotic convergence rate, and pre-asymptotic progress on selected examples in order to assess the benefit of our multi-fidelity acceleration. Implemented the inverse problem by extended Libmesh and integrated into Utopia,  Find [heart](https://bitbucket.org/FatemehChe/heart.git), [based on Libmesh](https://github.com/libMesh/libmesh) & integrated with [utopia](https://bitbucket.org/zulianp/utopia/src/master/) 

![measured data](/assets/img/solution_measured.png)
![Scar detection](/assets/img/target_measured.png)

## Talks
- 2024-01-19 Efficient Domain Decomposition Reconditioners For Time Stepping In EMI Models, wonapde2024 2024, Concepcion, Chile [ca 25 attendees, raising community awareness of Microcard, networking with developer from PETSc and exchange with project members]
- 2023-08-21 Higher order time Integration for EMI Cardiac Electrophysiology Simulations with Nested Subset Selection and BDDC Preconditioning, ICIAM 2023, Tokyo, Japan [ca 20 attendees, raising community awareness of Microcard, networking with developer from PETSc and exchange with project members]
- 2023-07-04 Adaptive higher-order time integration and BDDC preconditioning; EMI in openCARP, Microcard Workshop, Strasbourg [ca 40 attendees, exchange with project members]
- 2023-05-25 Implementing the µCARP simulator, openCARP User Workshop, Karlsruhe [ca 50 attendees, raising awareness of openCARP user community for Microcard and the µCARP code, fostering collaboration on implementation within Microcard]
- 2022-08-03 Higher order time integration with algebraic adaptivity in a cell by cell discretization of cardiac excitation, WCCMC 2022, Yokohama, Japan [ca 25 attendees, raising community awareness of Microcard, and exchange with project members]
- 2022-07-06 Higher-order time integration with algebraic adaptivity in the cell-by-cell model, Microcard Workshop, Bordeaux [ca 40 attendees, exchange with project members]


## Publications
1. J Steyer, F Chegini, T Starý, M Potse, M Weiser, A Loewe. Electrograms in a Cardiac Cell-by-Cell Model 2024
2. F Chegini, T Steinke, M Weiser. Efficient adaptivity for simulating cardiac electrophysiology with spectral deferred correction methods. 2023
3. J Steyer, F Chegini, M Potse, A Loewe, M Weiser. Continuity of Microscopic Cardiac Conduction in a Computational Cell-by-Cell Model. 
2023 Computing in Cardiology (CinC)

4. F Chegini, A Froehly, NMM Huynh, LF Pavarino, M Potse, S Scacchi. Efficient numerical methods for simulating cardiac electrophysiology with cellular resolution. 10th International Conference on Computational Methods for Coupled Problems 2023

5. F Chegini, A Kopaničáková, M Weiser, R Krause. Quantitative Analysis of Nonlinear Multifidelity Optimization for Inverse Electrophysiology. Domain Decomposition Methods in Science and Engineering 2022
6. NMM Huynh, F Chegini, LF Pavarino, M Weiser, S Scacchi. Convergence analysis of BDDC preconditioners for hybrid DG discretizations of the cardiac cell-by-cell model. 2022.
7. F Chegini, M Weiser (2021). Higher-order time integration using spectral deferred correction method (SDC) in a cell by cell discretization of cardiac excitation.

8. F Chegin 2022. Multilevel optimization algorithm for Inverse Problem in Electrocardiography, 29 March 2022, Phd Thesis, Lugano Switzerland. 

9. F Chegini, M Weiser (2021). Machine Learning, Big Data, and Spatial Tools: Adaptive multirate integration of cardiac electrophysiology with spectral deferred correction methods. In: CMBE 2022 Proceedings
10. F Chegini, A Kopaničáková, R Krause, M Weiser (2021). Efficient identification of scars using heterogeneous model hierarchies. In: EP Europace.

