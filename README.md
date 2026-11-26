# yaronlab.tools

**Live site: [yaronlab.tools](https://yaronlab.tools)**

Research tools from the Yaron lab.

## Flagship: benchsiDE

**[benchsiDE](https://www.benchside.org)** (benchside.org) is the lab's tool for
differential expression and cross-dataset analysis of bulk RNA-seq counts, with
no R and no install: filtering, TMM normalization, limma moderated-t and voom with
covariates and factorial designs, gene-set and co-expression tests, random-effects
meta-analysis across datasets, and replication of a signature in independent data
including across species by homology. Source and validation:
[github.com/jyaron/benchsiDE](https://github.com/jyaron/benchsiDE).

benchsiDE is a separate project with its own domain and repository; it is featured
on the landing page but is not part of this site's source.

## Utilities

Single-file tools hosted under yaronlab.tools. Each is one self-contained HTML
file with no dependencies, no accounts, and no ads. The cloning and protein-
engineering tools share a bundled sequence-logic core (genetic code, codon usage,
nearest-neighbor Tm, degenerate codons) inlined into each page.

### Cloning & protein engineering

| URL | Tool |
|---|---|
| [/construct](https://yaronlab.tools/construct/) | Plasmid construct builder: fusion and affinity tags, fluorescent proteins and self-labeling tags, linkers, codon optimization for mammalian or E. coli expression, Kozak and Shine-Dalgarno signals, restriction-site avoidance, cited methods text, GenBank export |
| [/mutate](https://yaronlab.tools/mutate/) | Site-directed mutagenesis primer designer: substitutions, insertions, deletions; nearest-neighbor Tm, host-optimized codons, overlapping or back-to-back styles, order table and methods text |
| [/scan](https://yaronlab.tools/scan/) | Scanning mutagenesis designer: alanine, glycine, or saturation scans across a position range; per-position primers, degenerate codons, library complexity |
| [/degenerate](https://yaronlab.tools/degenerate/) | Degenerate codon designer: minimal IUPAC codon for a chosen amino-acid set, codon decoding, library diversity |

### Sequence utilities

| URL | Tool |
|---|---|
| [/dna](https://yaronlab.tools/dna/) | DNA sequence toolbox: cleanup, reverse complement, DNA to RNA, case conversion, line wrapping, position numbering |

### Figures & data

| URL | Tool |
|---|---|
| [/figure](https://yaronlab.tools/figure/) | Multi-panel figure layout manager: justified packing with no wasted whitespace, auto-trim, row grouping, panel lettering, project save/load, and export to PNG, TIFF, PPTX, and SVG at 300 or 600 DPI in RGB or CMYK. Arranges finished panels; does not edit inside them |

### Writing & publishing

| URL | Tool |
|---|---|
| [/credit](https://yaronlab.tools/credit/) | CRediT author contribution statement generator: paste an author list, check roles in a grid, copy a journal-ready statement |
| [/authors](https://yaronlab.tools/authors/) | Author and affiliation block builder: auto-numbered affiliations, corresponding-author and equal-contribution marks, ORCID iDs |
| [/statements](https://yaronlab.tools/statements/) | Submission statements: conflict-of-interest, data availability, funding, and ethics, generated from a few fields |
| [/wordcount](https://yaronlab.tools/wordcount/) | Manuscript word counter: live counts with reference/caption/citation exclusions, checked against common journal limits |
| [/abbrev](https://yaronlab.tools/abbrev/) | Abbreviation checker: find acronyms, verify define-at-first-use, flag undefined/unused, build the abbreviations table |

## Offline use

Because every utility is one dependency-free file, you can save any tool's
`index.html` (or download it from this repo) and it will keep working
locally, with no internet connection.

## Feedback

Spotted a bug or have an idea for a tool? Open an issue on this repo.
