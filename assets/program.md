# Tensor Network States: Algorithms and Applications 2019-2020  

## Time Table

|   | 12/4 (Wed)  |  12/5 (Thu) | 12/6 (Fri)  |
|---|---|---|---|
|09:00—09:30| registration | registration  |  registration |
|09:30—10:30| [Naoki Kawashima](#kawashima)  | [Tao Xiang](#xiang) |  [Ian McCulloch](#mcculloch) |
|10:30—10:50| break | break  | break  |
|10:50—11:30|[Pan Zhang](#zhang) |[Dong-Hee Kim](#kim)|[Katharine Hyatt](#hyatt)|
|11:30—12:10|[Kouichi Okunishi](#okunishi)|[Tsuyoshi Obuko](#obuko)|[Ching-Yu Huang](#huang)|
|12:10—13:30|lunch| lunch|lunch|
|13:30—14:30|[Tomotoshi Nishino](#nishino)|[Chia-Min Chung](#chung)|[Stefan Kuhn](#kuhn)|
|14:30—15:10|[Kenji Harada](#harada)|[Satoshi Morita](#morita)|[C.-J. David Lin](#lin)|
|15:10—15:30|break|break|break|
|15:30—16:10|[Poster session discussion](/poster/)|[Yoshifumi Nakamura](#nakamura)|[Daisuke Kadoh](#kadoh)|
|16:10—16:50|Poster session discussion|||
|||banquet|



updated: 2019/12/02

\pagebreak

## Abstracts
## Day One: 12/4 (Wed)
### Morning session
Chair: Ying-Jer Kao

## <a name="kawashima"></a>Understanding Kitaev Related Models through Tensor Networks
Naoki Kawashima, ISSP, University fo Tokyo

I review recent activities related to the Kitaev model and its derivatives. Especially, we developed a new series of tensor network ansatzes that describes the ground state of the Kitaev model with high accuracy. The series of ansatzes suggest the essential similarity between the classical loop gas model and the Kitaev spin liquid. We also use the ansatzes for the initial state for TEBD-type optimization.

## <a name="zhang"></a>Approximately contracting arbitrary tensor networks: efficient algorithms and applications in graphical models and quantum circuit simulations

Pan Zhang, Institute of Theoretical Physics, Chinese Academy of Sciences

Tensor networks are powerful tools in quantum many-body problems, usually defined on lattices where efficient contraction algorithms exist. However, when applied to problems out of physics such as graphical models, the underlying network connections could be far from lattices.
In this talk I will introduce an approach for approximately contracting tensor networks with arbitrary connections, such as on lattices, random graphs, and complete graphs. We show applications of our algorithm in estimating free energy of finite-size spin glasses defined on various of topologies, where our algorithm outperforms existing algorithms including mean-field, MCMC based, and recently proposed neural network based methods. We further apply our algorithm to simulations of random quantum circuits with a low depth, where it displays significant speed up and memory efficiency over exact simulations while produce only negligible SVD cut-off error.

## <a name="okunishi"></a> Corner transfer matrix and lattice Unruh effect for the XXZ chain

Kouichi Okunishi, Department of Physics, Niigata University

For the XXZ chain, we discuss the relation between a lattice version of Unruh effect and the ground-state entanglement on the basis of corner transfer matrix. We show that the lattice Unruh temperature with an effective acceleration can be related to the anisotropy parameter of the XXZ chain. Quantum Monte Carlo simulations demonstrate that world lines of spins surrounding the entangle point provides an intuitive view for the quantum entanglement. We also discuss an XXZ-chain analogue of the detector for the thermalized entanglement spectrum.

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

## <a name="harada"></a> New numerical approaches for directed percolation

Kenji Harada, Graduate School of  Informatics, Kyoto University

The directed percolation(DP) is a canonical model of a nonequilibrium continuous transition. A broad class of dynamical processes shares the critical property with the DP in spacetime. In this talk, I introduce our recent numerical study of DP with new numerical approaches. I report MPS[1] and Monte Calro results of the entropies of DP in the (1+1)-dimensional spacetime, and TRG results with an oblique projection for the transfer matrix of DP.

[1]     K. Harada and N. Kawashima, Entropy Governed by the Absorbing State of Directed Percolation, Phys. Rev. Lett. 123, 090601 (2019).

\pagebreak

## Day two: 12/5 (Thurs)
### Morning session

Chair: Ching-Yu Huang

## <a name="xiang"></a> Berezinskii-Kosterlitz-Thouless Criticality in the $q$-state Clock Model

Tao Xiang, Institute of Physics, Chinese Academy of Sciences

We perform state-of-the-art tensor network simulations to pinpoint the nature of phase transitions in the two-dimensional $q$-state clock model. We establish that for all $q$, a $Z_q$-deformed sine-Gordon theory describesthe 2D $q$-state clock model in the continuum limit. For $q > 4$, this field theory predicts that a critical phase
emerges within an intermediate temperature domain $T_{c1} < T < T_{c2}$, with both critical points at $T_{c1}$ and $T_{c2}$ being Berezinskii-Kosterlitz-Thouless (BKT) transitions. We determine precisely the critical temperatures by performing tensor network simulations in the thermodynamic limit and provide extensive numerical evidences supporting that both critical points for $q > 4$ are of the BKT-type. Within the critical phase, we determine for the first time the single characteristic parameter (related to the compactification radius in compactified boson conformal field theory) governing the critical properties and give a hint on the possible existence of a self-dual point in the phase diagram.


## <a name="kim"></a> Higher-order tensor renormalization group study on partition function zeros in the $p$-state clock model

Dong-Hee Kim, Department of Physics and Photon Science, Gwangju Institute of Science and Technology

In this talk, I present our recent study on partition function zeros in the p-state clock model in square lattices. First, I discuss the numerical difficulties that the previous Wang-Landau Monte Carlo calculations faced so that they were limited to very small system sizes. The physical origin of the difficulties is highly related to the nondivergent specific heat at the Berezinskii-Kosterlitz-Thouless (BKT) transitions expected in the $p$-state clock model of $p>4$, causing an exponentially growing signal-to-noise ratio in the Monte Carlo measurements of partition function with increasing system size. Then, I present our main results based on the higher-order tensor renormalization group (HOTRG) calculations of the leading Fisher zeros in these systems. By employing the HOTRG method, which is free from stochastic noises, we manage to reach the systems of $128 \times 128$ sites in search for the leading Fisher zeros in the model of $p$=5 and 6. To perform the finite-size-scaling (FSS) analysis, we have derived the logarithmic finite-size corrections to the scaling of the leading zeros. We have found that their FSS behaviors show excellent agreement with our predictions of the logarithmic corrections to the BKT ansatz at both of the high- and low-temperature transitions in the $p$-state clock model, resolving the disagreements between the previous Fisher zero studies and the other studies with different measures.

## <a name="obuko"></a> Anisotropic tensor renormalization group

Tsuyoshi Obuko, Department of Physics, University of Tokyo

The real-space renormalization group methods based on tensor network representations are becoming popular numerical algorithms for calculating classical/quantum partition functions. However, when we consider high dimensional tensor networks, the existing methods, such as HOTRG, are suffered from huge computation cost. In this talk, we proposed a new algorithm, named the Anisotropic Tensor Renormalization Grope (ATRG) [1]. Different from the previous methods, we decompose tensors in an anisotropic way so that the increase of the computation cost in high dimensions can be suppressed: For d dimensional hyper cubic lattice with the bond dimension $D$, it scales as $D^{2d+1}$. We will demonstrate the ability of ATRG for several models; They show that the accuracy with fixed computation time is improved greatly compared with HOTRG. [1] D. Adachi, T. Okubo, and S. Todo, arXiv:1906.02007.


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

## <a name="morita"></a> Higher-order tensor renormalization group with the corner transfer matrix

Satoshi	Morita, ISSP, University of Tokyo

The higher-order tensor renormalization group method (HOTRG) is a tensor-network method applicable to higher-dimensional systems. The global optimization with the environment tensor improves the accuracy, which is called the higher-order second renormalization method (HOSRG) [1]. However, its computational cost is larger than HOTRG. In this talk, we propose a new HOSRG algorithm whose computational cost scales the same as HOTRG. We replace the environment tensor with the corner transfer matrices (CTM) and the edge tensors. Since CTM can be updated by using the CTM renormalization group [2], our algorithm does not need a backward iteration. If time permits, we will also report other topics related to HOTRG.
[1] Z. Y. Xie, et al., Phys. Rev. B 86, 045139 (2012)
[2] T. Nishino, K. Okunishi, J. Phys. Soc. Jpn, 65, 891 (1996); 66, 3040 (1997)

## <a name="nakamura"></a> Towards computing the standard model of particle physics by tensor renormalization group

Yoshifumi	Nakamura, Center for Computational Science, RIKEN

In this talk, I will review recent works on quantum field theory
by using tensor renormalization group and discuss computations
of the standard model of particle physics.

\pagebreak
## Day Three: 12/6 (Fri)
### Morning session

Chair: Chia-Min Chung


## <a name="mcculloch"></a>  Correlations and order parameters in infinite matrix product states

Ian McCulloch, School of Physics and Mathematics, University of Queensland

I will give a pedagogical survey of methods based on correlation
functions, order parameters, fluctuations, and scaling functions, for
determining critical properties of 1D transitionally-invariant systems,
focusing on recent work on scaling functions and Binder cumulants.

## <a name="hyatt"></a> DMRG Approach to Optimizing Two-Dimensional Tensor Networks

Katharine	Hyatt, Center for Computational Quantum Physics, Flatiron Institute

Tensor network algorithms have been remarkably successful solving a variety of problems in quantum many-body physics. However, algorithms to optimize two-dimensional tensor networks known as PEPS lack many of the aspects that make the density matrix renormalization group (DMRG) algorithm so powerful for optimizing one-dimensional tensor networks known as matrix product states (MPS). I will motivate the development of our DMRG-for-PEPS technique from the more common MPS case, discuss our implementation, and propose some further directions for research and applications.

## <a name="huang"></a> The application of tensor network method in three dimensional quantum system

Ching-Yu Huang, Department of Applied Physics, Tunghai University

In our work, we employ a tensor-network method to compute physical observables in  three-dimensional quantum wave functions. First, topologically ordered quantum systems have robust physical properties, such as quasiparticle statistics and ground-state degeneracy, which do not depend on the microscopic details of the Hamiltonian. We consider a three-dimensional  $Z_N$ topological phase under a string tension $g$.  We calculate the modular matrices $S$ and $T$ using tensor network methods and these matrices can serve as order parameters to determine the critical string tension $g_c$. The obtained transition agrees with results from a mapping to a three-dimensional classical N-state Potts model.  We also consider the  Affleck-Kennedy-Lieb-Tasaki (AKLT) state on the cubic lattice and study the phase diagram  of the AKLT state with deformation numerically.

### Afternoon session

Chair: Ian McCulloch

## <a name="kuhn"></a> Application of Tensor Network States to Lattice Field Theories

Stefan	Kühn, Perimeter Institute

The conventional Euclidean time Monte Carlo approach to Lattice Field Theories faces a major obstacle in the sign problem in certain parameter regimes, such as the presence of a nonzero chemical potential or a topological theta-term. Tensor Network States, a family of ansatzes for the efficient description of quantum many-body states, offer a promising alternative for addressing Lattice Field Theories in the Hamiltonian formulation. In particular, numerical methods based on Tensor Network states do not suffer from the sign problem which makes it possible to study regimes which are not accessible with standard Monte Carlo methods.

Using 1+1d models as test bed, we demonstrate this capability by exploring various scenarios at nonzero chemical potential and with topological theta-term, which are inaccessible with conventional Monte Carlo methods. Our results show that Tensor Networks States are suitable to accurately describe the low-energy spectrum, and that numerical errors can be controlled well enough to make contact with continuum predictions.


## <a name="lin"></a> Phase structure and real-time dynamics of the massive Thirring model in 1+1 dimensions using the tensor-network method

C.-J. David	Lin, Institute of Physics, National Chiao-Tung University

We present concluding results from our study for phase structure
of the massive Thirring model in 1+1 dimensions with staggered
regularisation. Employing the method of matrix product state , several quantities are investigated, leading to numerical evidence of a Kosterlitz-Thouless phase transition. In particular, we examine two correlators and determine the relevant
exponents. Exploratory results for real-time dynamics pertaining to this transition, obtained
using the approaches of variational uniform matrix product state and time-dependent
variational principle, are also discussed.

## <a name="kadoh"></a> A new renormalization group on higher dimensional tensor networks

Daisuke Kadoh, Physics Division, National Center for Theoretical Sciences

We propose a new tensor renormalization group which can be applied to any dimension. We test it in 3d Ising model and compare results to those obtained from the higher-oder TRG and anisotropic TRG methods.


/pagebreak

## <a name="poster"></a> Poster session

### Kibble-Zurek mechanism in quantum link model

Yao-Tai	Kang, Department of Physics, National Tsing Hua University

We study the driven critical dynamics of the quantum link model, whose Hamiltonian describes the one-dimensional $U(1)$ lattice gauge theory. We find that combined topological defects emerge after the quench and they consist of both gauge field and matter field excitations. Furthermore, the ratio of gauge field and matter field excitation is 1/2 due to the constraint of the Gauss' law. We show that the scaling of these combined topological defects satisfies the usual Kibble-Zurek mechanism. We verify that both the electric flux and the entanglement entropy satisfy the finite-time scaling theory in the whole driven process. Possible experimental realizations are discussed.

### Unitary Group Adapted selected CI

Vijay	Chilkuri, Max Planck Institute

### Tensor network renormalization study on boundary CFT underlying classical spin models

Shumpei	Iino, ISSP, University of Tokyo

Tensor network renormalization (TNR) [1] is one of the most efficient tensor renormalization group [2] algorithms,  which is able to eliminate the short correlated loop and yield the correct fixed point tensor even at criticality. We implement the extended TNR algorithm so as to be applicable for the system with open boundaries, and investigate the surface critical behavior and the emergent conformal invariance.  We successfully compute the boundary conformal spectrum for various classical spin models on a lattice, all of which are completely consistent with the results from the underlying boundary CFT [3].

[1] G. Evenbly and G. Vidal, Phys. Rev. Lett. 115, 180405 (2015).
[2] M. Levin and C. P. Nave, Phys. Rev. Lett. 99, 120601 (2007).
[3] S. Iino, S. Morita, and N. Kawashima, in preparation.


### Phase diagram of the SU(2)xSU(2)-invariant Penson-Kolb-Hubbard model

Roman	Rausch, Department of Physics, Kyoto University

Using the variational uniform matrix product state (VUMPS) technique, we investigate the Hubbard model with a nearest-neighbor density-density (extended) term as well as a pair-hopping (Penson-Kolb) term $V$; at a point where the charge-SU(2) pseudospin symmetry is preserved. Strong positive $V$ leads to a phase where s-wave superconductivity is mixed with a charge-density wave (CDW), while strong negative $V$ leads to a phase where $\eta$-wave superconductivity is mixed with phase separation (PS). It is shown that there are also two intervening phases: For negative $V$, we find an intervening partially polarized pseudospin-ferromagnet. For positive $V$, there is a dimerized bond order wave phase (BOW) which is much broader and extends to much larger interactions than in the charge-SU(2) broken extended Hubbard model. Apart from standard techniques, we also apply machine learning to confirm its phase boundaries.

### Self-learning Monte Carlo simulation in the semiclassical site-diluted double-exchange model

Hidehiko	Kohshiro, ISSP, University of Tokyo

The self-learning Monte Carlo (SLMC) method is a speed-up algorithm for Markov chain Monte Carlo simulation which employs an effective model trained to generate a Boltzmann weight similar to one of the original model[1]. SLMC method has not been applied to inhomogeneous systems. We applied SLMC method to the site-diluted the semiclassical double exchange model, where itinerant many-body electron system coupled to localized classical spins to investigate the efficiency of SLMC for disordered systems[3]. As a result of training, we observed RKKY-like exchange coupling, which oscillates with a distance between localized spins consistent with previous work [2].

[1]J. Liu et al., PRB 95, 041101(R) (2017). [2]J. Liu et al., PRB 95, 241104(R) (2017). [3]H. Kohshiro and Y. Nagai, in preparation.

### Numerical strong-disorder renormalization group for two-dimensional random quantum spin systems

Kouichi	Seki, Department of Physics, Niigata University

Recently, two-dimensional (2D) frustrated quantum spin systems with random interactions attract much interest, where the randomness and frustration effects may cooperatively induce exotic spin-liquid-like behaviors[1]. However, the exact diagonalization (ED) results in the previous studies are not sufficient to conclude precise properties of such exotic behaviors. The main purpose of our study is to develop a numerical renormalization group approach that efficiently works for the 2D random quantum spin systems, on the basis of the strong-disorder renormalization groups (SDRGs)[2,3], which actually succeeded in extracting the random singlet ground state of 1D random quantum spin systems. We reformulate an SDRG algorithm for 2D random quantum spin systems and then evaluate its numerical accuracy with precise comparisons with ED results up to 24 spins. We then find that that the numerical accuracy is significantly affected by definitions of energy scale cutoffs used in renormalizing two block spins. In our presentation, we explain the physical roles of the energy scale cutoffs and then present benchmark results of our numerical SDRG for S = 1/2 triangular lattice Heisenberg antiferromagnets with box-type random exchange couplings.

[1] K. Watanabe, H. Kawamura, H. Nakano, T. Sakai, J. Phys. Soc. Jpn. 83, 034714 (2014).
[2] S.-k. Ma, C. Dasgupta, and C.-k. Hu, Phys. Rev. Lett. 43, 1434 (1979).
[3] T. Hikihara, A. Furusaki, and M. Sigrist, Phys. Rev. B 60, 12116 (1999).

### Direct numerical observation of Bose-Einstein condensation of deconfined spinons

Adam Iaizzi, Department of Physics, National Taiwan University

We study a 2D S=1/2 quantum antiferromagnet (the J-Q model) in the presence of an external magnetic field using quantum Monte Carlo methods. The J-Q model combines the standard Heisenberg exchange (J) with a four-spin interaction (Q) that drives a quantum phase transition from the O(3) Néel state to the valence-bond solid (a nonmagnetic state breaking Z4 lattice symmetry). This transition is believed to be an example of deconfined quantum criticality, where the critical point is described by exotic fractionalized excitations called spinons (S=1/2 bosons) [1]. We present direct evidence for the presence of these fractionalized excitations. Using a magnetic field we induce a finite ground-state density of magnetic excitations at the critical point and measure energy as a function of field and temperature. Expanding on previous work [2], we include an extra U(1) gauge field in our analysis, resulting in new predictions for the behavior of both a BEC and gas of deconfined spinons. We compare these predictions to numerical results. At low temperatures, we find behavior consistent with a Bose-Einstein condensate of deconfined spinons. At higher temperatures we find an anomalous temperature dependence that can only be explained by a gas of deconfined spinons. Our findings are also summarized in our preprint [3].
[1] H Shao, W Guo & AW Sandvik, Science 352, 213 (2016)
[2] HD Scammell & OP Sushkov, Phys. Rev. Lett. 114 055702 (2015)
[3] A Iaizzi, HD Scammell, OP Sushkov & AW Sandvik arXiv:1909.01594 (under review)


### Phase Transition of the Ising Model on a 3-Dimensional Fractal Lattice

Jozef Genzor, Department of Physics, National Taiwan University

The current study is an extension of our earlier study of the phase transition phenomena on a fractal lattice*. Whereas the before-studied fractal lattice was embedded into the two-dimensional space, now, the embedding space is three dimensional. It can be expected that such a change of the topology would have a rather significant influence on the character of the phase transition of the system. The Hausdorff dimension of the currently-studied fractal lattice is exactly $d^{(\text{H})} = \ln32 / \ln4 = 2.5$; thus, singular behavior of the specific heat might be expected, as such behavior is already exhibited by a regular square-lattice Ising model. Indeed, we have observed a singular behavior (divergence) at $T_{\text{c}}$ of the specific heat per site $c(T)$ obtained as a numerical derivative of the bond energy $u$ with respect to the temperature, i.~e., $c(T)=d u/ dT$. We want to emphasize that this behavior is different from one observed in the case of the 2-dimensional fractal lattice with the Hausdorf dimension $d^{(H)} = \ln 12 / \ln 4 \approx 1.792$ studied earlier*, where no such divergence was found. Moreover, even though the currently studied fractal is three-dimensional, the critical exponent $\beta \approx 0.059 \approx 1/17$ is smaller than the exponent in the case of the square lattice Ising model $\beta_{\text{square}}=1/8$.

*J. Genzor, A. Gendiar, and T. Nishino, Phys. Rev. E {\bf 93} (2016) 012141.
