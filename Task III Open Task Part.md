# Quantum Computing and Quantum Machine learning

Theoretical and experimental research on quantum computing is already quite advanced, but our understanding of QML is still relatively limited. The excitement around QML suggests that it can significantly speed up training and modify machine learning methods, but the reality is that we currently lack enough quantum resources to run our QML circuits on actual quantum hardware in the near future.

Due to our ability to only have a certain amount of qubits and the quantum inaccuracy that exists in present quantum systems, the evolution of QML algorithms is less certain than that of ML algorithms. A relevant ML problem for which it would make sense to employ a quantum computer as opposed to a classical computer does not exist, according to physicist Ryan Sweke of the Free University of Berlin in Germany. It's possible that in the quantum realm, jobs that make sense classically may not. 
But, the goal shouldn't only be to speed up any classical programme by making it operate in a quantum environment. Understanding quantum computing in general or gaining knowledge about the conventional ML algorithms and improving them may both be accomplished by creating QML algorithms for already existing ML algorithms. A fresh approach to many intractable problems can be found by applying quantum thinking to classical ones.

# Familiar Quantum Algorithms

I am well-versed in a number of quantum algorithms, including Grover, Simon, Shor, Brassard Hoyer Tapp (BHT), thanks to my study of Qiskit's Textbook: Quantum Computing for Computer Scientists by Yanofsky and Mannucci. I've been researching quantum symmetric key cryptanalysis for a while, so QML is also new to me (4 months to be precise).

In order to beat the traditional $O(n)$ time, the grover's method, which searches through an unsorted list of size $n$ in $O(sqrtn), will be explained. It does this by amplifying the desired state's amplitude utilising the idea of amplitude amplication. Both machine learning[2] and symmectric key cryptography[1] have seen extensive use of Grover.

# Familiar Quantum Software

Qiskit[3] and ProjectQ[4] are two quantum libraries that I have been utilising the most of the time. I've also utilised Qsim[5], a freshly created Indian programme. When it comes to effectively modelling huge depth circuits, libQuantum[6] in C is also really helpful. For QML HEP work, I have utilised Cirq for the first time. Using Cirq was more simpler than I had anticipated because I was already familiar with Tensorflow from my previous work in machine learning.

Tensorflow Quantum, in my opinion, is still in a very early stage while Qiskit has seen significant development. With Qiskit, genuine quantum hardware and IBM simulators are both utilised.
One of Qiskit's benefits over Tensorflow Quantum, in my opinion, is the sizeable open source community that has produced some excellent content (such as the textbook and summer school for Qiskit).

# References
1. Wikipedia [link](https://en.wikipedia.org/wiki/Grover%27s_algorithm#Cryptography), [papers](https://ieeexplore.ieee.org/search/searchresult.jsp?action=search&newsearch=true&matchBoolean=true&queryText=(%22All%20Metadata%22:Grover)%20AND%20(%22All%20Metadata%22:Cryptanalysis)) in IEEE.
2. [A Grover-search based quantum learning scheme for classification](https://iopscience.iop.org/article/10.1088/1367-2630/abdefa).
3. [Qiskit, open source software development kit (SDK)](https://qiskit.org/).
4. [Website](https://projectq.ch/). Damian S. Steiger, Thomas Haener, and Matthias Troyer "ProjectQ: An Open Source Software Framework for Quantum Computing" Quantum 2, 49 (2018) (published on arXiv on 23 Dec 2016).
5. [QSim](https://qctoolkit.in/) QC workbench.
6. [libquantum](http://www.libquantum.de/) Hendrik Weimer.
