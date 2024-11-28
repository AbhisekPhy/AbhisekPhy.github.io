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

<b> Selected Refs: </b>
<ol>
<li> <b>A. Samanta</b>, Amulya Ratnakar, Nandini Trivedi and Rajdeep Sensarma, <em>Two-particle spectral function for disordered $s$-wave superconductors: local maps and collective modes</em>, Physical Review B <b>101</b>, 024507 (2020); <a href= "https://journals.aps.org/prb/abstract/10.1103/PhysRevB.101.024507"> Link</a> </li>

<li> Bo Fan, <b>A Samanta</b>, Antonio M. Garcia-Garcia, <em>Tuning superinductors by quantum coherence effects for enhancing quantum computing</em>, Physical Review Letters <b>130</b>, 047001 (2023); <a href= "https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.130.047001"> Link</a> </li>

<li> <b>A. Samanta</b>, Itay Mangel, Amit Keren, Daniel P. Arovas, Assa Auerbach, <em>The two critical temperatures conundrum in La$_{1.83}$Sr$_{0.17}$CuO$_4$</em>, SciPost Physics <b>16</b>, 148 (2024); <a href="https://scipost.org/SciPostPhys.16.6.148"> Link </a>  </li>
</ol>

---
## Transport and thermopower properties of semimetals and interacting systems

<p align="center">
    <img width="700" src="/images/FigHall.jpg" alt="Material Bread logo">
</p>

The Hall coefficient ($R_H$) has been traditionally used to measure the charge carrier density in transport measurements, via the Drude relation $R_H\sim \frac{1}{n}$. However, this relation may break down in semimetals due to the presence of multiple bands and intriguing Fermi surface topology. Multiband conductivity calculations involve coupled Boltzmann equations with interband collision integrals which are quite challenging. To avoid this difficulty, we have developed a new formalism [Auerbach et al] where the Hall coefficient is expressed in terms of thermodynamic susceptibilities only. By using this, we calcule the deviation of $R_H$ from the Drude relation in spin-split semiconductor bands, as well as Weyl and nodal-line semimetals [<a href="https://journals.aps.org/prb/abstract/10.1103/PhysRevB.102.104201"> Samanta et al</a>]. We propose experiments to measure these deviations.

In presence of strong interactions, our formalism can calculate $R_H$ over a large range of temperatures between the antiferromagnetic interaction ($J$) and the Mott gap scales ($\sim U$). This is done by employing a high-temperature expansion of the t-J model, supplemented by Quantum Monte Carlo (QMC) simulations of the strongly interacting Hubbard model. Our calculation explains the observation of "Hall anomalies" in experiments, i.e. abrupt changes in sign and magnitude of $R_H$ in cuprates. My current research interest extends to explore the thermopower properties (Seebeck) of several multi-band models (such as kagome superconductors, Kane-Mele models), semimetals (Weyl, nodal-line) and interacting systems. These systems promise to provide an interesting playground with recent experimental observations of different sign changes and anomalies, as well as enhancement of thermopower, necessary for making effecicient thermoelectric materials.

<b> Selected Refs: </b>
<ol>
<li> <b>A. Samanta</b>, Daniel P. Arovas, Assa Auerbach, <em>Hall coefficient of semimetals</em>, Physical Review Letters <b>126</b>, 076603 (2021); <a href= "https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.126.076603"> Link </a> </li>

<li> Ilia Khait, Sauri Bhattacharyya*, <b>A. Samanta</b>*, Assa Auerbach, <em> Hall anomalies of the doped Mott insulator</em>, NPJ Quantum Materials <b>8</b>, 75 (2023); <a href= "https://www.nature.com/articles/s41535-023-00611-5"> Link </a> </li>

</ol>

---

## Superconductivity in ionic Hubbard model (IHM)

![](/images/FigIHM.jpg){: style="width: 350px; float: right; border: 10px"} The ionic Hubbard model (IHM) is defined on a bipartite lattice, where, in addition to the kinetic energy ($t$) and the local Hubbard repulsion ($U$) terms, the fermions also feel a constant potential difference between the two sublattices (ionic potential $V$). While large $U$ (Mott insulator) and large $V$ (band insulator) by themselves promote insulating behavior, they compete with each other leading to charge fluctuations when $U\sim V$. However, the model is challenging to solve in this limit where most of the conventional methods fail. In our work, we use a strong-coupling expansion (Schrieffer-Wolff transformation) and derive an effective low-energy dimer-dipole Hamiltonian in the limit $U\sim V\gg t$. Further, we employ a slave-boson (parton) mean-field theory in presence of both double occupancy (doublons) and holes (holons). We show the appearance of a novel superconducting phase with $T_c\sim t$ due to the condensation of the doublon-holon pairs – this phase can be detected in ultra-cold atom experiments.

<b> Selected Refs: </b>
<ol>
<li> <b>A. Samanta</b>, Rajdeep Sensarma, <em>Superconductivity from doublon condensation in the ionic Hubbard model</em>, Physical Review B <b>94</b>, 224517 (2016); <a href= "https://journals.aps.org/prb/abstract/10.1103/PhysRevB.94.224517"> Link </a> </li>
</ol>

---

## MBL to ergodic transition via extremal statistics of entanglement spectra
Some interacting disordered many-body systems are unable to thermalize when the quenched disorder becomes larger than a threshold value – this is known as many-body localization (MBL). Many commonly-used diagnostics, such as the gap-ratio or the entanglement entropy, are unable to track the MBL-ergodic transition accurately and are very sensitive to the system size. Instead, we use extremal statistics of entanglement eigenvalues ($\lambda_i$), and show that they can characterize the MBL and ergodic phases, and also track the transition very accurately in a system size independent way.

Using our new measures, we can also study the MBL-ergodic transition in presence of experimentally relevant correlated disorder. We provide a model of correlated disorder where both disorder ($V$) and correlation ($\alpha$) can be tuned independently. Using our new measures, we show that the MBL phase diagram can be obtained very accurately in the $V-\alpha$ plane.

<b> Selected Refs: </b>
<ol>
<li> <b>A. Samanta</b>, Kedar Damle, Rajdeep Sensarma, <em>Tracking the many-body localized to ergodic transition via extremal statistics of entanglement eigenvalues</em>, Physical Review B <b>102</b>, 104201 (2020); <a href= "https://journals.aps.org/prb/abstract/10.1103/PhysRevB.102.104201"> Link </a> </li>

<li> <b>A. Samanta</b>, Ahana Chakraborty, Rajdeep Sensarma, <em>Many-body localized to ergodic transitions in a system with correlated disorder</em>, Physical Review B <b>106</b>, L060201 (Letter) (2022); <a href= "https://journals.aps.org/prb/abstract/10.1103/PhysRevB.106.L060201"> Link</a> </li>
</ol>


## Modification of quantum criticality due to lattice vibrations
![](/images/FigON.jpg){: style="width: 350px; float: right; border: 10px"} The transition between ordered and disordered phases in magnets, superfluids, charge density waves, etc., are typically studied within "static" lattice models. However, acoustic phonons are ubiquitous in realistic solid state systems, and their gapless nature can fundamentally change the standard critical behavior. Therefore, the fate of the second-order quantum phase transition in the presence of lattice vibrations is an intriguing question. We developed a renormalization group (RG) analysis near (3+1) space-time dimensions and derive the RG equations using an $\epsilon$ expansion. Our results indicate that when the number of flavors of the underlying O($N$) model exceeds a critical number $N_c=4$, the quantum transition remains second-order of the Wilson-Fisher type; while for $N\le4$, it turns to weakly first-order. We have characterized this weakly first-order transition by a length scale $\xi^*$, below which the transition changes from second-order to first-order. We are currently in the process of verifying these analytical predictions numerically, using Monte Carlo simulations of O($N$) models coupled to gapless phonons.

<b> Selected Refs: </b>
<ol>

</ol>


## Effect of interactions on the Quantum Oscillations (QO) in Kondo insulator
Kondo insulators, such as SmB6 or YbB$x_{12}$, are found to exhibit quantum oscillations in density of states (Shubnikov deHass/SdH) and magnetization (deHass van Alphen/dHvA), even in absence of a Fermi surface. Recently, it has been shown [Panda et al] in a mean-field approach (Hybridization-gap insulators) that SdH and dHvA oscillations in such systems show different frequencies and different field and temperature-dependent amplitudes, in marked contrast with metals. Kondo insulators are, how- ever, strongly correlated systems where interaction effects cannot be a priori ignored. We generalize the periodic Anderson model with Sachdev-Ye-Kitaev (SYK)-like interactions, where the large-N limit allows us to control the calculation. We study the fate of quantum oscillations in Kondo insulators in this solvable limit. We find that the QO frequencies are not renormalized by interactions. The QO amplitudes show a remarkable difference: the dHvA amplitude is essentially unaffected by interaction, while the SdH amplitude is strongly enhanced.


{% include base_path %}


