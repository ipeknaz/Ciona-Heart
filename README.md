<h1>Ciona Heart Single-Cell RNA Sequencing Analysis</h1>
<p>This analysis pipeline is made for 10x genomics 3' scRNASeq assembled using CellRanger or Kallisto. The pipeline uses Seurat v1.2 library for data analyses.</p>

<p>Filtering.Rmd contains preprocessing steps including removal of empty droplets, removal of ambeint RNA, removal of doublets and filtering of dead cells based on gene count and mitochondrial content. It also includes feature selection, logarithmic normalisation and principle component analysis steps.</p>

<p>Clustering.Rmd contains clustering analysis for the adult heart data and annotation of heart, blood and neuronal clusters based on differential gene expression analyses.</p>