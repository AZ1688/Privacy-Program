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

# Differential Privacy 
  - Ɛ-DP:  Random Response mechanism 
  - Ɛ-DP:  Laplace mechanism 𝐹(𝑥) = 𝑓(𝑥) + Lap (𝑠/𝜖)
  - (Ɛ, 𝛿)-DP: Gausian mechanism  
    - 𝖯𝗋[𝐹(𝑥)=𝑆]≤𝑒xp(𝜖)𝖯𝗋[𝐹(𝑥′)=𝑠]+𝛿, 
      - With probability 1−𝛿, 𝖯𝗋[𝐹(𝑥)=𝑆]/𝖯𝗋[𝐹(𝑥′)=𝑠]≤𝑒𝜖 
      - With probability 𝛿, we get no guarantee at all
      - 𝛿  to be very small - usually  1/𝑛(2)  or less
  - Renyi Mechanism
# Type of Queries
  - sequential (kƐ), parallel(Ɛ), post-processing (Ɛ1+Ɛ2)
  - count, histogram
# Federated Analytics
  - TensorFlow Privacy 

# Tools 
  - NIST Tool List https://www.nist.gov/itl/applied-cybersecurity/privacy-engineering/collaboration-space/focus-areas/de-id/tools
  - FAIR  Factors Analysis in Information Risk, inviduals 
  - NIST Privacy Risk Assessment Methodology (PRAM) : NISTIR 8062,  org privacy, cybersecurity, business, and IT personnel
  - 
# Readings
  - Differential Privacy: A Primer for a Non-Technical Audience
  - 
