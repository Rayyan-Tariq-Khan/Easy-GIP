# Easy-GIP
An execution and analysis workflow for GIP (Gaussian Interaction Profiler)

# Description
Easy-GIP is a Python notebook that lets you easily run [GIP](https://github.com/joerivstrien/gip-bio) as well as analyse the output in a graphical manner. It also contains a molecular weight calibrator for gel slices from a complexomic experimental run.

# Input formats
The following data exemplifying the input format are provided in the Input folder-

**Abundances.tsv** - This is the main input file. First column should have Protein IDs and rest of the column representing gel slices should have serially numbered headers.

**ExtendedAbundances.xlsx** (Optional) - This is an optional excel sheet, which may have extra identifiers, abundance values per slice in different formats, various other annotations. This is optionally used to re-add other protein name identifiers into the output file.

**Complexes.xlsx** (Optional) - This is an excel workbook where each sheet is a specific known protein complex. It may have multiple columns representing different types of protein identifiers as well as other annotations. This optionally used for complex analysis.

# How to Run

The workbook was originally scripted in Colab. Simply create an appropriately labelled folder in Google Drive, upload the notebook and the input files directory into the folder, and launch the notebook in Colab. Once it has been launched, mount your Google drive from within the Colab environment and follow the cell wise instructions.

The notebook may also be used in other Python notebook environments (eg- Jupyter or Anaconda notebook).
