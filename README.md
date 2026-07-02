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

The [JBrowseMSA Gene Explorer](https://gmod.org/JBrowseMSA/gene-explorer/)
auto-launches a linked view combining a multiple sequence alignment (MSA), a 3-D
protein structure, and a linear genome view — the graphical abstract of our
paper.

## Screenshots

![image2](https://github.com/user-attachments/assets/a9ac296c-e2fe-41c7-bf7d-d519548eb046)

![image5](https://github.com/user-attachments/assets/7f52de03-0a2b-47fb-95f6-bb4505185487)

<img width="1475" height="929" alt="k1" src="https://github.com/user-attachments/assets/f17265d1-8991-4544-9135-cc7dbb3f7d03" />

## Main web server

- [genomes.jbrowse.org](https://genomes.jbrowse.org) — JBrowse 2 instances with
  the 3-D protein structure and MSA plugins loaded. Right-click any gene of
  interest to launch an MSA or 3-D protein viewer.

## Other demos

- [Ensembl Compara and TreeFam browser](https://jbrowse.org/demos/msafam/) — load
  data from Ensembl Compara Gene Trees and TreeFam.
- [Uniprot Browser](https://cmdcolin.github.io/uniprot_browser) — accesses the
  UniProt API to retrieve protein annotations.

## JBrowse 2 plugins

We created two independent JBrowse 2 plugins to connect the genome browser to
protein resources. Users can install them via the in-app plugin store, or
administrators can install them for all their users:

- [jbrowse-plugin-msaview](https://github.com/GMOD/jbrowse-plugin-msaview) —
  integrates react-msaview into JBrowse 2 and supports querying NCBI BLAST.
- [jbrowse-plugin-protein3d](https://github.com/GMOD/jbrowse-plugin-protein3d) —
  integrates Mol\* 3-D protein structure views and supports querying AlphaFold DB
  and UniProt.

## User and developer guide

A short user guide for JBrowseMSA is available at
https://github.com/GMOD/JBrowseMSA/blob/main/docs/user_guide.md

## Live demos

- [BRAF 3-D structure connected with genome](https://jbrowse.org/code/jb2/main/?config=%2Fucsc%2Fhg38%2Fconfig.json&session=share-oZc6gP5zSQ&password=zFvQi)
- [BRAF 1-D protein annotations view](https://jbrowse.org/code/jb2/main/?config=%2Fucsc%2Fhg38%2Fconfig.json&session=share-xgw4Y7Xoby&password=SMk7u)
- [BRAF V600](https://jbrowse.org/code/jb2/main/?config=%2Fucsc%2Fhg38%2Fconfig.json&session=share-muppi_-WsU&password=tvhMa)

## Contact

Please [contact us](https://jbrowse.org/jb2/contact) or open a GitHub issue if
you have any questions or bug reports.
