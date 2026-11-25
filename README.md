# Mycobacterium tuberculosis (MDR-TB) Drug-Resistance pipeline

An end-to-end NGS genomic variant calling and functional annotation pipeline identifying drug-resistance mutatations in *Mycobacterium tuberculosis* (H37Rv reference 'NC_000962.3').

## Tools & Workflow
**Quality Control & Trimming:** 'Fastqc', 'fastp', 'MultiQC'
**Alignment & Processing:** 'BWA_MEM', 'Samtools'
**Variant Calling & Filtering:** 'bcftools'
**Functional Annotation:** 'SnpEff' ('Mycobacterium_tuberculosis_h37rv')

## Key Finding
successfully detected and annotated the clinically critical **'rpoB' ('p.ser450Leu' / 'c.1349C>T')** missense mutation at genome position '761155', associated with Rifampicin antibiotic resistance (MDR_TB).
