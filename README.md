# proteinbrowser

A collection of resources for our paper "Proteins in the Genome Browser,"
published in the Journal of Molecular Biology.

If you find these tools useful, please cite our work:

> Diesh, C., Stevens, G., Bridge, C., Hogue, G., Buels, R., Cain, S., Stein, L.,
> & Holmes, I. (2026). Proteins in the Genome Browser: Integration of
> Phylogenies, Alignments, and Structures With Nucleotide-level Evidence in
> JBrowse 2. _Journal of Molecular Biology_, 169645.
> https://doi.org/10.1016/j.jmb.2026.169645

## Featured demo

The [Protein Browser](https://staging.genomes.jbrowse.org/protein-browser/) demo
auto-launches a linked view combining a multiple sequence alignment (MSA), a 3-D
protein structure, and a linear genome view — the graphical abstract of our
paper.

## Screenshots

[![Gene Explorer headline](img/2.png)](https://gmod.org/JBrowseMSA/gene-explorer/?gene=PTEN)

![](img/1.png)

## Other ways to access the protein browser

- [genomes.jbrowse.org](https://genomes.jbrowse.org) — JBrowse 2 instances with
  the 3-D protein structure and MSA plugins loaded. Right-click any gene of
  interest to launch an MSA or 3-D protein viewer.
- [Ensembl Compara and TreeFam browser](https://jbrowse.org/demos/msafam/) —
  load data from Ensembl Compara Gene Trees and TreeFam.
- [Uniprot Browser](https://cmdcolin.github.io/uniprot_browser) — accesses the
  UniProt API to retrieve protein annotations.

## JBrowse 2 plugins

We created two independent JBrowse 2 plugins to connect the genome browser to
protein resources. Users can install them via the in-app plugin store, or
administrators can install them for all their users:

- [jbrowse-plugin-msaview](https://github.com/GMOD/jbrowse-plugin-msaview) —
  integrates react-msaview into JBrowse 2 and supports querying NCBI BLAST.
- [jbrowse-plugin-protein3d](https://github.com/GMOD/jbrowse-plugin-protein3d) —
  integrates Mol\* 3-D protein structure views and supports querying AlphaFold
  DB and UniProt.

## User and developer guide

User guide and developer docs for JBrowseMSA are available at
https://gmod.org/JBrowseMSA/

## Contact

Please [contact us](https://jbrowse.org/jb2/contact) or open a GitHub issue if
you have any questions or bug reports.
