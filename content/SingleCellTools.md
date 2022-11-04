---
title: "SingleCellTools"
menu: "main"
draft: false
---

Selected tools for single-cell and spatial transcriptomics.

### scRNA-seq
- ALRA: [Zero-preserving imputation](https://www.nature.com/articles/s41467-021-27729-z)
- HotSpot: [identifies informative gene modules](https://hotspot.readthedocs.io/en/latest/) ([pip install hotspotsc==0.9.1](https://yoseflab.github.io/Hotspot/))
- SCENIC/pySCENIC: [Single-cell regulatory network and clustering](https://scenic.aertslab.org/)
- SpaOTsc: [spatial optimal transport for SC data](https://www.nature.com/articles/s41467-020-15968-5)([py](https://github.com/zcang/SpaOTsc))
- PROGENy & decoupleR: [inference of pathway activities](https://saezlab.github.io/progeny/articles/progeny.html) (human & mouse)
- MetaNeighbor: [characterizing the replicability of cell types across datasets](https://www.nature.com/articles/s41596-021-00575-5) ([R](https://www.bioconductor.org/packages/release/bioc/html/MetaNeighbor.html))
- SAMap: [mapping cell atlas manifolds across species](https://github.com/atarashansky/SAMap) (py)
- MAGIC: [imputing missing values and restoring the structure of single-cell data](https://www.krishnaswamylab.org/projects/magic) ([R & py](https://github.com/KrishnaswamyLab/MAGIC))

***

### spatial transcriptomics
- Giotto: [toolbox for integrative analysis of spatial data](https://rubd.github.io/Giotto_site/)
- SSAM (lite): [segmentation-free inference of cell types](https://www.nature.com/articles/s41467-021-23807-4)
- SpatialDE: [identification of spatially variable genes](https://github.com/Teichlab/SpatialDE) (py)
- Spark: [Statistical analysis of spatial expression patterns](https://github.com/xzhoulab/SPARK)
- BayesSpace: [Clustering and Resolution Enhancement of Spatial Transcriptomes](http://www.bioconductor.org/packages/release/bioc/vignettes/BayesSpace/inst/doc/BayesSpace.html)

***

### Integration of single cell data

#### Benchmarking analysis

- [Benchmarking spatial and single-cell transcriptomics integration methods for transcript distribution prediction and cell type deconvolution](https://www.nature.com/articles/s41592-022-01480-9)

#### Selected tools
- PASTE: [Alignment and integration of spatial transcriptomics data from multiple adjacent tissue slices](https://www.nature.com/articles/s41592-022-01459-6) ([Python](https://github.com/raphael-group/paste))
- GLUE: [Multi-omics single-cell data integration and regulatory inference with graph-linked embedding](https://www.nature.com/articles/s41587-022-01284-4) ([Python/R](https://github.com/gao-lab/GLUE))
- CellTrek: [Spatial charting of single-cell transcriptomes in tissues](https://www.nature.com/articles/s41587-022-01233-1) ([R](https://github.com/navinlabcode/CellTrek))
- Tangram: [aligns sc/snRNA-seq data to spatial data](https://www.nature.com/articles/s41592-021-01264-7) ([Python](https://github.com/broadinstitute/Tangram))
- SPOTlight: [integration of Spatial Transcriptomics with scRNA-seq data to infer the location of cell types and states](https://academic.oup.com/nar/article/49/9/e50/6129341) ([R](https://github.com/MarcElosua/SPOTlight))
- Harmony: [Fast, sensitive and accurate integration of single-cell data](https://www.nature.com/articles/s41592-019-0619-0) ([R](https://github.com/immunogenomics/harmony))
- [cell2location](https://cell2location.readthedocs.io/en/latest/): [Cell2location maps fine-grained cell types in spatial transcriptomics](https://www.nature.com/articles/s41587-021-01139-4) ([Python](https://github.com/BayraktarLab/cell2location/))

***

### Single cell data interactive visualisation

- [Comparison of visualization tools for single-cell RNAseq data](https://academic.oup.com/nargab/article/2/3/lqaa052/5877814)
- [Seurat interactive plotting](https://satijalab.org/seurat/articles/visualization_vignette.html#interactive-plotting-features-1) (`HoverLocator()`)
- [Plotly.R](https://plotly.com/r/)

### Automated cell type annotation [Turorial](https://www.nature.com/articles/s41596-021-00534-0)

#### Reference-based

- RCTD/spacexr: [Robust decomposition of cell type mixtures in spatial transcriptomics](https://github.com/dmcable/spacexr) (R)
- scmap: [unsupervised projection of scRNA-seq data](https://scmap.sanger.ac.uk/han2018/) (R)
- SingelR: [Reference-based cell type annotation](http://bioconductor.org/books/release/SingleRBook/introduction.html) 
- CelliD: [clustering-free extraction of per-cell gene signatures](https://www.nature.com/articles/s41587-021-00896-6) ([R](https://github.com/RausellLab/CelliD))
- ScType: [fully-automated and ultra-fast cell-type identification](https://www.nature.com/articles/s41467-022-28803-w) ([R](https://github.com/IanevskiAleksandr/sc-type))
- SciBet: [Single Cell Identificator Based on E-test](http://scibet.cancer-pku.cn/index.html) ([R](http://scibet.cancer-pku.cn/installation.html))

#### Marker-based

- AUCell: [cells with active gene sets](https://www.bioconductor.org/packages/devel/bioc/vignettes/AUCell/inst/doc/AUCell.html)
- GSEA/GSVA: [gene set enrichment analysis](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-14-7) ([test](https://github.com/jdime/scRNAseq_cell_cluster_labeling)) (for clusters)
- SCINA: [Semi-Supervised Cell Type Detection and Assignment](https://lce.biohpc.swmed.edu/scina/) ([R](https://github.com/jcao89757/SCINA)) (for cells)
- MACA: [marker-based automatic cell-type annotation](https://github.com/ImXman/MACA) / [ScTypeDB: cell-type marker database](https://www.nature.com/articles/s41467-022-28803-w#Abs1)

#### Knowledge-based clustering and annotation

- UNIFAN: [using known gene sets + neural network](https://genome.cshlp.org/content/early/2022/06/28/gr.276609.122.long)  
 

***

### Other tools

- sceasy: easy conversion of different single-cell data formats ([R](https://github.com/cellgeni/sceasy))

