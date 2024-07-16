# How to generate inputs for the eva-sub-cli 

The eva-sub-cli tool requires two inputs: 
- One or several valid VCF files
- Completed metadata spreadsheet
- list 3 Reference genome in fasta format

The VCF file must adhere to official VCF specifications, and the metadata spreadsheet provides contextual information about the dataset. In the following sections, we will examine each of these inputs in detail.

```
##fileformat=VCFv4.2
##INFO=<ID=DP,Number=1,Type=Integer,Description="Total Depth">
##FILTER=<ID=PASS,Description="All filters passed">
##FORMAT=<ID=GT,Number=1,Type=String,Description="Genotype">

```
