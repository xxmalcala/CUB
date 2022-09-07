# CUB
**C**odon **U**sage **B**ias
## Description
This repo contains scripts to calculate the effective number of codons (EN<sub>c</sub>) based upon [Wright (1990)](https://pubmed.ncbi.nlm.nih.gov/2110097/). This includes options to plot the relationship between EN<sub>c</sub> with GC3 at 4-fold degenerate codons and options to account for non-universal genetic codes (supporting some of [NCBI's genetic codes](https://www.ncbi.nlm.nih.gov/Taxonomy/Utils/wprintgc.cgi)).

Other scripts include aapproaches to assess alternative genetic codes, as well as other *in prep* scripts that can be used at your own peril! Note that this README will be updated with more discrete information as time permits (still populating/migrating to personal repo).

## Dependencies
- **cbias.py**
  + [Python 3.6+](https://www.python.org/downloads/)
  - [BioPython](https://biopython.org/wiki/Download)

+ **eval_gencode.py**
  - [Python 3.6+](https://www.python.org/downloads/)
  - [BioPython](https://biopython.org/wiki/Download)
  - [DIAMOND](https://github.com/bbuchfink/diamond)
  
## Planned Updates
- [ ] Fix plotting options (cbias.py).
- [ ] Upload eval_gencode.py's database.
- [ ] Update with usage information.
- [ ] Fix STOP codon assessment issue (eval_gencode.py)

### When using these tools in published research, please cite:

**Codon usage bias**
-   Sterner ES, Maurer-Alcalá XX, Cote-L'Heureux A, Katz LA. *in prep*. \"Extreme codon usage bias reflects emergent genome properties\"

**Alternative genetic codes**
-   Yan Y, Maurer-Alcalá XX, Knight R, Kosakovsky-Pond SL, Katz LA. 2019. \"Single-cell transcriptomics reveal a correlation between genome architecture and gene family evolution in ciliates\". *_mBio_* **10(6)**: e02524-19. [https://doi.org/10.1128/mBio.02524-19](https://https://doi.org/10.1128/mBio.02524-19)
