---
layout: default
title: ActivePapers Python edition
---

## The ActivePapers Python edition

The Python edition is the most practically useful implementation of
the ActivePapers concept, because it can build on the very well
developed ecosystem for scientific computing in the Python language,
which offers libraries for many scientific application domains.
However, the Python platform also imposes a few limitations:

 1. The restrictions on calclet execution cannot be strictly
    enforced. Circumventing the rules is possible, but unlikely
    to happen by accident. Users should inspect the code in a
    downloaded ActivePaper before executing it, or run ActivePapers
    in a virtual machine where malicious code cannot do any harm.
    
 2. Reproducibility is limited, as the same Python code can produce
    different results with different versions of Python or one of the
    libraries on which ActivePapers depends (NumPy, HDF5, h5py and
    their respective dependencies).
 
 3. Many popular libraries for scientific computing contain extension
    modules and can therefore not be packaged as ActivePapers. They
    can be used as external dependencies, but this increases the
    number of dependencies that every user must install before being
    able to use an ActivePaper, and it reduces reproducibility.

For a first impression of ActivePapers, see the [tutorial](tutorial.html).

The development of the ActivePapers Python edition is
[hosted on Bitbucket](https://bitbucket.org/khinsen/active_papers_py/wiki/Home).
 