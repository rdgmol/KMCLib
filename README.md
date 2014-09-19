## *KMCLib* - a general framework for lattice kinetic Monte Carlo (KMC) simulations

### License and copying

    Developed by Mikael Leetmaa at the Royal Institute of Technology (KTH), Sweden.
    Copyright (c)  2012-2014  Mikael Leetmaa
    Released under the GPLv3 license, see 'LICENSE.txt' for details.

When you use *KMCLib* in your research please **cite** the paper describing the code

    Mikael Leetmaa and Natalia V. Skorodumova
    “KMCLib: A general framework for lattice kinetic Monte Carlo (KMC) simulations”
    Comput. Phys. Commun. (2014) DOI: 10.1016/j.cpc.2014.04.017


### *KMCLib* version 1.0 ready for release
*KMCLib* is a general framework for *lattice* kinetic Monte Carlo (KMC) simulations, to simulate the time evolution of systems of up to millions of particles in one, two or three dimensions. *KMCLib* is organized as a collection of Python frontend functions, classes and interfaces for performing efficient *lattice* KMC simulations, with all computationally heavy backend functionality implemented in C++.

###The combination of features makes *KMCLib* unique
* Python user interface - well documented, easily extended.
* C++ backend library for maximizing efficiency.
* Easy to prototype KMC models - no need to recompile source to run new models.
* Arbitrarily complex elementary processes can be used.
* On-the-fly evaluation of custom rate expressions written in Python.
* Built in on-the-fly mean square displacement (MSD) analysis to facilitate diffusion studies.
* MPI parallelism without loss of accuracy.

### Well documented with usage examples and install instructions
The code manual (http://leetmaa.github.io/KMCLib/manual-v1.0/) includes full documentation of the Python interface and several usage examples, as well as installation instructions for both Linux and Mac.

### No known issues
With the latest bugfix update 1.0.1 there are at the time of writing *no* known issues with the program. This is of course no guarantee that there are none left to be found. So if you find any bugs or issues, or if you have suggestions for improvements, please let me know.

### Obtain a copy
The program is distributed under the GPLv3 license and can be obtained from the *KMCLib* git repository https://github.com/leetmaa/KMCLib/releases/tag/v1.0

### Use *KMCLib* in your own research
If you would be interested to use this code in your research and need any assistance, or if you are interested in collaborations, please don't hesitate to send me an e-mail: leetmaa@kth.se


Mikael Leetmaa, May 6 2014


