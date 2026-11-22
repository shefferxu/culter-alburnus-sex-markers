# Culter alburnus candidate sex-associated markers

Computational supporting records for “Development and preliminary evaluation of candidate sex-associated SNP and InDel markers in Culter alburnus”.

## Contents and evidence types

- R1: candidate identities, archived discovery-cohort genotype summaries and allele-frequency calculations.
- R2: reference-based gene and SNP positional annotations.
- R4: sequencing yields and QC for the 24 discovery fish. Sampling was in June 2025; the sequencing report is dated 21 August 2025.
- R5: comparative searches of publicly available sequences associated with the published LG4 marker.
- R6A/R6B: original, sample-resolved resequencing genotype calls for SNP2 and Marker10. These are computational calls from measured resequencing data, not Sanger results or predicted PCR band identities.
- R7: sample-to-SRA run mapping.
- [Computational methods](Computational_methods.md) and [table notes](Table_notes.md) preserve the archived workflow descriptions, definitions and interpretation limits. This repository does not claim that a new association analysis was performed.

The manuscript reports experimental performance using the author-reported Sanger genotypes and visible PCR band patterns. Experimental primer information and cohort summaries remain in the Supplementary Information. The computational records are preserved separately and have not been replaced with the reported laboratory results.

## Discovery-cohort discrepancy

At SNP2 (CM079600.1:13,556,322; REF G, ALT A), the archived sample m1, displayed as BY_M1, is GG (GT 0/0, DP 21, GQ 60, AD 21,0). This agrees between the combined and SNP-only VCFs. The authors report that they rechecked the laboratory records and confirmed AG for all 12 discovery males, including BY_M1. The original resequencing calls are retained unchanged. The cause of the discrepancy between the VCF and laboratory records remains unresolved.

Marker10 visible bands have not been sequenced; reference-based amplicon predictions do not establish the identity of the observed bands.

## Table index

| File | Original table heading | Data rows |
|---|---|---|
| [tables/R1_part_01.tsv](tables/R1_part_01.tsv) | Table S1A. Candidate identities and alleles — rows 1–10 | 10 |
| [tables/R1_part_02.tsv](tables/R1_part_02.tsv) | Table S1A. Candidate identities and alleles — rows 11–20 | 10 |
| [tables/R1_part_03.tsv](tables/R1_part_03.tsv) | Table S1A. Candidate identities and alleles — rows 21–30 | 10 |
| [tables/R1_part_04.tsv](tables/R1_part_04.tsv) | Table S1A. Candidate identities and alleles — rows 31–40 | 10 |
| [tables/R1_part_05.tsv](tables/R1_part_05.tsv) | Table S1A. Candidate identities and alleles — rows 41–50 | 10 |
| [tables/R1_part_06.tsv](tables/R1_part_06.tsv) | Table S1B. Discovery-cohort genotype counts — rows 1–20 | 20 |
| [tables/R1_part_07.tsv](tables/R1_part_07.tsv) | Table S1B. Discovery-cohort genotype counts — rows 21–40 | 20 |
| [tables/R1_part_08.tsv](tables/R1_part_08.tsv) | Table S1B. Discovery-cohort genotype counts — rows 41–50 | 10 |
| [tables/R1_part_09.tsv](tables/R1_part_09.tsv) | Table S1C. Recalculated frequencies and missingness — rows 1–20 | 20 |
| [tables/R1_part_10.tsv](tables/R1_part_10.tsv) | Table S1C. Recalculated frequencies and missingness — rows 21–40 | 20 |
| [tables/R1_part_11.tsv](tables/R1_part_11.tsv) | Table S1C. Recalculated frequencies and missingness — rows 41–50 | 10 |
| [tables/R2_part_12.tsv](tables/R2_part_12.tsv) | Table S2. Candidate-gene and selected-SNP positional audit | 3 |
| [tables/R2_part_13.tsv](tables/R2_part_13.tsv) | Table S2 continued. 9 targeted SNPs | 9 |
| [tables/R4_part_18.tsv](tables/R4_part_18.tsv) | Table S4A. Females — exact source-report sequencing statistics | 12 |
| [tables/R4_part_19.tsv](tables/R4_part_19.tsv) | Table S4A. Males — exact source-report sequencing statistics | 12 |
| [tables/R5_part_20.tsv](tables/R5_part_20.tsv) | Table S5A. Public assembly and marker-correspondence analysis | 7 |
| [tables/R5_part_21.tsv](tables/R5_part_21.tsv) | Table S5B. Selected HSPs of the predicted 1123-bp product against ASM4018292v1 | 4 |
| [tables/R6A_part_22.tsv](tables/R6A_part_22.tsv) | Table S6A. Individual archived SNP2 genotypes in the 24-fish discovery cohort. | 24 |
| [tables/R6B_part_23.tsv](tables/R6B_part_23.tsv) | Table S6B. Individual archived Marker10 genotypes in the 24-fish discovery cohort. | 24 |
| [tables/R7_part_24.tsv](tables/R7_part_24.tsv) | Table S7. Public SRA accessions for the 24 discovery fish (BioProject PRJNA1498283). | 24 |

## Sequence files and original calls

[Public-sequence comparison files](sequence_comparisons/README.md) preserve the predicted queries and existing BLAST outputs. [Targeted VCF excerpts](Archived_target_VCF_records.json) preserve the sample order and original site records for SNP2 and Marker10. These files are distinct from laboratory Sanger records.
