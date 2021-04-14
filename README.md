# AB1_tracefile_pipeline: Linux-based pipeline to detect variants from Sanger sequence AB1 trace files
This pipeline describes the installation and use of multiple open source tools to detect variants from Sanger sequence AB1 trace files.

### Install ###
The This pipeline was demonstrated using the Ubuntu Linux workstation equipped with AMD Ryzen 5 processors and 8GB of RAM. Therefore its recommended use is on the Ubuntu-Linux terminal. This can be dual-installed here: https://ubuntu.com/.

### Input files ###
This pipeline accepts AB1 files that have ben converted to FASTA format using https://www.ebi.ac.uk/Tools/sfc/emboss_seqret/. 

### Output files ### 
This pipeline will produce a range of files, and if the location of where these files should be deposited is not given they will be produced in the current working directory.
Some of the output files include SAM, BAM, VCF, and sorted BAM files. 

