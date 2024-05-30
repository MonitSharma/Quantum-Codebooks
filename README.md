[←←Back to Homepage](https://monitsharma.github.io/)

# Quantum Computing Resources

Welcome to this repository, which contains comprehensive solutions and walkthroughs for various popular quantum computing packages and platforms. Quantum computing is a rapidly growing field that has the potential to revolutionize a wide range of industries, from finance and healthcare to logistics and machine learning. 

The packages and platforms that are covered in this repository include:

( medium articles will be added soon) 



# Table
- [Xanadu Codebook](#xanadu-codebook)
- [Qiskit Textbook](#qiskit-textbook)
- [QuTip Codebook](#qutip-codebook)
- [Google Cirq](#google-cirq)
- [Microsoft Q#](#microsoft-q)



# Contents

The repository is organized by resource, with each resource having its own subdirectory containing the solutions and walkthroughs. The subdirectories are named after the specific quantum computing package or platform and contain detailed explanations and examples of how to use it. The repository will be regularly updated with new solutions and walkthroughs as new quantum computing packages and platforms are released.


## Xanadu Codebook

- [Xanadu](https://xanadu.ai/): Xanadu is a leading company in the field of quantum computing, providing a full-stack platform for quantum software development. Their platform, "Strawberry Fields" is a powerful tool for creating and running quantum algorithms. It provides a high-level interface for working with quantum systems, making it easy to create and run quantum circuits on real quantum hardware.

### Introduction

This folder contains solutions to the [introductory module of the Xanadu Quantum Codebook](https://github.com/MonitSharma/Quantum-Codebooks/tree/main/Xanadu-Codebook-Solutions/Introduction). The solutions are written in python and aim to provide a solid understanding of the concepts of quantum computing.




### Algorithms

[Introduction to quantum Algorithms](https://github.com/MonitSharma/Quantum-Codebooks/tree/main/Xanadu-Codebook-Solutions/Algorithms)
   





### Fourier

[In this node](https://github.com/MonitSharma/Quantum-Codebooks/tree/main/Xanadu-Codebook-Solutions/Quantum%20Fourier%20Transform), we will change gears and discuss the basics of the classical Discrete Fourier transform (DFT), which has made a significant impact in the field of signal processing for transforming data from the time domain to the frequency domain and back. The DFT is a unitary transformation, which makes it a good candidate for quantum computers




### Quantum Phase Estimation

[In this module](https://github.com/MonitSharma/Quantum-Codebooks/tree/main/Xanadu-Codebook-Solutions/Phase%20Estimation) we are going to learn about an algorithm that helps us estimate the eigenvalue of a given unitary operator. The eigenvectors of a unitary operator form an orthonormal basis set. Applying the unitary operator on one of its eigenvectors multiplies it by a global phase (the eigenvalue). For unitary operators, the eigenvalues have magnitude and can be written in the form , where is called the eigenphase corresponding to the eigenvalue.






### Shor's algorithm
[Working on Shor's algorithm.](https://github.com/MonitSharma/Quantum-Codebooks/tree/main/Xanadu-Codebook-Solutions/Shor)
Modular arithmetic is a fundamental concept of basic mathematics. We say that two integers are equivalent modulo if the difference between them is a multiple of , that is, there exists an integer such that . In order to understand this type of equivalence it is common to work with a "clock"-like picture, which will have hours instead of . We will say that two numbers are equivalent if they mark the same hour on the clock.




### G, Grover's algorithm

[In module A](https://github.com/MonitSharma/Quantum-Codebooks/tree/main/Xanadu-Codebook-Solutions/Grover), we sped up the lock-breaking process by testing states in pairs. This told us when the solution was present, but not which state it was. Our goal now will be to try and figure out the state directly, and our broad strategy will be to start in the uniform superposition and somehow "pump" amplitude from the other states into , so that we measure the solution with high probability. This strategy is called amplitude amplification. Let's start by exploring what happens to amplitudes when we apply the oracle.






### H, Hamiltonian simulation
[In this module, we'll learn about Hamiltonian Simulations.](https://github.com/MonitSharma/Quantum-Codebooks/tree/main/Xanadu-Codebook-Solutions/Hamiltonians)
Fundamentally, quantum computing is different from classical computing because of the physical laws working "under the hood" of the computer. To understand quantum computing in this light, it's useful to treat Nature as a sort of black box. It takes an initial condition as an input, evolves it using physical laws, and outputs experimental data (aka measurements) at the end. We can try to infer the laws of Nature from looking at the pattern of input conditions and output measurements.





### E, Error Correction


[Introduction to Error Correction](https://github.com/MonitSharma/Quantum-Codebooks/tree/main/Xanadu-Codebook-Solutions/Error%20Correction)







## Qiskit Textbook

- [Qiskit](https://qiskit.org/): Qiskit is an open-source quantum computing framework that allows users to create, manipulate, and execute quantum programs. It is built on top of popular open-source libraries such as NumPy and Scipy, making it easy for users to get started with quantum computing. With Qiskit, users can build and run quantum programs on a local simulator or on real quantum hardware.

   
### Prerequisites

Learn about the software used to write the Qiskit (Python and Jupyter Notebooks), and set up your environment to reproduce the experiments.

| Serial Number | Title                                     | Links     | Medium                                                                                |
| ------------- | --------------------------------------------------- | ----------------------------------------------------------------------------------------- |------------------------------------|
| 1             | Checking versions and installing  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Quantum-Computing-with-Qiskit-and-IBMQ/blob/main/Installing%20Qiskit%20and%20Dependancies.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/learn-quantum-computing-with-qiskit-the-beginning-a177b588df88) |
| 2             | Complex Arithmetic    |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Quantum-Computing-with-Qiskit-and-IBMQ/blob/main/ComplexArithmetic.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/learn-quantum-computing-with-qiskit-complex-arithmetic-453d5f15638b) |
| 3             |  A very basic intro to Linear Algebra | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Quantum-Computing-with-Qiskit-and-IBMQ/blob/main/Linear%20Algebra%20Background.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/learn-quantum-computing-with-qiskit-linear-algebra-501587c3297d) |



### Quantum States and Qubits

This chapter introduces the computing concepts that we'll explore in later chapters, then introduces basic quantum concepts.





| Serial Number | Title                                     | Links     | Medium                                                                                |
| ------------- | --------------------------------------------------- | ----------------------------------------------------------------------------------------- |------------------------------------|
| 1             | Atoms of Computation  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Quantum-Computing-with-Qiskit-and-IBMQ/blob/main/Atoms_of_Computation.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/learn-quantum-computing-with-qiskit-atoms-of-computation-463eb0a038aa) |
| 2             | Representing Qubit States | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Quantum-Computing-with-Qiskit-and-IBMQ/blob/main/Represenitng_Qubit_States.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/learn-quantum-computing-with-qiskit-representing-qubit-state-aed033b612d0) |
| 3             | Single Qubit Gates | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Learn-Quantum-Computing-with-Qiskit/blob/main/Single_Qubit_Gates.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/learn-quantum-computing-with-qiskit-single-qubit-gates-17a5a419ed7c) |



### Multiple Qubits and Entanglement

With the basics down, this chapter explores the consequences of these new quantum effects, and sets us up with tools to understand quantum algorithms.





| Serial Number | Title                                     | Links     | Medium                                                                                |
| ------------- | --------------------------------------------------- | ----------------------------------------------------------------------------------------- |------------------------------------|
| 1             |Multiple Qubits and Entanglement  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Learn-Quantum-Computing-with-Qiskit/blob/main/Multiple_Qubits_and_Entanglement.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/learn-quantum-computing-with-qiskit-multiple-qubits-and-entanglement-39b8ffa9b95d) |
| 2             |Phase Kickback  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Learn-Quantum-Computing-with-Qiskit/blob/main/Phase_Kickback.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/computational-linear-algebra-scalars-vectors-matrices-and-tensors-50e392df9ccc) |
| 3            |Basic Circuit Identities  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Learn-Quantum-Computing-with-Qiskit/blob/main/Basic_Circuit_Identities.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/computational-linear-algebra-scalars-vectors-matrices-and-tensors-50e392df9ccc) |







### Quantum Protocols and Quantum Algorithms

In this chapter, we use quantum effects to build powerful algorithms, starting from simple proof-of-concept algorithms, through to Shor's famous factoring algorithm (and beyond).




| Serial Number | Title                                     | Links     | Medium                                                                                |
| ------------- | --------------------------------------------------- | ----------------------------------------------------------------------------------------- |------------------------------------|
| 1             | Quantum Circuits  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Learn-Quantum-Computing-with-Qiskit/blob/main/Quantum_Circuits.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/learn-quantum-computing-with-qiskit-quantum-circuit-8f07571a23f6) |
| 2             | Deutsch Jozsa Algorithm  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Learn-Quantum-Computing-with-Qiskit/blob/main/Deutsch_Jozsa_Algorithm.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/learn-quantum-computing-with-qiskit-deutsch-jozsa-algorithm-3f9bedee8f9d) |
| 3             | Bernstein-Vazirani Algorithm  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Learn-Quantum-Computing-with-Qiskit/blob/main/Bernstein_Vazirani_Algorithm.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/learn-quantum-computing-with-qiskit-bernstein-vazirani-algorithm-fa1300517624) |
| 4             | Simons Algorithm  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Learn-Quantum-Computing-with-Qiskit/blob/main/Simons_Algorithm.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/learn-quantum-computing-with-qiskit-simons-algorithm-8525adecd091) |
| 5             | Quantum Fourier Transform  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Learn-Quantum-Computing-with-Qiskit/blob/main/Quantum_Fourier_Transform.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/learn-quantum-computing-with-qiskit-quantum-fourier-transform-e27176c8f378) |
| 6             | Quantum Phase Estimation  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Learn-Quantum-Computing-with-Qiskit/blob/main/Quantum_Phase_Estimatoin.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/learn-quantum-computing-with-qiskit-quantum-phase-estimation-9c64c59c074c) |




### Investigating Quantum Hardware Using Microwave Pulses

In this chapter, we get a level closer to the real quantum machines. Learn about the physics of these devices, and how to program them at the level of microwave pulses.





| Serial Number | Title                                     | Links     | Medium                                                                                |
| ------------- | --------------------------------------------------- | ----------------------------------------------------------------------------------------- |------------------------------------|
| 1             | TBA  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Quantum-Computing-with-Qiskit-and-IBMQ/blob/main/Atoms_of_Computation.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/computational-linear-algebra-scalars-vectors-matrices-and-tensors-50e392df9ccc) |





### Quantum Algorithms for Applications


If algorithms are the solution, then what is the problem? In this chapter, we look at how we can take general algorithms and apply them to more specific situations.





| Serial Number | Title                                     | Links     | Medium                                                                                |
| ------------- | --------------------------------------------------- | ----------------------------------------------------------------------------------------- |------------------------------------|
| 1             | TBA  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Quantum-Computing-with-Qiskit-and-IBMQ/blob/main/Atoms_of_Computation.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/computational-linear-algebra-scalars-vectors-matrices-and-tensors-50e392df9ccc) |




### Investigating Quantum Hardware Using Quantum Circuits

All circuit-based quantum devices share some similar characteristics and challenges. In this chapter, we explore how quantum circuits perform on modern quantum computers, and ways to improve performance.




| Serial Number | Title                                     | Links     | Medium                                                                                |
| ------------- | --------------------------------------------------- | ----------------------------------------------------------------------------------------- |------------------------------------|
| 1             | TBA  |  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Quantum-Computing-with-Qiskit-and-IBMQ/blob/main/Atoms_of_Computation.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/computational-linear-algebra-scalars-vectors-matrices-and-tensors-50e392df9ccc) |


















## QuTiP Codebook


- [QuTiP](http://qutip.org/): QuTiP is an open-source quantum mechanics and optics framework that allows users to simulate the dynamics of open quantum systems. It is built on top of the popular Python numerical library NumPy, and provides a high-level interface for working with quantum systems. QuTiP is particularly useful for simulating the dynamics of open quantum systems and for analyzing the results of quantum experiments.


### Visualizations
   
| Serial Number | Title                                     | Description                                         | Links     | Medium                                                                                |
| ------------- | ----------------------------------------- | --------------------------------------------------- | ----------------------------------------------------------------------------------------- |------------------------------------|
| 1             | Bloch Sphere Animation    | Introduction to basic concepts in linear algebra    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Quantum-Codebooks/blob/main/QuTiP%20Codebooks/Visualizations/Bloch_Sphere_Animation.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/computational-linear-algebra-scalars-vectors-matrices-and-tensors-50e392df9ccc) |





## Google Cirq




- [Cirq](https://github.com/quantumlib/Cirq): Cirq is an open-source framework for creating, editing, and invoking Noisy Intermediate Scale Quantum (NISQ) circuits. It is designed to be easy to use, with a simple and intuitive syntax, and it is compatible with a wide range of quantum hardware platforms. With Cirq, users can easily create and run quantum circuits on real quantum hardware and analyze the results.


| Serial Number | Title                                     | Description                                         | Links     | Medium                                                                                |
| ------------- | ----------------------------------------- | --------------------------------------------------- | ----------------------------------------------------------------------------------------- |------------------------------------|
| 1             | Scalars, vectors, matrices and tensors    | Introduction to basic concepts in linear algebra    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Numerical-Linear-Algebra/blob/main/Basic%20Numerical%20Linear%20Algebra/1-Scalars%2C_Vectors%2C_Matrices_and_Tensors.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/computational-linear-algebra-scalars-vectors-matrices-and-tensors-50e392df9ccc) |





## Microsoft Q#

- [Microsoft Q#](https://docs.microsoft.com/en-us/quantum/language/): Microsoft Q# is a domain-specific programming language used for expressing quantum algorithms. It is designed to be used in conjunction with the Microsoft Quantum Development Kit, a set of tools that allows developers to create, test, and run quantum programs on a local machine or in the cloud. Q# is designed to be easy to learn for developers with experience in classical programming, and it provides a wide range of libraries and functionality for working with quantum systems.


| Serial Number | Title                                     | Description                                         | Links     | Medium                                                                                |
| ------------- | ----------------------------------------- | --------------------------------------------------- | ----------------------------------------------------------------------------------------- |------------------------------------|
| 1             | Scalars, vectors, matrices and tensors    | Introduction to basic concepts in linear algebra    | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/MonitSharma/Numerical-Linear-Algebra/blob/main/Basic%20Numerical%20Linear%20Algebra/1-Scalars%2C_Vectors%2C_Matrices_and_Tensors.ipynb) |  [![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@_monitsharma/computational-linear-algebra-scalars-vectors-matrices-and-tensors-50e392df9ccc) |





# Getting Started

To use this repository, simply clone it to your local machine using the following command:

```python
git clone https://github.com/MonitSharma/Quantum-Codebooks.git
```
      
      







## Contributing

If you would like to contribute to this repository, please submit a pull request. We welcome any additions or improvements to the existing solutions and walkthroughs. We are also open to suggestions for new quantum computing packages and platforms that should be covered in this repository.

## Contact

If you have any questions or issues with this repository, please don't hesitate to reach out to us by opening an issue on this repository or contact us via email.

The repository is designed to be a valuable resource for anyone interested in learning about quantum computing and working with quantum computing packages and platforms. Whether you are a quantum computing researcher, a developer looking to build quantum applications, or just someone interested in learning more about quantum computing, this repository has something for you.

We encourage you to explore the solutions and walkthroughs provided in this repository and try them out for yourself. With the resources provided in this repository, you will have everything you need to start working with quantum computing packages and platforms and building your own quantum applications.

Thank you for visiting this repository and we hope you find it useful in your journey to learn about quantum computing.
