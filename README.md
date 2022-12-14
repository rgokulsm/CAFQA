# CAFQA

A python notebook that runs CAFQA on the H2 molecule at some specific molecular specification. This is a sanity check for CAFQA. It needs the hypermapper tool - https://github.com/luinardi/hypermapper) apart from Qiskit.

This is a very trivial example - the search space is very small, with many degenerate solutions, and it often finds the best Clifford result just in its initial random search.

This can be extended to other molecules and molecular configurations. 

A future automated version will be out soon!

CAFQA paper: https://arxiv.org/abs/2202.12924

Bibtex:
```
@misc{CAFQA,
  doi = {10.48550/ARXIV.2202.12924},
  
  url = {https://arxiv.org/abs/2202.12924},
  
  author = {Ravi, Gokul Subramanian and Gokhale, Pranav and Ding, Yi and Kirby, William M. and Smith, Kaitlin N. and Baker, Jonathan M. and Love, Peter J. and Hoffmann, Henry and Brown, Kenneth R. and Chong, Frederic T.},
  
  keywords = {Quantum Physics (quant-ph), Hardware Architecture (cs.AR), FOS: Physical sciences, FOS: Physical sciences, FOS: Computer and information sciences, FOS: Computer and information sciences},
  
  title = {CAFQA: A classical simulation bootstrap for variational quantum algorithms},
  
  publisher = {arXiv},
  
  year = {2022},
  
  copyright = {arXiv.org perpetual, non-exclusive license}
}
```
