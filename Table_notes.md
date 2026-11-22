# Computational table descriptions

Former Supplementary Tables S1, S2, S4, S5, S6 and S7 are preserved here as Repository Tables R1, R2, R4, R5, R6 and R7. Historical cross-references below retain the numbering of the source revision. Current experimental Supplementary Tables S1 and S2 correspond to former S3 and S8.

Table S1. Chr19 candidate-marker panel
Reference: GCA_040182925.1 (ASM4018292v1); chromosome accession CM079600.1. Positions are 1-based. “Inside” indicates 10,500,000–14,200,000 bp inclusive. Row keys S01–S50 link the 3 parts. Historical IDs are preserved as identifiers; InDel length is calculated from the displayed REF and ALT and may differ from the length embedded in an old ID.
SNP2 corresponds to S43 at Chr19:13,556,322; SNP_02_13556322 and Fig4_marker_02_13556322 are source-record aliases for this coordinate. Marker10 corresponds to S10, InDel_marker_010_Chr19_30348951_insertion_22bp. Historical identifiers are retained for traceability and do not refer to current figure numbering. Of these candidates, 15 lie within the provisional interval; all 10 InDels lie outside it. Primer-coordinate matching does not by itself confirm the identity of an experimental band.
Table S1A. Candidate identities and alleles — rows 1–10

Table S1A. Candidate identities and alleles — rows 11–20

Table S1A. Candidate identities and alleles — rows 21–30

Table S1A. Candidate identities and alleles — rows 31–40

Table S1A. Candidate identities and alleles — rows 41–50

Table S1B. Discovery-cohort genotype counts — rows 1–20
M = phenotypic males; F = phenotypic females; 12 individuals per sex. 0/0 = REF homozygote; 0/1 = heterozygote; 1/1 = ALT homozygote; ./. denotes missing calls (shown as “missing” below). Counts are transcribed from the archived candidate table, not re-called genotypes.

Table S1B. Discovery-cohort genotype counts — rows 21–40
M = phenotypic males; F = phenotypic females; 12 individuals per sex. 0/0 = REF homozygote; 0/1 = heterozygote; 1/1 = ALT homozygote; ./. denotes missing calls (shown as “missing” below). Counts are transcribed from the archived candidate table, not re-called genotypes.

Table S1B. Discovery-cohort genotype counts — rows 41–50
M = phenotypic males; F = phenotypic females; 12 individuals per sex. 0/0 = REF homozygote; 0/1 = heterozygote; 1/1 = ALT homozygote; ./. denotes missing calls (shown as “missing” below). Counts are transcribed from the archived candidate table, not re-called genotypes.

Table S1C. Recalculated frequencies and missingness — rows 1–20
AF = (n0/1 + 2n1/1)/(2ncalled). ΔAF = AFfemale − AFmale. Frequencies use non-missing diploid calls; missingness uses 12 individuals per sex or 24 pooled. Signed and absolute differences are reported separately; 12 signed values are negative. Reference/alternate coding does not identify X/Y or Z/W ancestry, and allele-frequency differences alone do not establish sex linkage.

Table S1C. Recalculated frequencies and missingness — rows 21–40
AF = (n0/1 + 2n1/1)/(2ncalled). ΔAF = AFfemale − AFmale. Frequencies use non-missing diploid calls; missingness uses 12 individuals per sex or 24 pooled. Signed and absolute differences are reported separately; 12 signed values are negative. Reference/alternate coding does not identify X/Y or Z/W ancestry, and allele-frequency differences alone do not establish sex linkage.

Table S1C. Recalculated frequencies and missingness — rows 41–50
AF = (n0/1 + 2n1/1)/(2ncalled). ΔAF = AFfemale − AFmale. Frequencies use non-missing diploid calls; missingness uses 12 individuals per sex or 24 pooled. Signed and absolute differences are reported separately; 12 signed values are negative. Reference/alternate coding does not identify X/Y or Z/W ancestry, and allele-frequency differences alone do not establish sex linkage.

Table S2. Candidate-gene and selected-SNP positional audit
Coordinates and locus tags refer to the GFF accompanying GCA_040182925.1. Functional labels are homology-based predictions. The 118-gene summary includes functional assignments for 5 genes; the other 113 lack assignments in that summary. Alignment coverage and independent domain validation are unavailable.

The THAP assignment has substantially weaker sequence identity and should not be treated as confirmed orthology or an independently verified domain architecture.
Table S2 continued. 9 targeted SNPs

None of these 9 SNPs overlaps the bodies of the 3 highlighted genes. SNP2 is approximately 188,404 bp beyond the end of ABG768_011658. Gene-window labels are screening labels, not evidence of an intragenic or causal variant. Transcript intersection identifies positional context only; regulatory effects and consequences of other interval variants remain untested.

Table S4. Sequencing quality-control records
Sequencing quality statistics are reported for the 24 discovery fish (12 females and 12 males). F and M denote phenotypic females and males, respectively. The sequencing report is dated 21 August 2025.
Resequencing generated 654,080,035,464 raw bases (654.080 Gb) and 641,436,346,377 clean bases (641.436 Gb), corresponding to 2,165,827,932 raw and 2,147,073,949 clean read pairs. Counts are interpreted as read pairs based on the reported base-to-count relationship.
Q20 was not reported. Mapped depths for ASM4018292v1 are given in Table 1, with depth-calculation methods described in Supplementary Method SM1.
Table S4A. Females — exact source-report sequencing statistics

Counts are interpreted as read pairs. Base totals are exact source values; clean Q30 and GC are percentages. These QC values are not reference-mapped depth statistics.
Table S4A. Males — exact source-report sequencing statistics

Counts are interpreted as read pairs. Base totals are exact source values; clean Q30 and GC are percentages. These QC values are not reference-mapped depth statistics.
Table S5A. Public assembly and marker-correspondence analysis

Source: Ren et al. (2025), doi:10.1093/gigascience/giae117; Figshare doi:10.6084/m9.figshare.24125487.v1 (released 22 September 2023). The downloaded FASTA and GFF3 MD5 checksums are 8ca0f041d792d9db2235ac88f790240b and 8e79e44941470e3a97eebd9e81db1b99, respectively. Coordinates are 1-based inclusive. The predicted product matches the primer ends and stated length; its complete sequence has not been compared with a sequenced experimental product from Zhang et al. (2026).
Table S5B. Selected HSPs of the predicted 1123-bp product against ASM4018292v1

Query coverage = HSP query span / 1123 × 100; alignment columns containing gaps are not used as query span. The first 3 rows are from sensitive blastn; the fourth is the highest-scoring product hit under masked megablast with identity ≥ 90%. Dispersed HSPs are not a unique locus placement. The 40 extended-flank tiles yielded 5 passing HSPs from 2 tiles, on Chr1, Chr4, Chr11, Chr16 and Chr22, with no coherent two-sided anchor and none on Chr19. These results establish neither overlap nor non-overlap with Chr19:10.5–14.2 Mb.
Table S6A. Individual archived SNP2 genotypes in the 24-fish discovery cohort.

F and M denote phenotypic females and males. Display identifiers use uppercase letters; VCF sample names are the corresponding lowercase F/M identifiers without the BY_ prefix. GT is the original diploid genotype; DP is depth; GQ is genotype quality; AD lists reference and alternate allele read counts. No calls have been masked or replaced. SNP2: CM079600.1:13,556,322; REF = G, ALT = A. GT 0/0, 0/1 and 1/1 correspond to GG, AG and AA.
Table S6B. Individual archived Marker10 genotypes in the 24-fish discovery cohort.

F and M denote phenotypic females and males. Display identifiers use uppercase letters; VCF sample names are the corresponding lowercase F/M identifiers without the BY_ prefix. GT is the original diploid genotype; DP is depth; GQ is genotype quality; AD lists reference and alternate allele read counts. No calls have been masked or replaced. Marker10: CM079600.1:30,348,951; REF = T, ALT = TTGCTATGTCCGACAAGCCCTGC (22-bp insertion). GT 0/0, 0/1 and 1/1 denote reference homozygotes, heterozygotes and insertion homozygotes. These sequence calls do not identify the visible gel bands.
Table S7. Public SRA accessions for the 24 discovery fish (BioProject PRJNA1498283).

The deposited read-pair and base totals match the clean sequencing yields in Table S4: 2,147,073,949 pairs and 641,436,346,377 bp. Sample names are displayed with uppercase F/M; the NCBI sample aliases use lowercase f/m. The archived reads were generated on an Illumina NovaSeq X Plus. This accession refers to the discovery-cohort resequencing data, not the 48-fish validation assays or a reference assembly.
