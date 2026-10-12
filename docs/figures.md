# The paper's figures

The sessions open on a hosted JBrowse 2 with the msaview and protein3d plugins loaded, so they need no setup.

| Figure                | What it shows                                                                                    | Open it                                                      |
| --------------------- | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| 1A                    | BRAF V600 on the AlphaFold structure, with the ClinVar melanoma variants beside it in the genome | [connected session][fig1a]                                   |
| 1B                    | The same V600 position in a 100-way vertebrate protein alignment                                 | [Protein Browser on BRAF][braf] → **Open in JBrowse**        |
| 1C                    | BRAF's UniProt annotations as tracks in protein coordinates, AlphaMissense among them            | the click-path below                                         |
| 1D                    | Human and mouse PTEN AlphaFold predictions superposed                                            | [connected session][fig1d]                                   |
| Supp. Fig. 1, Table 1 | JBrowseMSA against JalviewJS, Wasabi and biojs-msa on large alignments                           | [msa-viewer-bench](https://github.com/GMOD/msa-viewer-bench) |

## Figure 1C

Figure 1C has no session URL, because its view has no assembly until the plugin builds one.

- Right-click the gene on [genomes.jbrowse.org](https://genomes.jbrowse.org)
- Choose **Launch protein view**
- Click the arrow beside **Launch**, then **Launch 1D protein annotation view**

The plugin registers the UniProt accession as an assembly whose reference sequence is the amino-acid sequence. It adds a track per UniProt feature type, alongside AlphaFold pLDDT and AlphaMissense scores.

[fig1a]:
  https://jbrowse.org/code/jb2/latest/?config=%2Fucsc%2Fhg38%2Fconfig.json&session=spec-%7B%22views%22%3A%5B%7B%22type%22%3A%22ProteinView%22%2C%22structures%22%3A%5B%7B%22uniprotId%22%3A%22P15056%22%2C%22initialResidues%22%3A%7B%22start%22%3A600%2C%22end%22%3A600%7D%7D%5D%2C%22transcriptId%22%3A%22NM_004333.6%22%2C%22sideBySide%22%3Atrue%2C%22zoomToBaseLevel%22%3Afalse%2C%22connectedView%22%3A%7B%22assembly%22%3A%22hg38%22%2C%22loc%22%3A%22chr7%3A140%2C753%2C280-140%2C753%2C400%22%2C%22tracks%22%3A%5B%22hg38-ncbiRefSeqSelect%22%2C%22hg38-clinvarMain%22%5D%7D%7D%5D%7D
[fig1d]:
  https://jbrowse.org/code/jb2/latest/?config=%2Fucsc%2Fhg38%2Fconfig.json&session=spec-%7B%22views%22%3A%5B%7B%22type%22%3A%22ProteinView%22%2C%22structures%22%3A%5B%7B%22uniprotId%22%3A%22P60484%22%7D%2C%7B%22uniprotId%22%3A%22O08586%22%7D%5D%2C%22transcriptId%22%3A%22NM_000314.8%22%2C%22sideBySide%22%3Atrue%2C%22connectedView%22%3A%7B%22assembly%22%3A%22hg38%22%2C%22loc%22%3A%22chr10%3A87%2C863%2C625-87%2C971%2C930%22%2C%22tracks%22%3A%5B%22hg38-ncbiRefSeqSelect%22%5D%7D%7D%5D%7D
[braf]: https://genomes.jbrowse.org/protein-browser/?gene=BRAF
