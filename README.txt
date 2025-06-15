This notebook two quantum state preparation functions using SELECT and SELECTSWAP ROM. 
QSP_select and QSP_select swap take in as input: 

- an integer n
- a vector in C^{2^n}
- an integer b representing the precision

and outputs a Qiskit circuit implementing quantum state preparation. 

The Jupyter notebook also includes explanations and examples of function for both the 
ROM and the QSP.
To view the notebook, run each cell in order to compile all functions and explore all
included test cases. 