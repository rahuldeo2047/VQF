# VQF
Variational Quantum Factoring

**Code is basically a refactoring of publicly available code (https://github.com/mstechly) by referencing papers, and other content online. The objective of the VQF project is to understand and implement Variational Quantum Factoring through a working model.**

**Referenced papers:**
* Shor, Peter W., Polynomial-time algorithms for prime factorization and discrete logarithms on a quantum computer, 1997, SIAM Journal on Computing.
* Anschuetz, Eric et al., Variational Quantum Factoring, 2019, Lecture Notes in Computer Science...
* Farhi, Edward et al., A Quantum Approximate Optimization Algorithm, 1997, SIAM Journal on Computing.

**Referenced online content:**
* https://github.com/mstechly/vqf/tree/master/vqf
* https://github.com/rigetti/pyquil/tree/master/pyquil
* https://pyquil-docs.rigetti.com

**To execute the script in Windows**
* Install pyquil by executing the following inline command in Jupyter notebook:
    - !pip install pyquil
    - !pip install --upgrade pyquil
* Post installation restart the machine 
* Run the following commands in separate command prompt screens and keep them running till you execute this script:
    - qvm -S
    - quilc -S
