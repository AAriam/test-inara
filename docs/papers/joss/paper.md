---
title: >-
    MyPackage: A Very Cool Python Application
authors:
  - name: Jane Doe
    orcid: 0000-0000-0000-0000
    affiliation: 1
  - name: John L. Doe
    orcid: 0000-0000-0000-0001
    affiliation: [1, 2]
    equal-contrib: true
  - name: John Smith
    orcid: 0000-0000-0000-0002
    affiliation: [2, 3]
    equal-contrib: true
  - given-names: Ludwig
    dropping-particle: van
    surname: Beethoven
    orcid: 0000-0000-0000-0003
    affiliation: 3
    corresponding: true
affiliations:
  - index: 1
    name: Independent Researcher, Country
  - index: 2
    name: Institution Name, Country
  - index: 3
    name: Lyman Spitzer, Jr. Fellow, Princeton University, United States
    ror: 00hx57361
tags:
  - first keyword
  - second keyword
  - third keyword
date: 11 November 2024
bibliography: ../paper.bib
---

# Summary

Begin your paper with a summary of the high-level functionality
of your software for a non-specialist reader.
Avoid jargon in this section.

JOSS welcomes submissions from broadly diverse research areas.
For this reason, we require that authors include in the paper some sentences
that explain the software functionality and domain of use to a non-specialist reader.
We also require that authors explain the research applications of the software.
The paper should be between 250-1000 words.
Authors submitting papers significantly longer than 1000 words
may be asked to reduce the length of their paper.

JOSS papers are only expected to contain a limited set of metadata,
a Statement of need, Summary, Acknowledgements, and References sections.
Given this format, a “full length” paper is not permitted,
and software documentation such as API (Application Programming Interface) functionality
should not be in the paper and instead should be outlined in the software documentation.

# Statement of Need

A Statement of need section that clearly illustrates the research purpose
of the software and places it in the context of related work.

# Other Section

Figures can be included like this:

![This is the caption of the figure.\label{fig:example}](../full_light.png){ width=50% }

and referenced from text using \autoref{fig:example}.

Single dollars `$` are required for inline mathematics e.g. $f(x) = e^{\pi/x}$.

Double dollars make self-standing equations:

$$
\Theta(x) = \left\{\begin{array}{l}
0\textrm{ if } x < 0\cr
1\textrm{ else}
\end{array}\right.
$$

You can also use plain \LaTeX for equations:

\begin{equation}\label{eq:fourier}
\hat f(\omega) = \int_{-\infty}^{\infty} f(x) e^{i\omega x} dx
\end{equation}

and refer to \autoref{eq:fourier} from text.

For long dashes---like this one---use three hyphens.

authentic tasks leveraging on commonly used Python packages, such as MDAnalysis
[@michaud-agrawal2011mdanalysis] [@oliver_beckstein-proc-scipy-2016] [@alibay2023building] and 
scikit-learn [@pedregosa2011scikitlearn]. 


| Session                            | Materials |
|------------------------------------|-----------|
| L1: Introduction to Proteins | [Lecture Slides](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/1_Introduction/Lecture_1_Introduction.pdf) | 
| L2: Understanding Protein Systems | [Lecture Slides](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/2_Protein_Preparation/Lecture_2_Protein_Prep.pdf)
| L3: Protein-Ligand Docking                 |  [Lecture Slides](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/3_Docking/Lecture_3_Docking.pdf)| 
| P: Protein-Ligand Docking                 |  [![Docking](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/3_Docking/3_Docking.ipynb)| 
| L4: Simulation Setup          | [Lecture Slides](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/4_Simulation_Setup/Lecture_4_Simulation_setup.pdf) |
| P: Simulation Setup          | [![Simulation](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/4_Simulation_Setup/4_Simulation_Setup.ipynb) |


| Session                                             | Materials |
|-----------------------------------------------------|-----------|
| L5: Simulation Basic Analyses             | [Lecture Slides](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/5_Analysis_MDAnalysis/Lecture_5_Analysis_MDAnalysis.pdf)|
| P: Simulation Basic Analyses             | [![Analysis_0](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/5_Analysis_MDAnalysis/5_Analysis_MDAnalysis.ipynb)|
| L6: Dimensionality Reduction                   | [Lecture Slides](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/6_Analysis_DR/Lecture_6_DR.pdf)  |
| P: Dimensionality Reduction, part 1           |  [![Analysis_1](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/6_Analysis_DR/6_Analysis_part1.ipynb)|
| P: Dimensionality Reduction, part 2           | [![Analysis_2](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/6_Analysis_DR/6_Analysis_part2.ipynb)|
| L7: Clustering   | [Lecture Slides](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/7_Analysis_clustering/Lecture_7_Clustering.pdf)|
| P: Clustering   | [![Analysis_3](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/7_Analysis_clustering/7_clustering.ipynb) |
| L8: Data Classification    | [Lecture Slides](https://github.com/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/8_Analysis_classification/Lecture_8_classification.pdf) | 
| P: Data Classification  | [![Analysis_4](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CCPBioSim/Into_to_MD_simulation_and_analysis/blob/main/8_Analysis_classification/1_classification.ipynb) |


# Acknowledgements

# References
