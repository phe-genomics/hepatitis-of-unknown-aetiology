# hepatitis-of-unknown-aetiology

## Introduction

This site is intended to help coordinate international sharing of sequencing data and limited metadata associated with viral genome sequences linked to the investigation of hepatitis of unknown aetiology.

## Suggested metadata fields

|                         |                                                        |                                                                                                                                                  | 
|-------------------------|--------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------| 
| Field                   | Description                                            | Reason                                                                                                                                    | 
| anonymous_biosample_id  | Anonymised sample identifier                           | A public label to permit communication of results (entirely randomly generated ID)                                                               | 
| biosample_source_id     | Used to identify mutliple samples from same individual | To permit cases versus genome replicates to be distinguished (simply a pointer to anonymous_biosample_id so no additional patient info involved) | 
| collection_date         | YYYY-MM                                                | For phylogenetic reconstructions relying on timestamps                                                                                           | 
| received_date           | YYYY-MM                                                | In case collection_date unavailable                                                                                                              | 
| clinical_presentation   | Hepatitis,Non-hepatitis                                | To distinguish cases vs controls for international analysis                                                                                      | 
| sample_site             | Respiratory,Faecal,Tissue,Stool,Blood,Plasma           | For analysis of genetic tropism                                                                                                                  | 
| sample_type             | Swab,BAL,Aspirate,Biopsy,Other                         | To permit analysis of confounders associated with sampling method                                                                                | 
| age                     | age bands (0-4, 5-9, 10-15, etc.)                      | To distinguish cases vs controls for international analysis                                                                                      | 
| adm1_country            | England/Scotland/Wales/Northern Ireland                | For genomic epidemiology analysis e.g. phylogeography                                                                                            | 
| enrichment_protocol     | Details of enrichment protocol                         | To permit analysis of technical confounders associated with enrichment protocols                                                                 | 
| library_protocol        | Details of sequencing library construction             | To permit analysis of technical confounders associated with library protocol                                                                     | 
| sequencing_protocol     | Details of sequencing                                  | To permit analysis of technical confounders associated with sequencing protocol                                                                  | 
| bioinformatics_protocol | Detail of bioinformatics protocol                      | To permit analysis of technical confounders associated with bioinformatics protocol                                                              | 

## Sharing website

We are recommending the use of INSDC databases such as Genbank for rapid sharing of sequence data. We will provide a mapping between the above fields and Genbank source identifiers shortly.

For ultra-rapid sharing please feel free to link to official sources of sequences and metadata via the Github issues page here.



Nick Loman, UKHSA 2022-05-06.



