# Privacy-Program - PET
# Privacy Attacks
  - linking attack
  - membership inference attack
  - local privacy poison attack 
  - model inversion attack 
  - white box access attack (secret sharer)
  - 
# Traditional PET 
# Anonymization or pseudoanonymization 
  - Redaction
  - Tokenization
  - Hashing
  - Generalization
  - k-anonymity (Homogeneity Attack, Background Knowledge Attack, NP-hard, naive algorithm is 𝑂(𝑛2))
  - ℓ-diversity, t-closeness, (α,k)-anonymity, and δ-presence
  - de-identification 
   
# Encryption 
  - Homomorphic encryption (PHE, SHE, FHE)
  - In-transit encryption
  - At rest encryption
  
# Zero Knowledge Proofs
  - prover, verifier, no information leakage
  - completeness, soundness, zero knowledgeness
  
# Trusted Execution  Environment (TEE) 
  - assured workloads, confidential computing, shielded VMs 
  
# Secure Multiparty Computing (MPC)

# Differential Privacy (numeric vs. vector)
  - Ɛ-DP:  Random Response mechanism 
  - Ɛ-DP:  Laplace mechanism 𝐹(𝑥) = 𝑓(𝑥) + Lap (𝑠/𝜖)
  - (Ɛ, 𝛿)-DP: 
    - 𝖯𝗋[𝐹(𝑥)=𝑆]≤𝑒xp(𝜖)𝖯𝗋[𝐹(𝑥′)=𝑠]+𝛿, 
      - With probability 1−𝛿, 𝖯𝗋[𝐹(𝑥)=𝑆]/𝖯𝗋[𝐹(𝑥′)=𝑠]≤𝑒xp(𝜖)
      - With probability 𝛿, we get no guarantee at all
      - 𝛿  to be very small - usually  1/𝑛**2  or less
  - Gausian mechanism  
     - 𝐹(𝑥)=𝑓(𝑥) + N(𝛿**2)
     - where 𝜎**2=2*𝑠**2*log(1.25/𝛿)/𝜖**2
     - Gaussian (normal) distribution with center 0 and variance  𝜎**2
     - the Gaussian mechanism has two major drawbacks - it requires the use of the the relaxed  (𝜖,𝛿) -differential privacy definition, and it's less accurate than the Laplace mechanism
     -  For applications in which  𝐿2  sensitivity is much lower than  𝐿1  sensitivity, the Gaussian mechansim allows adding much less noise.
  - KL Max Divergence 
  - Renyi Divergence
  
# Sensitivity
  - global sensitivity ( mechanism only)
    - the vector-valued Laplace mechanism requires the use of 𝐿1 sensitivity
    - while the vector-valued Gaussian mechanism allows the use of either 𝐿1 or 𝐿2 sensitivity
  - local sensitivity (mechanism and dataset)
  - Local sensitivity places finite bounds on the sensitivity of some functions whose global sensitivity is difficult to bound. i.e. mean()
  
# Type of Queries
  - sequential (kƐ), parallel(Ɛ), post-processing (Ɛ1+Ɛ2)
  - count, histogram, sum, mean
  
# Federated Analytics
  - TensorFlow Privacy 
  - Rényi Differential Privacy ( Gausian mechanism) 
    - (𝛼,𝜖¯)-RDP mechanism
  - Zero-Concentrated Differential Privacy 
  - Exponential Mechanism for Finite Sets
# Tools 
  - NIST Tool List https://www.nist.gov/itl/applied-cybersecurity/privacy-engineering/collaboration-space/focus-areas/de-id/tools
  - FAIR  Factors Analysis in Information Risk, inviduals 
  - NIST Privacy Risk Assessment Methodology (PRAM) : NISTIR 8062,  org privacy, cybersecurity, business, and IT personnel
   
# Readings
  - Differential Privacy: A Primer for a Non-Technical Audience
  - 
