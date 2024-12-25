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

# Other Sections

Other than a **Summary** and a **Statement of Need** section,
your paper can also contain other main sections and sub-sections.

## Citations

Citations can be used like this [@michaud-agrawal2011mdanalysis] [@oliver_beckstein-proc-scipy-2016] [@alibay2023building],
or this [@pedregosa2011scikitlearn], or this @pedregosa2011scikitlearn.

## Math Equations

For inline math, use single dollars `$`; for example $f(x) = e^{\pi/x}$.

For block math, use double dollars:

$$a^n + b^n = c^n \label{eq:fermat}$$

Math blocks can be referenced using \autoref{eq:fermat} or \ref{eq:fermat}.

Authors who do not wish to include the label directly in the formula
can use a Markdown span to add the label:

[$$a^n + b^n = c^n$$]{label="eq:fermat2"}

These can be referenced the same using \autoref{eq:fermat2} or \ref{eq:fermat2}.

You can also use plain \LaTeX for equations:

\begin{equation}
\label{eq:fourier}
\hat f(\omega) = \int_{-\infty}^{\infty} f(x) e^{i\omega x} dx
\end{equation}

and reference them using \autoref{eq:fourier} or \ref{eq:fourier}.


## Markdown

Links can be used like [this](https://example.com).

For long dashes---like this one---use three hyphens.

### Inline Markup

Inline markup in Markdown should be semantic, not presentations.
It can be used to make *italic*, **bold**, ~~strikethrough~~, ~sub~script, ^super^script,
[underline]{.ul}, [Small Caps]{.sc}, and `inline code`.

### Lists

- apples
- citrus fruits
  - lemons
  - oranges

### Ordered Lists

0. If two systems are each in thermal equilibrium with a third, they are
   also in thermal equilibrium with each other.
1. In a process without transfer of matter, the change in internal
   energy, $\Delta U$, of a thermodynamic system is equal to the energy
   gained as heat, $Q$, less the thermodynamic work, $W$, done by the
   system on its surroundings. $$\Delta U = Q - W$$

### Inline Images

Inline images can be used like this ![](../full_light.png){height="9pt"} inside a paragraph.


### Figures

Figures can be included like this:

![This is the caption of the figure.\label{fig:example}](../full_light.png){ width=50% }

and referenced from text using \autoref{fig:example} or \ref{fig:example}.


### Footnotes

Footnotes can be defined anywhere (see end of document) and referenced using [^first-footnote].


# Acknowledgements

# References

[^first-footnote]: This is a footnote.