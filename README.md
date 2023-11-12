# Linux-Assignment

This is my submission for Linux assignment, My work is on **Quantum Machine Learning**. Where I briefly explain how we use Quantum Variational Circuits(VQC's) to devolop machine learning models.

### Description 
The basic idea behind quantum machine learning is to leverage the unique properties of quantum systems, such as superposition and entanglement, to perform certain computational tasks more efficiently than classical methods.

Here's a brief overview of how quantum machine learning works:
1. **Quantum Bits (Qubits)**: Information is processed in classical computing using bits that can be either 0 or 1. Quantum bits, or qubits, are used in quantum computing and can exist in a superposition of states (0, 1, or any combination). This enables quantum computers to simultaneously represent and process a substantially bigger range of possibilities.
2. **Quantum Gates and Circuits**:Quantum gates, which manipulate the states of qubits, represent quantum operations. Quantum circuits are built by linking these gates in specified ways. These circuits can carry out complicated operations on quantum states, perhaps surpassing classical algorithms in some cases.
3. **Quantum Variational Circuits (QVC)**: Quantum variational circuits are a subset of quantum circuits that are employed in quantum machine learning. They use parameterized quantum circuits with changeable gate parameters. These circuits are used in optimisation tasks, allowing the algorithm to alter the parameters iteratively to minimise a cost function.
4. **Quantum Speedup**: Quantum machine learning algorithms try to tackle specific problems more efficiently than conventional algorithms by leveraging the parallelism given by superposition and the optimisation capabilities of quantum variational circuits. Solving linear algebra issues, completing pattern recognition tasks, and optimising large-scale problems are some examples.

we use quantum variational circuits because:
Quantum variational circuits provide a flexible ansatz or parameterized structure for approximating complex quantum states. The parameters of these circuits are optimised to discover the best approximation to a specific problem's solution. Quantum variational circuits are frequently used in quantum algorithms for optimisation tasks, such as determining the lowest or maximum of a cost function. In a quantum situation, variational circuits enable the study of a wide solution space, and the optimisation process can be more efficient.

### Here is how a Quantum Machine Learning model architecture typically looks like

![image](https://github.com/Userfound404/Linux-Assignment/assets/97509220/324eb83d-7e30-4b9c-9c7a-6d9863e88fc4)
<br>

references - [IBM Qiskit](https://learn.qiskit.org/course/machine-learning/introduction)
