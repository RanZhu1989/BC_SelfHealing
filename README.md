# Reproduced Code for Paper "Hybrid Imitation Learning for Real-Time Service Restoration in Resilient Distribution Systems"

This repository contains the reproduced code for the paper titled "Hybrid Imitation Learning for Real-Time Service Restoration in Resilient Distribution Systems". The original code was obtained from the authors' publication or official code repository (https://github.com/whoiszyc/IntelliHealer), and I have made modifications to make it runnable.

---

## Installation
To install the required packages mentioned in the table and configure the solvers, please follow the instructions below:
###  Prerequisites
* Python 3.6+
* Solver: Install the solver of your choice. I have already tested the CPLEX (version 12.8-12.10) and Gurobi (version 9.0-10.0) solvers and found them to be compatible.

### Required Packages
Install the required Python packages in the table below.
* numpy, pandas, scipy, sympy
* pyomo
* gym<0.26 (version 0.18 is tested)
* tensorflow v1 (version 1.14 is tested)
* keras==2.3.0
* stable-baselines3
* networkx
* shimmy

### Solver API
Please note that you are not limited to CPLEX or Gurobi. You can choose and install any other solver you prefer, following their respective installation instructions.

If you choose to use CPLEX as an example, follow these steps:

* Navigate to the CPLEX installation directory, for example, C:\Program Files\IBM\ILOG\CPLEX_Studio1210\cplex\python\3.7\x64_win64.

* Run "python setup.py install" to install the Python API:

Test the solver configuration by running the "pyomo_test.py" included in the project. This will ensure that the solver is properly installed and configured.

### Package Installation
Nivigate to the two packages directory ("package_algorithms" and "package_env") and run "pip install -e .". 

## Acknowledgments
Thank the authors of the original paper for providing valuable research and code. If there are other contributors who have helped with your reproduction work, express your gratitude and mention their contributions here.