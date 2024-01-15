# Simulation Based Inference of BNS Kilonova Properties: A Case Study with AT2017gfo
Amortized Neural Posterior Estimation - Kilonova modelling 


Kilonovae are a class of astronomical transients observed as counterparts to mergers of compact binary systems, such as a binary neutron star (BNS) or black
hole-neutron star (BHNS) inspirals. They serve as probes for heavy-element nucleosynthesis in astrophysical environments, while together with gravitational wave
emission constraining the distance to the merger itself, they can place constraints
on the Hubble constant. Obtaining the physical parameters (e.g. ejecta mass,
velocity, composition) of a kilonova from observations is a complex inverse problem, usually tackled by sampling-based inference methods such as Markov-chain
Monte Carlo (MCMC) or nested sampling techniques. These methods often rely
on computing approximate likelihoods, since a full simulation of compact object
mergers involve expensive computations such as integrals, the calculation of likelihood of the observed data given parameters can become intractable, rendering
the likelihood-based inference approaches inapplicable. We propose here to use
Simulation-based Inference (SBI) techniques to infer the physical parameters of
BNS kilonovae from their spectra, using simulations produced with KilonovaNet.
Our model uses Amortized Neural Posterior Estimation (ANPE) together with an
embedding neural network to accurately predict posterior distributions from simulated spectra. We further test our model with real observations from AT 2017gfo,
the only kilonova with multi-messenger data, and show that our estimates agree
with previous likelihood-based approaches.


Machine Learning and the Physical Sciences Workshop, NeurIPS 2023.
