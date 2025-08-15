---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 10

title: Research
subtitle:


design:
  columns: '1'
---

Our group studies how **structure and symmetry** enable robust quantum information processing and precision sensing. Current themes include:

## Quantum Error Correction & Codes
We are interested in new kinds of codes e.g. bosonic codes, we design and analyze codes that suppress realistic noise while remaining hardware-aware. See e.g.
- [Quantum computing with rotation-symmetric bosonic codes (PRX, 2020)](https://doi.org/10.1103/PhysRevX.10.011058)  


## Novel Qubits and Circuits
We explore protected and engineered‑spectrum qubits (e.g., 0–π‑like circuits), mapping design space to stability, control, and readout.  And we have developed an enumeration framework to systematically catalogue superconducting qubit circuit designs, mapping their parameters to performance and stability characteristics. See e.g.
- [Enumeration of all superconducting circuits up to 5 nodes](https://arxiv.org/abs/2410.18497)  


## Quantum Measurement & Amplification
We study the fundamentals and applications of measurement in quantum systems, including backaction, weak measurement, and near-quantum-limited amplification for fast, high-fidelity control and sensing.  See e.g. [Quantum limits on phase-preserving linear amplifiers
 (PRA, 2012)](https://arxiv.org/abs/1208.5174). Two key interest are **developing new kinds of amplifiers** and  
**new kinds of quantum measurements**.  Recent examples of these are
- [Quantum limits on noise for a class of nonlinear amplifiers (2021)](https://arxiv.org/abs/2010.13851)  
- [Homodyne measurement with a Schrödinger cat state as a local oscillator (2022)](https://arxiv.org/abs/2207.10210)  


## Quantum Metrology
I have a long-standing interest in pushing the limits of parameter estimation. My work began with atomic interferometry (2005) and has since spanned:  Probabilistic metrology, Nonlinear metrology, and error corrected metrology. I recently became involved in the field of frequency combs through a rewarding collaboration with Scott Diddams and Jérôme Genest.

  
 ## Light–Matter Interaction with Nonclassical Light
We explore how quantum states of light—such as single photons and squeezed light—interact with atoms and other quantum systems. The interaction of matter with classical light (thermal or coherent/laser light) is well understood. Replacing the light with nonclassical states often produces non-Markovian dynamics and far richer physics. Understanding these interactions is key to advancing quantum communication, precision sensing, and technologies that use light as “flying qubits” to connect quantum devices. This has been a long-standing collaboration with Ben Baragiola and Jonathan Gross see e.g.
- [N-Photon wave packets interacting with an arbitrary quantum system (PRA, 2012)](https://doi.org/10.1103/PhysRevA.86.013811), 
- [Quantum trajectories for propagating Fock states (PRA 2017)](https://doi.org/10.1103/PhysRevA.96.023819)
- [Master equations and quantum trajectories for (narrowband) squeezed wave packets](https://doi.org/10.1103/PhysRevA.105.023721).


## Rapid Purification & Rapid Measurement
During my PhD, Kurt Jacobs, Howard Wiseman, and I developed feedback protocols that use continuous weak measurement and feedback to accelerate either information gain or entropy removal from a quantum system. We quantify the advantage over no-feedback strategies with a speedup factor $S$. These protocols fall into two broad classes:  

**Rapid measurement** protocols aim to minimize the time needed to determine a measurement outcome with high confidence. They also increase purity, making them a subset of rapid purification.   See e.g.
- [Rapid Measurement of Quantum Systems Using Feedback Control (PRL 2008)](https://doi.org/10.1103/PhysRevLett.100.160503) — showed that feedback can speed up measuring a qudit by a factor of $d^2$ and a register of $n$ qubits by a factor of $O(n)$.

**Rapid purification** protocols are designed to drive an initially mixed state to a pure state as quickly as possible. They achieve near-deterministic performance by measuring in an unbiased basis, but cannot perform readout and thus are not rapid measurement schemes.  Two key papers in this area:  
- [Rapid State Reduction of Quantum Systems Using Feedback Control (PRL 2006)](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.92.223602) — proved purification of a qudit can be sped up by at least $O(d)$.  
- [Rapid Purification of Quantum Systems by Measuring in a Feedback-Controlled Basis (PRL 2005)](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.94.010401) — proved the purification speedup is bounded by $O(d) \le S \le O(d^2)$.


