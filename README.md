# Privacy Program Guide
# Privacy Foundation
  - privacy (user data graph) vs. security (asset safeguards intelligence)
  - privacy/data protection in different countries (IAPP tracker)
  - regulations in different states in U.S. (IAPP tracker)
  - Regulators' expectations 
  - Consumers/users sentiment
  - Variances from different  
  - Privacy litigations and industrial impacts
# Privacy Program 
  - Compliance frameworks
      - ePprivacy, GDPR, Data Governance Act, proposed EU law from 2020
      - other 17 countries- Personal Information Protection Law (PIPL) (China)
      - Convention on Cybercrime
      - California Consumer Privacy Act (CCPA)
      - Children's Online Privacy Protection Act (COPPA)
      - EU–US Privacy Shield
      - Privacy and Electronic Communications Directive 2002
  
  - Privacy frameworks 
    - NIST 800-53 (Basic Privacy REquirements)
    - NIST IR 8062 (privacy engineering/risk factors)
    - Circular A-130 
    - ISO 27701 Privacy Information Management System
    - ISO 27018 Cloud Privacy
    - ISO/IEC 29100:2011 Information technology — Security techniques — Privacy framework

  - Privacy Process
      - Privacy Readiness Assessment
      - Privacy Engineering ( Privacy By Design (7 principles))
      - Privacy Impact Analysis 
      - Data Protection Impact Analysis
      - Common Operations: notice, consent, opt-in, opt-out, right to access/change/forget/legal, control on sales/share
      - Privacy in data process pipiline (collection, ingestion, processing, storage, archival, retention, disposal)
      - Privacy in SDLC (plan, code, test, deploy, operate, monitor)
      - Privacy in developer tools (test data, IDE, testing tools)
      - Data sharing or processing agreements
      - Data classification/inventory/retention policy
      - Automated Data Inventory
      - Breach response /Crisis management/Reporting 
      - Identity Protection/Credit monitoring
       
   - Measuring Program
      - Privacy metrics determination or tracking

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
     - the Gaussian mechanism has two major drawbacks - it requires the use of the the relaxed  (𝜖,𝛿) -differential privacy definition, and it's less accurate than the    - Laplace mechanism
     -  For applications in which  𝐿2  sensitivity is much lower than  𝐿1  sensitivity, the Gaussian mechansim allows adding much less noise.
  - KL Max Divergence, Renyi Divergence
   - RDP: Rényi Differential Privacy ( Gausian mechanism) 
    - (𝛼,𝜖¯)-RDP mechanism
  - zCDP/; Zero-Concentrated Differential Privacy 
  - Exponential Mechanism 
    - for Finite Sets
    - Report Noisy Max
  - Sparse Vector Mechanism (threshold, range queries)
  - ML Privacy (gradient descent)
  - Emprical risk minimization (ERM) 
    - Bayesian noise 
  - Local DP
    - Randomized Response
    - Unary Coding 
  - Synthetic Data 
  
# Sensitivity 
  - global sensitivity ( mechanism only)
    - the vector-valued Laplace mechanism requires the use of 𝐿1 sensitivity
    - while the vector-valued Gaussian mechanism allows the use of either 𝐿1 or 𝐿2 sensitivity
  - local sensitivity (mechanism and dataset)
  - Local sensitivity places finite bounds on the sensitivity of some functions whose global sensitivity is difficult to bound. i.e. mean()
# Upper and Lower Bounds

# Type of Queries
  - sequential (kƐ), parallel(Ɛ), post-processing (Ɛ1+Ɛ2)
  - count, histogram, sum, mean
  
# Federated Analytics

# Tools 
  - NIST Tool List https://www.nist.gov/itl/applied-cybersecurity/privacy-engineering/collaboration-space/focus-areas/de-id/tools
  - FAIR  Factors Analysis in Information Risk, inviduals 
  - NIST Privacy Risk Assessment Methodology (PRAM) : NISTIR 8062,  org privacy, cybersecurity, business, and IT personnel
   
# Readings
  - Differential Privacy: A Primer for a Non-Technical Audience
  - 
