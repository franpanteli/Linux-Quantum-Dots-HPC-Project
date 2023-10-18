# Linux-Quantum-Dots-Project
<strong>Executive summary:</strong>

<p<This project is from a research internship I completed which used HPC to perform calculations in materials science (geometry optimisation on quantum dots). This was my first in-depth introduction to Linux and involved 6 weeks of submitting and monitoring jobs to the Tier 2 HPC, Young.  The internship report I produced in this repository first introduces Indium Phosphide using condensed matter Physics nomenclature and then discusses results from calculations using the HPC facility. Further theory is then explored as an extension to this. A more technical abstract for this project is found in its internship report.</p>

<strong> Full research internship abstract </strong>
<p>Quantum dots are an example of a nanomaterial which are used for their size-tunable
optoelectronic properties. There is an active body of computational and experimental
research surrounding indium phosphide quantum dots (InP QDs), which have been suggested as a non-toxic alternative to cadmium selenide (CdSe) QDs. Experimental methods
used to investigate these properties are commonly accompanied by computational methods, frequently including the use of the Density Functional Theory (DFT) method. This
KURF report was produced as part of an undergraduate summer research project and
involved the use of the CP2K software package and Tier 2 HPC, Young1
. This was to
approximate the configurations of 125 InP QD clusters which resided in their most stable states (geometry optimisation) using DFT. This involved an in-depth skills training
in the Linux environment via tutorials and online courses and was used to submit and
monitor provided InP QD clusters to a High-Performance computational facility. One
observation which confirmed the real-world challenges with research of this nature was
the larger computation times associated with performing geometry optimisation, due to
the larger number of electrons present within these systems. Since the relaxation time
of these structures was larger than anticipated, five structures for which calculations had
been completed were selected, between the ranges of 8 and 132 atoms in size. The minimum Root Mean Square Deviations (RMSDs) of these structures were calculated using
Python, to quantify the extent to which they were similar to their initial versions prior
to geometry optimisation. The structural changes within these QDs were also compared
by producing visual representations of them with VMD. While a visual compression-like
effect was observed in all five structures, their minimum RMSDs varied widely and regardless of the number of atoms. Finally, the 125 structures which geometry optimisation
was performed on observed a success rate of 36.8%, indicating the need for further repeats
of these calculations in future research. This project highlights the importance and associated challenges with research of this nature, with further research aiming to form a
database of these relaxed structures to train a machine learning model and the theory of
ab-initio molecular dynamics (AIMD) explored as an extension to the report.</p>
