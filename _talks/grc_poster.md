---
title: "GRC Poster and Lightning Talk"
collection: talks
type: "Poster and lightning talk"
permalink: /talks/grc_poster
venue: "Gordon Research Conference, 2026"
date: 2019-12-20
location: "Southern New Hampshire University, Manchester, New Hampshire, USA"

---
The dipolar field between the target 13C nuclei during polarization transfer from the parahydrogen singlet state is a significant problem for hyperpolarization techniques, such as Parahydrogen-Induced Polarization via Side Arm Hydrogenation (PHIP-SAH). The hyperpolarized agent concentration increases the dipolar field, which reduces the polarization transfer efficiency. It is essential to design an optimized pulse that can handle such system dynamics among all system imperfections, such as $B_{0}$ and $B_{1}$ field inhomogeneities, chemical shift dispersion, simultaneously. Unlike errors due to $B_{0}$ and $B_{1}$ field inhomogeneities and chemical-shift dispersion, the dipolar field introduces a state-dependent Hamiltonian that results in nonlinear spin dynamics. Due to the nonlinear dynamics, the conventional GRAPE algorithm converges prematurely, and it fails to achieve optimal fidelity under the state-independent Hamiltonian assumption. 

This work focuses on modifying the GRAPE algorithm to recalculate the state-adjoint gradient by consistently incorporating the state-dependent Hamiltonian, which is the dipolar field interaction. This modified GRAPE approach prevents premature convergence in the optimization without imposing any penalty on the cost function. Numerical simulations are presented for three spin systems that demonstrate improved convergence behavior over the classical GRAPE method in the presence of dipolar interactions and other system imperfections.

[Download poster](/files/sreya_poster_final_print.pdf)

[Download lightning talk](/files/lightening_talk_sreya.pdf)
