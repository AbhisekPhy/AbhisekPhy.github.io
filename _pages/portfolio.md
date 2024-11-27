---
layout: archive
title: "Research"
permalink: /portfolio/
author_profile: true
---

## Disordered superconductors and their collective modes (Higgs, Goldstone)

<p align="center">
    <img width="800" src="/images/FigSC.jpg" alt="Material Bread logo">
</p>

Superconductivity is characterized by a complex wave-function (with both amplitude and phase), which represents the coherent state of the Cooper pairs. In presence of large disorder, superconductivity can be destroyed due to strong phase fluctuations of the Cooper pairs, even when their amplitude remains finite! This leads to a novel quantum phase transition at zero temperature, called superconductor-insulator transition (SIT). The physics of SIT is "qualitatively" described by inhomogeneous Bogoliubov-de Gennes (BdG) mean-field theory of the attractive Hubbard model -- this theory captures the formation of superconducting "puddles" with lack of phase coherence. However, the BdG theory misses the fluctuations completely!

In our work, we have developed a field-theoretical formalism for disordered superconductors, based on functional integral and effective action, which can add quantum fluctuations around the BdG saddle point. Our formalism can also study the evolution of the collective (amplitude/Higgs, phase/Goldstone) modes with disorder. We show that while the Higgs mode in a clean superconductor is gapped (by 2$\Delta$; $\Delta$ being the superconducting gap), disorder pushes it down to lower energy and forms a sub-gap mode, which can be observed in energy-resolved spectroscopies. In optical conductivity also, sub-gap states emerge due to fluctuations. Through calculations of kinetic inductance and quality factors, we demonstrate that these states can serve as sources of dissipation in superconducting nanowires. To include fluctuations of all orders, both quantum and thermal, we employ Quantum Monte Carlo (QMC) simulations combined with numerical analytic continuation. Our results show that the superconducting gap "fills up" with increasing temperature rather than "closing" -- a non-BCS behavior that is observed in thin-film superconductor experiments!

My current research focuses on low-density unconventional superconductivity in heterostructure materials (e.g. EuO/KTO interface), which hold promise for future generation applications, such as superconducting qubits, memory storage and single photon detectors.

## Transport and thermopower properties of semimetals and interacting systems
![](/images/Hall.jpg){: style="width: 500px; align: centre; border: 10px"}
The Hall coefficient ($R_H$) has been traditionally used to measure the charge carrier density in transport measurements, via the Drude relation $R_H\sim \frac{1}{n}$. However, this relation may break down in semimetals due to the presence of multiple bands and intriguing Fermi surface topology. Multiband conductivity calculations involve coupled Boltzmann equations with interband collision integrals which are quite challenging. We can avoid this difficulty by using a recently developed Hall coefficient formula [Auerbach et al] written in terms of thermodynamic susceptibilities. We have calculated the deviation of $R_H$ from the Drude relation in spin-split semiconductor bands, as well as Weyl and nodal-line semimetals [<a href="https://journals.aps.org/prb/abstract/10.1103/PhysRevB.102.104201"> Samanta et al</a>]. We proposed experiments to measure these deviations. 

In interacting systems, we have calculated $R_H$ over a large range of temperatures between the antiferromagnetic interaction and the Mott gap scales, by using high-temperature expansion of the t-J model, supplemented by DQMC simulations of the strongly interacting Hubbard model. Our calculation explains the observation of "Hall anomalies" in experiments, i.e. abrupt changes in sign and magnitude of $R_H$ in high temperature cuprates. My current research interest extends to explore the thermopower properties (Seebeck) of several multi-band models (such as kagome superconductors, Kane-Mele models), semimetals (Weyl, nodal-line) and interacting systems. These systems promise to provide an interesting playground with recent experimental observations of different sign changes and anomalies, as well as enhancement of thermopower, necessary for making effecicient thermoelectric materials.


## Effect of interactions on the Quantum Oscillations (QO) in Kondo insulator
Kondo insulators, such as SmB6 or YbB$x_{12}$, are found to exhibit quantum oscillations in density of states (Shubnikov deHass/SdH) and magnetization (deHass van Alphen/dHvA), even in absence of a Fermi surface. Recently, it has been shown [Panda et al] in a mean-field approach (Hybridization-gap insulators) that SdH and dHvA oscillations in such systems show different frequencies and different field and temperature-dependent amplitudes, in marked contrast with metals. Kondo insulators are, how- ever, strongly correlated systems where interaction effects cannot be a priori ignored. We generalize the periodic Anderson model with Sachdev-Ye-Kitaev (SYK)-like interactions, where the large-N limit allows us to control the calculation. We study the fate of quantum oscillations in Kondo insulators in this solvable limit. We find that the QO frequencies are not renormalized by interactions. The QO amplitudes show a remarkable difference: the dHvA amplitude is essentially unaffected by interaction, while the SdH amplitude is strongly enhanced.

## Modification of quantum criticality due to lattice vibrations
The transition between ordered and disordered phases in magnets, superfluids, charge density waves, etc., are typically studied within "static" lattice models. However, acoustic phonons are ubiquitous in realistic solid state systems, and their gapless nature can fundamentally change the standard critical behavior. Therefore, the fate of the second-order quantum phase transition in the presence of lattice vibrations is an intriguing question. We developed a renormalization group (RG) analysis near (3+1) space-time dimensions and derive the RG equations using an $\epsilon$ expansion. Our results indicate that when the number of flavors of the underlying O($N$) model exceeds a critical number $N_c=4$, the quantum transition remains second-order of the Wilson-Fisher type; while for $N\le4$, it turns to weakly first-order. We have characterized this weakly first-order transition by a length scale $\xi^*$, below which the transition changes from second-order to first-order. We are currently in the process of verifying these analytical predictions numerically, using Monte Carlo simulations of O($N$) models coupled to gapless phonons.

## MBL to ergodic transition via extremal statistics of entanglement spectra
Some interacting disordered many-body systems are unable to thermalize when the quenched disorder becomes larger than a threshold value, known as many-body localization (MBL). Many commonly-used diagnostics, such as the gap-ratio or the entanglement entropy, derived from properties of many-body eigenstates, can not track the MBL-ergodic transition accurately and are very sensitive to the system size. Instead, using the extremal statistics of entanglement eigenvalues ($\lambda_i$), denoted by $P_i(\lambda_i)$, we showed that they can characterize the MBL and ergodic phases, and also track the transition very accurately in a system size independent way. In particular, we used the following two criteria: (i) the sign change of the power-law exponent of the distribution of lowest entanglement eigenvalue $P_1(\lambda_1)$ and (ii) the vanishing of the probability of second lowest entanglement eigenvalue $P_2(\lambda_2)$ being $\ln(2)$, which can be used as an "order parameter" $p^*$ for the transition, i.e. $p^∗ = \lim_{\lambda_2\rightarrow\ln(2)^+} P_2(\lambda_2)$.
Using our new measures, we also studied the MBL-ergodic transition in presence of experimentally relevant correlated disorder. We constructed a model of correlated disorder, where both disorder and correlation can be tuned independently. Using our new measures, we showed that we can obtain the phase diagram in disorder-correlation plane by tracking the transition accurately.

## Superconductivity in ionic Hubbard model (IHM)

<p align="right">
    <img width="400" src="/images/FigIHM.jpg" alt="Material Bread logo">
</p>

The ionic Hubbard model is defined on a bipartite lattice, where, in addition to the kinetic energy and the local Hubbard repulsion terms, the fermions also feel a constant potential difference between the two sublattices (ionic potential). This model is challenging to solve in the limit when the staggered ionic potential competes with Hubbard repulsion term, opening up a window of charge fluctuations. Using a strong-coupling expansion (Schrieffer-Wolff transformation) we have derived an effective low-energy dimer-dipole Hamiltonian in this limit, and employed parton mean-field theory in presence of both double occupancy and holes to study the ground state properties of this model. Calculating of superfluid stiffness shows the appearance of a superconducting phase, which can be detected in the ultra-cold atom experiments.


{% include base_path %}


