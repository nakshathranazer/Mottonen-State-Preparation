# Mottonen-State-Preparation
 Mottonen State  Preparation on Qiskit


Problem Statement :
Task 3 Mottonen state preparation
Implement the Mottonen state preparation of any dataset you have for at most one 8-element vector.

def state_prep(Optional[list,array]: input_vector): <br> “”” input_vector: List, array that contain float values of size 2^n Return the mottomen state preparation of the input_vector “””
 


#use a framework that works with quantum circuits, qiskit, cirq, pennylane, etc. 

#define a quantum circuit to convert the vector in a quantum circuit.

#define the Mottonen state.


Basic Idea from the paper https://arxiv.org/pdf/quant-ph/0407010.pdf

"We begin from the transformation which equalizes the phases of the
elements of the input vector |a>and rotates it to the direction of the basis vector |e>. In the next phase the absolutevalues of elements of the target vector |b> are generated and finally the phases are adjusted to match of those of |b>."

In principle, the  transformation from an n-qubit quantum state |a> into the desired one |b> is implemented.



