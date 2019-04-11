# biomarker-discovery-of-cp1-compound-response
what's the cp1 compound?
CP1 compound is an inhibitor which we screened from small molecue library, it can target 
transcriptional factor TEAD to inhibit its transcriptional activity, whether this compound can also target other proteis is unknown.
Here, we try to answer two questions:
The first one is what's the biomarker of CP1 compount response, or whether some genetic alterations are predictive of CP1 
response in human cancer?
The second question is whether CP1 has other targets?

Recently some studies reported that genomic pertubations including mutations, copy number alterations and also gene expression 
signature are predictive of drug response, here, we firstly utilized public omic database called CCLE to look for 
some potential biomarkers which can be used to predict our inhibitor response.
Furthermore we also used gene dependency score  to discover new CP1 targets.

The basic protocol is :
Firstly we plotted the IC50 distribution by cancer type, then we selected the most sensitive cancer type for further study.
In order to discover new targets, gene dependency data was downloaded from Broad Institute, then we utilize the pearson 
correlation statistics to find out which gene's dependency score is positively correlated with IC50.








