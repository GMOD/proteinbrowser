# proteinbrowse

This page is a collection of resources for our paper "Proteins in the Genome Browser"

It is a meta-collection of tools that we have developed for these purposes

## Screenshots


![image2](https://github.com/user-attachments/assets/a9ac296c-e2fe-41c7-bf7d-d519548eb046)


![image5](https://github.com/user-attachments/assets/7f52de03-0a2b-47fb-95f6-bb4505185487)



### Multiple protein structure superposition

Live link https://jbrowse.org/demos/app/?session=share-9eVzKwMc5f&password=45RcZ 



### React-msaview standalone app

This page is a generic instance of react-msaview that provides standalone (non-JBrowse 2 integrated) MSA visualization

https://gmod.org/react-msaview/

### Ensembl Compara GeneTree browser

This is a demo of integrating react-msaview with simple programmatic automation to Web resources including:

- Ensembl Compara GeneTrees (REST API)
- TreeFam


https://jbrowse.org/demos/msafam/


### JBrowse 2 instances with protein3d and msaview plugins pre-loaded

This demo app has the jbrowse-plugin-msaview and jbrowse-plugin-protein3d plugins pre-installed. 

You can right-click a gene of interest and it will let you launch an MSA view or Protein 3D viewer for any gene. 

https://jbrowse.org/demos/app

## JBrowse 2 plugins

We created two independent plugins for enabling protein browsing:


- jbrowse-plugin-msaview - programmatically integrates react-msaview into JBrowse 2 for re-use, allows querying NCBI BLAST
- jbrowse-plugin-protein3d - programmatically integrates Mol* 3-D protein structure views, allows querying AlphaFoldDB and UniProt

Users can install these plugins via the in-app plugin store via a click of a button

Administrators can also pre-load the plugin for all their users

## User guide for the react-msaview

A short user guide for react-msaview is available here. It is a fairly feature rich and complex MSA viewer, so there are many small features worth noting.

https://github.com/GMOD/react-msaview/blob/main/docs/user_guide.md

## Developer guide for react-msaview

Developers seeking to use the react-msaview component on their webpages can visit our github and this usage guide

https://github.com/GMOD/react-msaview

https://github.com/GMOD/react-msaview/blob/main/USAGE.md
https://github.com/GMOD/react-msaview/blob/main/docs/user_guide.md




## Live demos

### BRAF 3-D structure connected with genome

See https://jbrowse.org/demos/app/?session=share-SyUYMmF2R3&password=0ycYQ

### BRAF multiple sequence alignment connected with genome

See https://jbrowse.org/demos/app/?session=share-IUdmod8VB7&password=MKfuU 

### BRAF 1-D protein annotations view

Live link https://jbrowse.org/demos/app/?session=share-YYu64eFQ3U&password=sDims 

