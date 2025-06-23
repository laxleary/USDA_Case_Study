# USDA_Case_Study
Case Study for an Operation Data Analyst Role using USDA Data

This repository contains a Jupyter Notebook, [processing.ipynb](processing.ipynb) that contains the necessary code for automating the extraction and cleaning of data from the U.S. Department of Agriculture (USDA) site, preparing it for the Excel Workbook deliverable requested by the Case Study. The Case Study asks for a snapshot of the relationship between farmer age and the progression of time over the last five census cycles (2002, 2007, 2012, 2017, and 2022). In order to address this, I have pulled more than 200 tables' data from the USDA website and parsed them to extract relevant age data. 

Almost all extraction and cleaning can be done in the provided Jupyter Notebook, however conversion of the original PDF files to Excel files requires the use of Adobe Acrobat. This process can be automated using the Adobe Acrobat action wizard to convert hundreds of files at once. 

To meet GitHub file constraints, the raw data files are omitted from this repository, but running the Jupyter Notebook will download the files and save them within a folder called raw_tables, should the user wish to do so. 
