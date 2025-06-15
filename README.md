# proteinbrowser - Resources for visualizing 3-D protein structures and multiple sequence alignments using JBrowse 2

This page is a collection of resources for our paper "Proteins in the Genome Browser" (in prep), including:

- Standalone web apps (JBrowse 2 genome hubs, Ensembl GeneTree browser, UniProt browser)
- Re-usable JBrowse 2 plugins (jbrowse-plugin-protein3d, jbrowse-plugin-msaview)
- Re-usable NPM packages (react-msaview)


## Screenshots


![image2](https://github.com/user-attachments/assets/a9ac296c-e2fe-41c7-bf7d-d519548eb046)


![image5](https://github.com/user-attachments/assets/7f52de03-0a2b-47fb-95f6-bb4505185487)


## Web server resources

### JBrowse 2 instances with protein functionality integrated

We have a live instance of JBrowse 2 with the protein3d and react-msaview plugins pre-installed for human data here

Live link https://jbrowse.org/demos/app/?session=share-9eVzKwMc5f&password=45RcZ 

You can right-click a gene of interest and launch a MSA or 3-D protein viewer

### React-msaview standalone app

This page is a generic instance of react-msaview that provides standalone (non-JBrowse 2 integrated) MSA visualization

https://gmod.org/react-msaview/

### Ensembl Compara GeneTree browser

This is a demo of integrating react-msaview with simple programmatic automation to Web resources, including Ensembl Compara GeneTrees (REST API) and TreeFam

https://jbrowse.org/demos/msafam/



## Software resources

### JBrowse 2 plugins 

We created two independent JBrowse 2 plugins for enabling protein browsing:

- jbrowse-plugin-msaview - programmatically integrates react-msaview into JBrowse 2 for re-use, allows querying NCBI BLAST
- jbrowse-plugin-protein3d - programmatically integrates Mol* 3-D protein structure views, allows querying AlphaFoldDB and UniProt

Users can install these plugins via the in-app plugin store via a click of a button

Administrators can also pre-load the plugin for all their users

### User guide/developer guide for the react-msaview

A short user guide for react-msaview is available here. 

It is a fairly feature rich and complex MSA viewer. Here is the user guide

https://github.com/GMOD/react-msaview/blob/main/docs/user_guide.md


## Live demos

- BRAF 3-D structure connected with genome - https://jbrowse.org/demos/app/?session=share-SyUYMmF2R3&password=0ycYQ
- BRAF multiple sequence alignment connected with genome - https://jbrowse.org/demos/app/?session=share-IUdmod8VB7&password=MKfuU 
- BRAF 1-D protein annotations view - https://jbrowse.org/demos/app/?session=share-YYu64eFQ3U&password=sDims 

