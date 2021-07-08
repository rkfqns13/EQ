# EQ

EQ project team repository

- [2021 양자정보경진대회](http://www.qcenter.kr/bbs/board.php?tbl=bbs51&mode=VIEW&num=15&category=&findType=&findWord=&sort1=&sort2=&it_id=&shop_flag=&mobile_flag=&page=1)
- [Hackaton Github](https://github.com/qiskit-community/quantum-hackathon-korea-21)

# Knapsack Problem
Knapsack problem is a constrained combinatorial optimization problem that refers to the general problem of packing a knapsack with the most valuable items without
exceeding its weight limit. To sum up, it is a NP-complete problem that finds high values within a limited weight.

For example, let’s assume that there are 4 items. 
[value, weight]
item 1 = [120, 13]
item 2 = [54, 6]
item 3 = [28, 15]
item 4 = [49, 9]
If the max weight is 32, this knapsack problem answer is to pick first, second, and last items. The max value is 223.

# Knapsack Problem with VQE
Variational Quantum Eigensolver algorithm(VQE) is a hybrid algorithm that uses a variational technique and interleaves quantum and classical computations in order to find the minimum eigenvalue of the Hamiltonian H of a given system. VQE is suitable for noisy intermediate scale quantum computation.
The process of solving the knapsack problem with VQE is as follows.
1) Make pauli list
2) Make matrix with values
3) Calculate the coefficient Weights * Values
4) Append the matrix and coefficient in pauli list
5) Make VQE algorithms
6) Run the VQE algorithm and extract the highest freqquency shot

# Knapsack Problem with QAOA
Quantum Approximate Optimization Algorithm(QAOA) is a general technique that can be used to find approximate solutions to combinatorial optimization problems, in
particular problems that can be cast as searching for an optimal bitstring.
The process of solving the knapsack problem with QAOA is as follows.
1) Make the graph
2) Grid search for the minimizing variables
3) Make a quantum circuit
4) Apply hadamard gates to all qubits
5) Run the QAOA algorithm
6) Extract the highest frequency shot

# Members
 - @rkfqns13 - Slack: `@Juon Kim` email: `kimjuon77@naver.com`
 
# GitHub repo
https://github.com/rkfqns13/EQ
