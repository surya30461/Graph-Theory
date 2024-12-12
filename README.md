# Digital Signatures and Quantum Cryptanalysis
This project explores digital signature schemes and their robustness against quantum cryptanalysis using simulated attacks such as Grover's and Shor's algorithms. It includes theoretical explanations, implementation details, and results from the simulations.

Features
Digital Signature Verification:

Implements and verifies a digital signature scheme.
Provides hash verification and eigenvalue computations for validation.
Grover's Attack Simulation:

Demonstrates quantum speedup in searching possible preimages.
Simulates Grover's attack and determines its success.
Shor's Attack Simulation:

Attempts factorization-based cryptanalysis of the signature system.
Provides results on the eigenvalue analysis and attack success.
Results Summary
Signature Validation: The implemented signature was successfully validated.
Grover's Attack:
Simulated a quantum search for possible preimages.
Attack Success: True
Possible preimages after reduction: 4.472
Shor's Attack:
Simulated quantum factorization but did not succeed in breaking the scheme.
Attack Success: False
Dependencies
Python (Version >= 3.8)
Libraries:
NumPy
Matplotlib
Any other library mentioned in the notebook
Usage
Clone the repository:
bash
Copy code
git clone <repository_url>
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Open the Jupyter Notebook:
bash
Copy code
jupyter notebook Digital_Signatures_Final.ipynb
Run the notebook cells sequentially to explore the implementation and results.
Future Work
Enhance simulations with optimized algorithms for Grover's and Shor's attacks.
Extend to other cryptographic primitives for a broader analysis.
Evaluate against hybrid classical-quantum schemes.
Acknowledgements
This project draws on theoretical insights from quantum computing and cryptographic security.
