This repository provides a simple and reliable workflow for extracting barcodes.tsv.gz, features.tsv.gz, matrix.mtx.gz, and metadata.csv files from a .h5ad file generated in a Scanpy-based single-cell RNA-seq analysis pipeline. These outputs are formatted to be fully compatible with Seurat in R, enabling users to continue downstream analysis even when the original preprocessing and predictions were performed in Python.

Although many researchers find Seurat more intuitive and user-friendly, especially for visualization and exploratory analysis, there are cases where data is produced upstream in Scanpy, necessitating a conversion step. This repository aims to bridge that gap, ensuring seamless interoperability between Python-based and R-based single-cell workflows.

It is worth noting, however, that starting your analysis in Python using Scanpy can offer long-term advantages. Python is widely regarded as the preferred ecosystem for machine learning and artificial intelligence, and early familiarity with Python-based tools can make later transitions into advanced algorithmic or ML-driven approaches significantly smoother.

This toolset ensures you can work in Seurat when required—without losing the benefits of upstream Scanpy workflows—and helps maintain flexibility across computational ecosystems as your project evolves.
