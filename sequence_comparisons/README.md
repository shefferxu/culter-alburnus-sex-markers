# Public marker sequence comparisons

These files contain the existing reference-based LG4 marker comparison. They are not experimental amplicon sequences.

- `lg4_20261008_queries.fasta`: the predicted 1123-bp marker product, immediate flanks and combined query from the public Ren et al. assembly.
- `lg4_20261008_100kb_tiles.fasta`: the extended flanks split into 5-kb tiles.
- `lg4_20261008_blastn.tsv.gz`: sensitive blastn results against ASM4018292v1.
- `lg4_20261008_megablast_masked.tsv.gz`: masked megablast results.
- `lg4_20261008_100kb_tiles.tsv`: passing extended-flank hits.

TSV columns, without a header, are `qseqid sseqid pident length mismatch gapopen qstart qend sstart send evalue bitscore qlen qcovhsp qcovs`. Coordinates follow BLAST conventions. Parameters and source assemblies are described in Computational_methods.md, SM5–SM6. Distributed matches do not establish a unique LG4-to-Chr19 correspondence. The checksum manifest reports hashes of the original uncompressed files.
