# PrimerScope

Design Sanger and nested PCR primers around a human variant, and check any primer for SNPs.

**Open it:** https://clairevaltin.github.io/PrimerScope/

## What it does

- **Sanger design** – enter a variant and get ranked primer pairs around it, designed with Primer3
- **Nested PCR** – an outer pair for the first PCR and an inner pair to sequence with
- **Specificity** – optional genome-wide check of each pair with NCBI Primer-BLAST
- **SNP avoidance** – primers never sit on a gnomAD v4 variant above the frequency you set
- **Primer check** – paste existing primers or sequences (up to 20) and find dbSNP and gnomAD variants under them; sequences are placed near a gene you name, or genome-wide with UCSC BLAT
- Accepts almost any variant format: `NM_…:c.`, `GENE c.`, intronic and UTR positions, del/dup/ins/delins, genomic coordinates and rsIDs (GRCh38)

## How to use

Open the link above. Nothing to install. A built-in FAQ explains each setting.

## Disclaimer

**This tool is NOT validated for clinical or diagnostic use.** It is provided for research and educational purposes only, without any warranty.

## License & citation

© 2026 Rehioui Soufiyan. All rights reserved.

You're welcome to explore this code. If you'd like to use, adapt, or share it, please get in touch first: rehiouisoufiyan@gmail.com

If this work helps you, please cite it or link back to this repository.
