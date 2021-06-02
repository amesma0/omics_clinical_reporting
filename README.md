# omics_clinical_reporting
Clinical_Report_Design_for_omics_integration

#Goal

To develop a tool to facilitate reporting of multiomics data. The tool generates two reports, one is aimed for clinical use and the second aimed for researchers, informing the interpretation of genetic variants pertaining to the gene provided by the user.

#Introduction

Many multi-omics datasets of different diseases have been generated and the availability of many new analytical tools are now for the first time allowing the combining of all of these resources in several ways in clinical reporting. The identification of biologically meaningful targets using multi-omics data will allow for better stratification, more targeted treatments, and a greater understanding of disease mechanisms.

#Installation 

Omics-ReportR is available in GitHub https://github.com/collaborativebioinformatics/omics_clinical_reporting 

#Methods

#Implementation 

##Inputs

currently planning to have inputs come from a SQLITE table

##Outputs

The tool generates two reports, one is aimed for clinical use and the second aimed for researchers, informing the interpretation of genetic variants pertaining to the gene provided by the user.



#Operation

Omics-ReportR requires a VCF file that includes all the variants that should be genotyped (Flow chart).

#Flow Chart


#Results

1-EXPERT VIEW
  Gene-level summary in addition to information about associated disease.
  Links to the gene's page on OMIM, GTEx, gnomAD.
  A dynamic table with the annotated variants overlapping the gene.
  A graph with showing summary of all the variants within the gene.
  Chromosome location.
  Table showing summary of gene expression analysis.
  Tissue specific gene expression summary table.
  PRS score
  SV data summary 
 
 2- Patients, non-specialist clinicians
genomics data simplification, which genes are overexpressed, how much of a gene is overexpressed (how the cohort respond to a certain treatment regarding this gene), In the gene level summary of the most pathogenic variants identified, each column in the dynamic table can be sorted and searched dynamically, and all data used by the app is available for download in tab-delimited files. By default, allele frequency is reported based on dbVar and gnomAD genomes and exomes. 
The tools provide Link to local genetic counselor, link to clinical trials related to the disease and the gene of interest and five most recent publications about the identified gene.

