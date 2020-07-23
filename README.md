# Qiskit Quantum Computing
* The following repository contains a Google colaboratory notebook that runs quantum circuits on the IBM quantum computing platform.

* Following concepts are covered in the script :
    1. Circuit creation & visualization using Qiskit Framework.Gates such as Pauli's Wolfgang, CNOT & Hadamard Gates are explored.
    
    ![Quantum Circuit](https://github.com/vedrocks15/Qiskit_Quantum/blob/master/Screenshot%202020-07-23%20at%208.18.08%20AM.png)
    
    2. Using Reverse Bell circuit the concept of superdense coding & quantum teleportation is implemented.
    
    3. Circuits are visualized using matplotlib inline magic function.
    
    4. All the circuits are run on IBMQ computers across various locations in the world & the script ensures that Quantum Computer contains appropriate number of Qubits to run the circuit & also the script finds the Quantum Computer with least waiting time.
    
    5. The circuits are samples at various "shots" to see varying probability histograms & also the noise induced in the measurements since we are making use of NISQ ( Near intermediate scale Quantum ) processors.
    
    6. Lastly the script uses IBM qasm & state vector simulation to see final collapsed measurement & superposition state as a BLoC sphere respectively.
    ![BLoC Sphere](https://github.com/vedrocks15/Qiskit_Quantum/blob/master/Screenshot%202020-07-23%20at%208.19.02%20AM.png)
