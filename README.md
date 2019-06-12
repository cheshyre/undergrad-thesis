# Bachelor's Thesis: Paper and Defense

## Exploring Many-Body Force Induction in the Similarity Renormalization Group in 1 Dimension

This repository contains the most up-to-date version of my bachelor's thesis.
While I have corrected a few minor typography mistakes and typos since
submitting it, the version that was submitted can be seen by selecting the
`submission_version` tag. In addition, the version of the thesis at the time of
my defense can be seen by selecting the `defense_version` tag. For
convenience, abstract is offered below.

## Abstract

A major goal of nuclear theory is to model atomic nuclei and make theoretical 
predictions of nuclear observables starting from inter-nucleon forces. 
Approaches starting from these inter-nucleon forces, known as ab-initio
methods, face significant computational challenges due to the complexity
of the nuclear system and the nature of the forces. The similarity
renormalization group (SRG) method is often used in modern calculations to
soften these interactions, which simplifies the problem thereby allowing
ab-initio methods to be extended to larger systems. SRG, when applied to an
$A$-particle system, induces many-body forces that are not accounted for
when the $A$-body results are used to compute results for larger systems.
The errors from these omitted induced many-body forces currently limit
the application of SRG to small and medium systems, as for large systems these
errors become too large for calculations to yield useful results. The SRG
method takes an input from the user, the flow operator $\hat{G}_s$, which is
taken to be the kinetic energy in most modern SRG calculations. Results have
suggested that alternative choices for the flow operator may produce smaller
induced many-body forces, which would allow calculations with SRG to be
extended to larger systems.

We return to the 1-dimensional system of bosons in which the nuclear theory 
group at OSU initially explored the application of SRG to nuclear problems. 
As the results from this simple system are generalizable to full 3-dimensional 
calculations, we seek to test alternative flow operators in this 1-dimensional 
system, where visualizing and interpreting results is substantially easier. 
We develop a Python library to handle the setup of the physical system and the 
SRG evolution. We compare the results obtained using this library to the 
results from an analogous paper by Jurgenson and Furnstahl in 2008 to verify 
the correctness of our implementation. We then use this framework to test 
induced 3-body forces for several 2-body flow operator choices. We discuss 
our preliminary results and offer some options for further exploration.

