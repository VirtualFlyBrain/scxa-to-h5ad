# scxa-to-h5ad

Aims: 
1. develop code (python functions and notebooks) that coverts Single Cell Expression Atlas (SCXA) matrix and metadata files into CxG compliant* AnnData format.
2. Write notebooks that show how we can use VFB_connect queries for expression data to retrieve SCXA dataset identifiers (e.g. E-CURD-134), using these to retrieve and convert SCXA files to CxG h5ad. 

\* Strictly, to be compliant would require limiting to specific versions of CL and Uberon + human and mouse stage ontologies. However, we will relax this a little by allowing ontologies that specialise CL and Uberon.


