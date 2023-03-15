# Quantum Computing and Quantum Machine learning

The theoritical and experimentail research is already very well in Quantum computing but QML is still a growing research field and we know very little about it. There a hype aboout QML that it can speed up training quite well and also that quantum power can bring a huge change in machine learning algorithms but the fact is that we still don't have that much quantum resources to run our QML circuits on real quantum hardware in the near term future.

ML algorithms are growing quite well but QML's growth is questionable as due to limitations of number of qubits we can have and quantum error that prevails in the current quantum systems. As said by physicit Ryan Sweke from Free university of Berilin, Germany, "I have not seen a single piece of evidence that there exists a meaningful ML task for which it would make sense to use a quantum computer and not a classical computer,". It may true that the tasks which makes classically may not make sense in the quantum world. But the aim should not solely to make any classical algorithm to run in a quantum setting for speed gain. Making QML algorithms for exisitng ML algorithms can also be source of understanding quantum computing in general or to get insights about the classical ML algorithms and improve them. Thinking in a quantum way to solve a classical problem can become a new way for solving many unsolved problemes.

# Familiar Quantum Algorithms

I have been reading Qiskit's Textbook, Quantum computing for computer scientists by Yanofsky and Mannucci and have a solid understanding of various quantum algorithms like Grover, Simon, Shor, Brassard Hoyer Tapp (BHT) etc. QML is also new to me as I have been studying Quantum symmetric key cryptanalysis for quite a time (4 months to be precise).

I would like to explain the grover's algorithm that search's in an unsorted list of size $n$ in $O(\sqrt{n})$ beating the classical $O(n)$ time. It using the concept of amplitude amplication which amplies the amplitude of the desired state. Grover has found many applications in symmectric key cryptography[1]  as well as in machine learning[2].

# Familiar Quantum Software

Quantum libraries that I have been using for most of the time includes Qiskit[3] and ProjectQ[4]. I have also used Qsim[5] which is recently developed in India. libQuantum[6] in C is also very useful when it comes to simulating large depth circuits efficiently. I have used Cirq for the first time for QML HEP tasks. Since I was already familiar with tensorflow due to my past background in machine learning, using cirq was much easier than i thought.

I think tensorflow quantum is still in a very early phase while Qiskit has been developed quite a lot. The use of IBM simulators and real quantum hardware in Qiskit is quite appreciable. One of the advantages of Qiskit that i found over tensorflow quantum is its huge open source community which has developed quite a nice material (like qiskit's textbook and summer school).

# References
1. Wikipedia [link](https://en.wikipedia.org/wiki/Grover%27s_algorithm#Cryptography), [papers](https://ieeexplore.ieee.org/search/searchresult.jsp?action=search&newsearch=true&matchBoolean=true&queryText=(%22All%20Metadata%22:Grover)%20AND%20(%22All%20Metadata%22:Cryptanalysis)) in IEEE.
2. [A Grover-search based quantum learning scheme for classification](https://iopscience.iop.org/article/10.1088/1367-2630/abdefa).
3. [Qiskit, open source software development kit (SDK)](https://qiskit.org/).
4. [Website](https://projectq.ch/). Damian S. Steiger, Thomas Haener, and Matthias Troyer "ProjectQ: An Open Source Software Framework for Quantum Computing" Quantum 2, 49 (2018) (published on arXiv on 23 Dec 2016).
5. [QSim](https://qctoolkit.in/) QC workbench.
6. [libquantum](http://www.libquantum.de/) Hendrik Weimer.
