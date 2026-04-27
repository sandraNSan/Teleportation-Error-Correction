<h1>TEC: Enhanced Error Correction for Noisy Teleported States under the Depolarising Noise Model</h1>

<h2>Abstract</h2>

Quantum teleportation is susceptible to noise and decoherence, causing transferred
states to no longer be true representatives of the original quantum information. 
We study a teleportation based error-correction (TEC) technique
using three-qubit repetition codes and stabilisers to protect the quantum information during 
the teleportation process. The density matrix simulations
are performed in Qiskit, where we compare the baseline teleportation protocol to TEC 
both with and without corrections on the stabiliser measure-
ments. Under depolarising noise, TEC reduces the logical error rates up 
to 64% compared with the baseline, whereas uncorrected stabilisers are shown
to degrade the fidelity of the fully optimised TEC implementation. This is
also demonstrated with the time evolution of the Lindblad equation to extend the analysis 
to hardware noise, where prolonged circuit duration exposes
qubits to greater environmental decoherence. The results determine TEC as
a practical tool for improving the fidelity, and therefore reduce logical errors
in quantum communications subject to noise.
