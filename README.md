# REKN_blocker_dvlpmt
Bioinformatic scripts associated with the Red Knot blocking primer development study

# Required software
FastQC, MultiFastQC, cutadapt, BLAST+, R (packages dada2, data.table)

# Required input files
SRA accessions links <link here>
MIDORI2 UNIQ NUC GB260 CO1 BLAST reference library <link here>

# Files provided 
05_REFDB_dada2_COI_2025-11-17.fasta.zip - Maine COI reference library for dada2 taxonomy assignment (need to unzipped first)

# Blocker test run read processing
a_metabarcoding_EG301-583_LerayCOI.Rmd - script for raw read processing
b_ASV_processing_EG301-583_LerayCOI.Rmd - script for parsing studies, de-contaminating, and resolving taxonomies
EG301-584_metadata_TrawlandSeamountandRedKnotTest_LerayCOITarEuk18SMiFish12SCeph18S.csv - sample metadata

# Extraction Kit test run
a_basic_metabarcoding_RedKnotExtractionTest.Rmd - script for raw read processing
b_ASV_functions_RedKnotExtractionTest.Rmd - script for de-contaminating and resolving taxonomies
EG_RedKnotExtractionTest.csv - sample metadata

# Manomet REKN survey run
a_basic_metabarcoding_EG601-784_Manomet_LerayCOI.Rmd - script for raw read processing
b_ASV_functions_EG601-784_Manomet_LerayCOI.Rmd - script for de-contaminating and resolving taxonomies
EG601-784_metadata_RedKnotManomet_LerayCOI.csv - sample metadata



