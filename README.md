# proteinbrowse

This page is a collection of resources for our paper "Proteins in the Genome Browser"

It is a meta-collection of tools that we have developed for these purposes

## Live demos

### BRAF 3-D structure connected with genome

See https://jbrowse.org/demos/app/?session=share-SyUYMmF2R3&password=0ycYQ

### BRAF multiple sequence alignment connected with genome

See https://jbrowse.org/demos/app/?session=share-IUdmod8VB7&password=MKfuU 

### BRAF 1-D protein annotations view

Live link https://jbrowse.org/demos/app/?session=share-YYu64eFQ3U&password=sDims 


### Multiple protein structure superposition

Live link https://jbrowse.org/demos/app/?session=share-9eVzKwMc5f&password=45RcZ 



### React-msaview standalone app


This page is a generic instance of react-msaview
https://gmod.org/react-msaview/

### Ensembl Compara GeneTree browser

This is a demo of react-msaview that connects to the Ensembl Compara GeneTrees REST API to download multiple sequence alignments. It also has the TreeFam database loaded (an older, no longer updated resource, but still useful!)
https://jbrowse.org/demos/msafam/



### JBrowse 2 instances with protein3d and msaview plugins pre-loaded

This demo app has the jbrowse-plugin-msaview and jbrowse-plugin-protein3d plugins pre-installed. You can right-click a gene of interest and it will let you launch an MSA view or Protein 3D viewer for any gene. 

Note 1. The procedure it uses to find the protein associated with the gene is 

(a) lookup gene ID on mygene.info to get uniprot ID and then 
(b) get AlphaFold entry via the UniProt ID

Note 2. The procedure it uses to find multiple sequence alignments for the gene is that we pre-loaded the knownCanonical.exonAA.fa file from https://hgdownload.soe.ucsc.edu/goldenPath/hg38/multiz100way/alignments/  

We used a somewhat manual procedure but we are working on documenting the method for other users to load their own MSAs


https://jbrowse.org/demos/app

## JBrowse plugins

We created two independent modules called jbrowse-plugin-msaview and jbrowse-plugin-protein3d that can be used on your JBrowse instances

Users can install it via the in-app plugin store via a click of a button

Administrators can also pre-load the plugin for all their users

https://github.com/GMOD/jbrowse-plugin-msaview

https://github.com/GMOD/jbrowse-plugin-protein3d


## User guide for the react-msaview

A short user guide for react-msaview is available here. It is a fairly feature rich and complex MSA viewer, so there are many small features worth noting.

https://github.com/GMOD/react-msaview/blob/main/docs/user_guide.md

## Developer guide for react-msaview

Developers seeking to use the react-msaview component on their webpages can visit our github and this usage guide

https://github.com/GMOD/react-msaview

https://github.com/GMOD/react-msaview/blob/main/USAGE.md
https://github.com/GMOD/react-msaview/blob/main/docs/user_guide.md

