---
layout: splash
permalink: /program/
title: "Program"
header:
  overlay_image: "/assets/images/data-stream-abstract-hd-wallpaper-1920x1080-2373.jpg"
  overlay_filter: 0.5
---

|   | 12/4 (Wed)  |  12/5 (Thu) | 12/6 (Fri)  |
|---|---|---|---|
|09:00—09:30| registration | registration  |  registration |
|09:30—10:30| [Naoki Kawashima](#kawashima)  | [Tao Xiang](#xiang) |  [Ian McCulloch](#mcculloch) |
|10:30—10:50| break | break  | break  |
|10:50—11:30|[Pan Zhang](#zhang) |[Dong-Hee Kim](#kim)|[Katharine Hyatt](#hyatt)|
|11:30—12:10|[Kouichi Okunishi](#okunishi)|[Tsuyoshi Obuko](#obuko)|[Ching-Yu Huang](#huang)|
|12:10—13:30|lunch| lunch|lunch|
|13:30—14:30|[Tomotoshi Nishino](#nishino)|[Chia-Min Chung](#chung)|[Stefan Kühn](#kuehn)|
|14:30—15:10|[Kenji Harada](#harada)|[Satoshi Morita](#morita)|[C.-J. David Lin](#lin)|
|15:10—15:30|break|break|break|
|15:30—16:10|[Poster session discussion](/poster/)|[Yoshifumi Nakamura](#nakamura)|[Daisuke Kadoh](#kadoh)|
|16:10—16:50|Poster session discussion|||
|||banquet|

[pdf version](/assets/program.pdf){:target="_blank"}

updated: 2019/12/02

## Abstracts
## Day One: 12/4 (Wed)
### Morning session
Chair: Ying-Jer Kao

## <a name="kawashima"></a>Understanding Kitaev Related Models through Tensor Networks
Naoki Kawashima, ISSP, University fo Tokyo

I review recent activities related to the Kitaev model and its derivatives. Especially, we developed a new series of tensor network ansatzes that describes the ground state of the Kitaev model with high accuracy. The series of ansatzes suggest the essential similarity between the classical loop gas model and the Kitaev spin liquid. We also use the ansatzes for the initial state for TEBD-type optimization.

[Slides](/assets/slides/kawashima.pdf){:target="_blank"}

## <a name="zhang"></a>Approximately contracting arbitrary tensor networks: efficient algorithms and applications in graphical models and quantum circuit simulations

Pan Zhang, Institute of Theoretical Physics, Chinese Academy of Sciences

Tensor networks are powerful tools in quantum many-body problems, usually defined on lattices where efficient contraction algorithms exist. However, when applied to problems out of physics such as graphical models, the underlying network connections could be far from lattices.
In this talk I will introduce an approach for approximately contracting tensor networks with arbitrary connections, such as on lattices, random graphs, and complete graphs. We show applications of our algorithm in estimating free energy of finite-size spin glasses defined on various of topologies, where our algorithm outperforms existing algorithms including mean-field, MCMC based, and recently proposed neural network based methods. We further apply our algorithm to simulations of random quantum circuits with a low depth, where it displays significant speed up and memory efficiency over exact simulations while produce only negligible SVD cut-off error.

[Slides](/assets/slides/zhang.pdf){:target="_blank"}

## <a name="okunishi"></a> Corner transfer matrix and lattice Unruh effect for the XXZ chain

Kouichi Okunishi, Department of Physics, Niigata University

For the XXZ chain, we discuss the relation between a lattice version of Unruh effect and the ground-state entanglement on the basis of corner transfer matrix. We show that the lattice Unruh temperature with an effective acceleration can be related to the anisotropy parameter of the XXZ chain. Quantum Monte Carlo simulations demonstrate that world lines of spins surrounding the entangle point provides an intuitive view for the quantum entanglement. We also discuss an XXZ-chain analogue of the detector for the thermalized entanglement spectrum.

[Slides](/assets/slides/okunishi.pdf){:target="_blank"}

### Afternoon Session
Chair: Pochung Chen

## <a name="nishino"></a> Thermodynamic Properties of Discrete Classical Heisenberg Models on Square Lattice

Tomotoshi Nishino, Department of Physics, Kobe University

In the first part of this talk we explain the classification of statistical lattice models, that
have discrete site degrees of freedom, from the view point of their model construction, and
briefly review the nature of their thermodynamic properties, chiefly in two dimension.
In the second part we focus on the polyhedral models, which are discrete analogues of
the classical Heisenberg model, on the square lattice. We analyze the character of phase
transition by means of corner transfer matrix renormalization group (CTMRG) method.
Thermodynamic functions and entanglement entropy are observed for the determination of
the universality class. In contrast to the clock models, which are the discrete analogues of
the classical XY model, no intermediate phase appears.
We finally discuss numerical challenges in near future in the field of study.

[1] ‘Phase diagram of truncated tetrahedral model’, Phys. Rev. E 94, 022134 (2016); arXiv:1512.09059.
[2] ‘Critical behavior of the two-dimensional icosahedron model’, Phys. Rev. E 96, 062112 (2017); arXiv:1709.01275.
[3] ‘Phase transition of the six-state clock model observed from the entanglement entropy’, arXiv:1612.07611.

[Slides](/assets/slides/nishino.pdf){:target="_blank"}

## <a name="harada"></a> New numerical approaches for directed percolation

Kenji Harada, Graduate School of  Informatics, Kyoto University

The directed percolation(DP) is a canonical model of a nonequilibrium continuous transition. A broad class of dynamical processes shares the critical property with the DP in spacetime. In this talk, I introduce our recent numerical study of DP with new numerical approaches. I report MPS[1] and Monte Calro results of the entropies of DP in the (1+1)-dimensional spacetime, and TRG results with an oblique projection for the transfer matrix of DP.

[1]     K. Harada and N. Kawashima, Entropy Governed by the Absorbing State of Directed Percolation, Phys. Rev. Lett. 123, 090601 (2019).

[Slides](/assets/slides/harada.pdf){:target="_blank"}

## <a name="poster"></a> Poster session

[Abstracts](/poster/){:target="_blank"}

## Day two: 12/5 (Thurs)
### Morning session

Chair: Ching-Yu Huang

## <a name="xiang"></a> Berezinskii-Kosterlitz-Thouless Criticality in the $$q$$-state Clock Model

Tao Xiang, Institute of Physics, Chinese Academy of Sciences

We perform state-of-the-art tensor network simulations to pinpoint the nature of phase transitions in the two-dimensional $$q$$-state clock model. We establish that for all $$q$$, a $$Z_q$$-deformed sine-Gordon theory describesthe 2D $$q$$-state clock model in the continuum limit. For $$q > 4$$, this field theory predicts that a critical phase
emerges within an intermediate temperature domain $$T_{c1} < T < T_{c2}$$, with both critical points at $$T_{c1}$$ and $$T_{c2}$$ being Berezinskii-Kosterlitz-Thouless (BKT) transitions. We determine precisely the critical temperatures by performing tensor network simulations in the thermodynamic limit and provide extensive numerical evidences supporting that both critical points for $$q > 4$$ are of the BKT-type. Within the critical phase, we determine for the first time the single characteristic parameter (related to the compactification radius in compactified boson conformal field theory) governing the critical properties and give a hint on the possible existence of a self-dual point in the phase diagram.

[Slides](/assets/slides/txiang.pdf){:target="_blank"}

## <a name="kim"></a> Higher-order tensor renormalization group study on partition function zeros in the $$p$$-state clock model

Dong-Hee Kim, Department of Physics and Photon Science, Gwangju Institute of Science and Technology

In this talk, I present our recent study on partition function zeros in the p-state clock model in square lattices. First, I discuss the numerical difficulties that the previous Wang-Landau Monte Carlo calculations faced so that they were limited to very small system sizes. The physical origin of the difficulties is highly related to the nondivergent specific heat at the Berezinskii-Kosterlitz-Thouless (BKT) transitions expected in the $$p$$-state clock model of $$p>4$$, causing an exponentially growing signal-to-noise ratio in the Monte Carlo measurements of partition function with increasing system size. Then, I present our main results based on the higher-order tensor renormalization group (HOTRG) calculations of the leading Fisher zeros in these systems. By employing the HOTRG method, which is free from stochastic noises, we manage to reach the systems of $$128 \times 128$$ sites in search for the leading Fisher zeros in the model of $$p$$=5 and 6. To perform the finite-size-scaling (FSS) analysis, we have derived the logarithmic finite-size corrections to the scaling of the leading zeros. We have found that their FSS behaviors show excellent agreement with our predictions of the logarithmic corrections to the BKT ansatz at both of the high- and low-temperature transitions in the $$p$$-state clock model, resolving the disagreements between the previous Fisher zero studies and the other studies with different measures.

[Slides](/assets/slides/DHKIM_TNSAA7.pdf){:target="_blank"}

## <a name="obuko"></a> Anisotropic tensor renormalization group

Tsuyoshi Obuko, Department of Physics, University of Tokyo

The real-space renormalization group methods based on tensor network representations are becoming popular numerical algorithms for calculating classical/quantum partition functions. However, when we consider high dimensional tensor networks, the existing methods, such as HOTRG, are suffered from huge computation cost. In this talk, we proposed a new algorithm, named the Anisotropic Tensor Renormalization Grope (ATRG) [1]. Different from the previous methods, we decompose tensors in an anisotropic way so that the increase of the computation cost in high dimensions can be suppressed: For d dimensional hyper cubic lattice with the bond dimension $$D$$, it scales as $$D^{2d+1}$$. We will demonstrate the ability of ATRG for several models; They show that the accuracy with fixed computation time is improved greatly compared with HOTRG. [1] D. Adachi, T. Okubo, and S. Todo, arXiv:1906.02007.

[Slides](/assets/slides/okubo.pdf){:target="_blank"}

### Afternoon session
Chair: C.-J. David Lin

## <a name="chung"></a> Minimally entangled typical thermal states with auxiliary matrix-product-state bases

Chia-Min Chung, Physics department, Ludwig-Maximilians-Universität München

Finite temperature problems in the strong correlated systems are important but challenging tasks.
Minimally entangled typical thermal states (METTS) are a powerful method in the framework of
tensor network methods to simulate finite temperature systems, including Fermions and frustrated
spins which introduce a sign problem in the typical Monte Carlo methods. In this work, we introduce
an extension of the METTS algorithm by using a new basis, the auxiliary matrix product state.
This new basis achieves the pre-summation process in the partition function, and thus improve the
convergence in the Monte Carlo samplings. The method also has the advantage of simulating the
grand canonical ensemble in a computationally efficient way by employing good quantum numbers.
We benchmark our method on the spin-1/2 XXZ model on the triangular lattice, and show that the
new method outperforms the original METTS as well as the purification methods at sufficiently low
temperature, the usual range of applications of METTS. The new method also naturally connects
the METTS method to the purification method.

[Slides](/assets/slides/chung.pdf){:target="_blank"}

## <a name="morita"></a> Higher-order tensor renormalization group with the corner transfer matrix

Satoshi	Morita, ISSP, University of Tokyo

The higher-order tensor renormalization group method (HOTRG) is a tensor-network method applicable to higher-dimensional systems. The global optimization with the environment tensor improves the accuracy, which is called the higher-order second renormalization method (HOSRG) [1]. However, its computational cost is larger than HOTRG. In this talk, we propose a new HOSRG algorithm whose computational cost scales the same as HOTRG. We replace the environment tensor with the corner transfer matrices (CTM) and the edge tensors. Since CTM can be updated by using the CTM renormalization group [2], our algorithm does not need a backward iteration. If time permits, we will also report other topics related to HOTRG.
[1] Z. Y. Xie, et al., Phys. Rev. B 86, 045139 (2012)
[2] T. Nishino, K. Okunishi, J. Phys. Soc. Jpn, 65, 891 (1996); 66, 3040 (1997)

[Slides](/assets/slides/morita.pdf){:target="_blank"}

## <a name="nakamura"></a> Towards computing the standard model of particle physics by tensor renormalization group

Yoshifumi	Nakamura, Center for Computational Science, RIKEN

In this talk, I will review recent works on quantum field theory
by using tensor renormalization group and discuss computations
of the standard model of particle physics.

[Slides](/assets/slides/nakamura.pdf){:target="_blank"}

## Day Three: 12/6 (Fri)
### Morning session

Chair: Chia-Min Chung

## <a name="mcculloch"></a>  Correlations and order parameters in infinite matrix product states

Ian McCulloch, School of Physics and Mathematics, University of Queensland

I will give a pedagogical survey of methods based on correlation
functions, order parameters, fluctuations, and scaling functions, for
determining critical properties of 1D transitionally-invariant systems,
focusing on recent work on scaling functions and Binder cumulants.

[Slides](/assets/slides/mcculloch.pdf){:target="_blank"}

## <a name="hyatt"></a> DMRG Approach to Optimizing Two-Dimensional Tensor Networks

Katharine	Hyatt, Center for Computational Quantum Physics, Flatiron Institute

Tensor network algorithms have been remarkably successful solving a variety of problems in quantum many-body physics. However, algorithms to optimize two-dimensional tensor networks known as PEPS lack many of the aspects that make the density matrix renormalization group (DMRG) algorithm so powerful for optimizing one-dimensional tensor networks known as matrix product states (MPS). I will motivate the development of our DMRG-for-PEPS technique from the more common MPS case, discuss our implementation, and propose some further directions for research and applications.

[Slides](/assets/slides/khyatt.pdf){:target="_blank"}

## <a name="huang"></a> The application of tensor network method in three dimensional quantum system

Ching-Yu Huang, Department of Applied Physics, Tunghai University

In our work, we employ a tensor-network method to compute physical observables in  three-dimensional quantum wave functions. First, topologically ordered quantum systems have robust physical properties, such as quasiparticle statistics and ground-state degeneracy, which do not depend on the microscopic details of the Hamiltonian. We consider a three-dimensional  $$Z_N$$ topological phase under a string tension $$g$$.  We calculate the modular matrices $$S$$ and $$T$$ using tensor network methods and these matrices can serve as order parameters to determine the critical string tension $$g_c$$. The obtained transition agrees with results from a mapping to a three-dimensional classical N-state Potts model.  We also consider the  Affleck-Kennedy-Lieb-Tasaki (AKLT) state on the cubic lattice and study the phase diagram  of the AKLT state with deformation numerically.

[Slides](/assets/slides/huang.pdf){:target="_blank"}

### Afternoon session

Chair: Ian McCulloch

## <a name="kuehn"></a> Application of Tensor Network States to Lattice Field Theories

Stefan	Kühn, Perimeter Institute

The conventional Euclidean time Monte Carlo approach to Lattice Field Theories faces a major obstacle in the sign problem in certain parameter regimes, such as the presence of a nonzero chemical potential or a topological theta-term. Tensor Network States, a family of ansatzes for the efficient description of quantum many-body states, offer a promising alternative for addressing Lattice Field Theories in the Hamiltonian formulation. In particular, numerical methods based on Tensor Network states do not suffer from the sign problem which makes it possible to study regimes which are not accessible with standard Monte Carlo methods.

Using 1+1d models as test bed, we demonstrate this capability by exploring various scenarios at nonzero chemical potential and with topological theta-term, which are inaccessible with conventional Monte Carlo methods. Our results show that Tensor Networks States are suitable to accurately describe the low-energy spectrum, and that numerical errors can be controlled well enough to make contact with continuum predictions.

[Slides](/assets/slides/kuehn.pdf){:target="_blank"}

## <a name="lin"></a> Phase structure and real-time dynamics of the massive Thirring model in 1+1 dimensions using the tensor-network method

C.-J. David	Lin, Institute of Physics, National Chiao-Tung University

We present concluding results from our study for phase structure
of the massive Thirring model in 1+1 dimensions with staggered
regularisation. Employing the method of matrix product state , several quantities are investigated, leading to numerical evidence of a Kosterlitz-Thouless phase transition. In particular, we examine two correlators and determine the relevant
exponents. Exploratory results for real-time dynamics pertaining to this transition, obtained
using the approaches of variational uniform matrix product state and time-dependent
variational principle, are also discussed.

[Slides](/assets/slides/dlin_TNSAA_2019.pdf){:target="_blank"}

## <a name="kadoh"></a> A new renormalization group on higher dimensional tensor networks

Daisuke Kadoh, Physics Division, National Center for Theoretical Sciences

We propose a new tensor renormalization group which can be applied to any dimension. We test it in 3d Ising model and compare results to those obtained from the higher-oder TRG and anisotropic TRG methods.

[Slides](/assets/slides/kadoh.pdf){:target="_blank"}
