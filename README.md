# proteinbrowser

This page is a collection of resources for our paper "Proteins in the Genome Browser: integration of phylogenies, alignments, and structures with nucleotide-level evidence in JBrowse 2" (in prep)

## Screenshots

![image2](https://github.com/user-attachments/assets/a9ac296c-e2fe-41c7-bf7d-d519548eb046)

![image5](https://github.com/user-attachments/assets/7f52de03-0a2b-47fb-95f6-bb4505185487)

<img width="1475" height="929" alt="k1" src="https://github.com/user-attachments/assets/f17265d1-8991-4544-9135-cc7dbb3f7d03" />

## Main web server

- We created JBrowse 2 instances for many species of interest (including human with hg19, hg38, and the T2T hs1 assembly) with jbrowse-plugin-protein3d and jbrowse-plugin-msaview loaded by default. You can
  right-click any gene-of-interest to launch an MSA or 3-D protein viewer for the human browsers at 
  https://genomes.jbrowse.org (other species being worked on)

## Other demos

- Ensembl Compara and TreeFam browser: This app provides a simple method to load
  data from Ensembl Compara Gene Trees and TreeFam into our app
  https://jbrowse.org/demos/msafam/
- Uniprot Browser: This app accesses the Uniprot API to get protein annotations
  https://cmdcolin.github.io/uniprot_browser

## JBrowse 2 plugins

We created two independent JBrowse 2 plugins to help connect the genome browser
to protein resources. Users can install these plugins via the in-app plugin
store, or administrators can install the plugin for all their users:

- [jbrowse-plugin-msaview](https://github.com/GMOD/jbrowse-plugin-msaview) -
  programmatically integrates react-msaview into JBrowse 2 for re-use, allows
  querying NCBI BLAST
- [jbrowse-plugin-protein3d](https://github.com/GMOD/jbrowse-plugin-protein3d) -
  programmatically integrates Mol\* 3-D protein structure views, allows querying
  AlphaFoldDB and UniProt

## User guide/developer guide for JBrowseMSA

A short user guide for JBrowseMSA is available here

https://github.com/GMOD/JBrowseMSA/blob/main/docs/user_guide.md

## Live demos

- BRAF 3-D structure connected with genome -
  https://jbrowse.org/code/jb2/main/?config=%2Fucsc%2Fhg38%2Fconfig.json&session=share-oZc6gP5zSQ&password=zFvQi
- BRAF 1-D protein annotations view -
  https://jbrowse.org/code/jb2/main/?config=%2Fucsc%2Fhg38%2Fconfig.json&session=share-xgw4Y7Xoby&password=SMk7u

## Footnote

Please feel free to contact us (https://jbrowse.org/jb2/contact) or make a github issue here if you have any questions or bug reports
