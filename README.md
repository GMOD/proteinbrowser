# proteinbrowser - Resources for visualizing 3-D protein structures and multiple sequence alignments using JBrowse 2

This page is a collection of resources for our paper "Proteins in the Genome Browser" (in prep)

## Screenshots


![image2](https://github.com/user-attachments/assets/a9ac296c-e2fe-41c7-bf7d-d519548eb046)


![image5](https://github.com/user-attachments/assets/7f52de03-0a2b-47fb-95f6-bb4505185487)


## Web server resources

- JBrowse 2 instances with protein plugins loaded. You can right-click any gene-of-interest to launch an MSA or 3-D protein viewer https://jbrowse.org/demos/app/
- React-msaview standalone app. This app demonstrates our MSA viewer functionality (no JBrowse 2 integration) https://gmod.org/react-msaview/
- Ensembl Compara and TreeFam browser. This app provides a simple method to load data from Ensembl Compara Gene Trees and TreeFam into our app https://jbrowse.org/demos/msafam/
- Uniprot Browser. This app accesses the Uniprot API to get protein annotations https://cmdcolin.github.io/uniprot_browser

## Software resources

### JBrowse 2 plugins 

We created two independent JBrowse 2 plugins to help connect the genome browser to protein resources. Users can install these plugins via the in-app plugin store, or administrators can install the plugin for all their users:

- [jbrowse-plugin-msaview](https://github.com/GMOD/jbrowse-plugin-msaview) - programmatically integrates react-msaview into JBrowse 2 for re-use, allows querying NCBI BLAST
- [jbrowse-plugin-protein3d](https://github.com/GMOD/jbrowse-plugin-protein3d) - programmatically integrates Mol* 3-D protein structure views, allows querying AlphaFoldDB and UniProt

### User guide/developer guide for the react-msaview

A short user guide for react-msaview is available here

https://github.com/GMOD/react-msaview/blob/main/docs/user_guide.md


## Live demos

- BRAF 3-D structure connected with genome - https://jbrowse.org/demos/app/?session=share-SyUYMmF2R3&password=0ycYQ
- BRAF multiple sequence alignment connected with genome - https://jbrowse.org/demos/app/?session=share-IUdmod8VB7&password=MKfuU 
- BRAF 1-D protein annotations view - https://jbrowse.org/demos/app/?session=share-YYu64eFQ3U&password=sDims 

