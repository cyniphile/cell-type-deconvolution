# Cell Type Deconvolution


Code for testing out various methods of cell-type deconvolution of bulk GEP data. The methods are described in the following papers:

- Abbas et al. 2009:  [Deconvolution of Blood Microarray Data Identifies Cellular Activation Patterns...](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0006098)
- Gong et al. 2011: [Optimal Deconvolution of Transcriptional Profiling Data Using Quadratic Programming...](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0027156) 
- Newman et al. 2015: [Robust enumeration of cell subsets from tissue expression profiles](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4739640/)


## Usage

Download and extract the data by running `ETL.ipynb`.  This will download the data from GEO and save it in the `data` directory. `Anaylsis.ipynb` contains the code for running the deconvolution methods and plotting the results.