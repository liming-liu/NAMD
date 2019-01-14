---
# NAMD in plain language

By Liming Liu

---
#### Dynamic 
Adiabatic or non-adiabatic is related to dynamics process of system evolution (mainly on how would the electronic and nuclei subsystem exchanging energy.

---
#### Adiabatic
Under minor perturbation, nuclei configuration changes little, so as the occupation eigenstates of each nuclei configuration. Most importantly, the occupation of each electronic eigenstate stays the same.

---
#### Non-adiabatic
Under violated stimulation, nuclei movies violently, the coupling between current and next time step eigenvalues mismatch, then the coupling between various depth energy levels eigenstates become magnificent. So there's probability for electron hoping among different eigenstates. aka, the occupation number of eigenstates changed.

---
#### Real Time Simulation for carrier dynamics
- Micro canonical ensembel (NVE) is isolated, volumn fixed and energy conserved. So the evolution of the system is in good approximation of real isolating system.
- Anyother?

---
#### Classical Path Approximation
- Nuclei tranjectory -> potential V_R(t) -> electrons
- electron configuration -> Hellman-Fynmann force -> nuclei
For low energy excitation of electronic system, the peturbation of nuclei configuration is tiny, using ground state AIMD trajectory to approximate.
Then there's no electron->nuclei. 

+++
Electronic configuration can be different to ground state configuration, then the syetem is not on ground state potential energy surfaces any more. Electrons relaxes then system can experience various PES. The drive force of electronic relaxation is the nuclei configuration change induced NA coupling change between current and next time step eigenstates.

---
#### Fewest Switch Surface Hoping
Hoping probability

---
#### Boltzman factor
Detail balence: At equilibrium, each elementary process should be equilibrated by its reverse process.
i->j v.s. j-i
Detailed balance ~ energy conservation
