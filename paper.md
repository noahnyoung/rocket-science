---
title: 'Rocket-Science: A mini-app for teaching Fortran code modernization'
tags:
  - Fortran
  - rocket propulsion
  - software archaeology
authors:
  - name: Damian Rouson^[Corresponding author.]
    orcid: 0000-0002-2344-868X
    affiliation: "1, 2" # (Multiple affiliations must be quoted)
  - name: Brad Richardson
    affiliation: 2
  - name: Brian Laubacher
    affiliation: 3
affiliations:
 - name: Better Scientific Software Fellow, Sustainable Horizons Institute
   index: 1
 - name: Sourcery Institute
   index: 2
 - name: Autoliv, Inc.
   index: 3
date: 13 August 2017
bibliography: paper.bib

# Optional fields if submitting to a AAS journal too, see this blog post:
# https://blog.joss.theoj.org/2018/12/a-new-collaboration-with-aas-publishing
aas-doi: 10.3847/xxxxx <- update this with the DOI from AAS once you know it.
aas-journal: Astrophysical Journal <- The name of the AAS journal.
---

# Summary

This repository contains

* A modern mini-application for simulating solid rocket motors using an
  object-oriented, functional programming style in Fortran 2018.
* A legacy motor simulator demonstrating the solution of the same governing
  equations using a procedural programming style in Fortran 77/90.
* A refurbished motor simulator demonstrating one modernization path for
  making the legacy solver object-oriented but without the radical redesign
  that affords the above purely functional programming style.

The simulator includes a capability for launching gnuplot to compare results
of the three solvers.

# Statement of need

The most highly cited article on refactoring Fortran is "Refactorings
for Fortran and high-performance computing" [@overbey2005refactorings].

# Governing Equations

Rockets obey the second law of motion of Isaac Newton:

\begin{equation}\label{eq:fourier}
   \vec{F} = \frac{ d\vec{p} }{ dt }
\end{equation}

# Figures

Figures can be included like this:
![Caption for example figure.\label{fig:example}](figure.png)
and referenced from text using \autoref{fig:example}.

# Acknowledgements

We stood on the shoulders of giants.

# References
