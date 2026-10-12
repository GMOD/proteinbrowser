# Software and data services

## Repositories

| Repository                                                                   | What it is                                                                   |
| ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| [jbrowse-plugin-protein3d](https://github.com/GMOD/jbrowse-plugin-protein3d) | Mol\* 3-D structure views inside JBrowse 2, with AlphaFold DB and UniProt lookups |
| [jbrowse-plugin-msaview](https://github.com/GMOD/jbrowse-plugin-msaview)     | JBrowseMSA inside JBrowse 2, with NCBI BLAST and ortholog workflows          |
| [JBrowseMSA](https://github.com/GMOD/JBrowseMSA)                             | The MSA viewer: a React component, also a script tag, an R package and a CLI |
| [g2p_mapper](https://github.com/GMOD/g2p_mapper)                             | Genome-to-protein mapper: transcript CDS ↔ structure residues                |
| [msa-viewer-bench](https://github.com/GMOD/msa-viewer-bench)                 | Benchmark harness behind Supplementary Figure 1 and Table 1                  |
| [jbrowse-components](https://github.com/GMOD/jbrowse-components)             | JBrowse 2 itself, which the two plugins extend                               |

Users install both plugins from the in-app plugin store. Administrators add them to a `config.json`.

## Data services

The demos resolve what they show per gene from these services:

- [AlphaFold DB](https://alphafold.ebi.ac.uk/) — predicted structures
- [3D-Beacons](https://www.ebi.ac.uk/pdbe/pdbe-kb/3dbeacons/) and [RCSB PDB](https://www.rcsb.org/) — experimental structures
- [UniProt](https://www.uniprot.org/) — accession mapping and 1-D protein annotations
- [NCBI Datasets](https://www.ncbi.nlm.nih.gov/datasets/) — genes, transcripts, orthologs
- [NCBI BLAST](https://blast.ncbi.nlm.nih.gov/) — sequences for genes with no ortholog record
- [NCBI CDD](https://www.ncbi.nlm.nih.gov/Structure/cdd/cdd.shtml) and [InterProScan](https://www.ebi.ac.uk/interpro/) — domain overlays
- [EBI Clustal Omega](https://www.ebi.ac.uk/jdispatcher/msa/clustalo) — on-demand alignments
- [UCSC Genome Browser](https://genome.ucsc.edu/) — assemblies, ClinVar, AlphaMissense, 100-way alignment
