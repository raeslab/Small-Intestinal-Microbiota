# Small intestinal microbiota – companion website and supplementary data

Companion website and supplementary data for:

> Zoetendal EG, Raes J, van den Bogert B, Arumugam M, Booijink CCGM, Troost FJ, Bork P, Wels M, de Vos WM, Kleerebezem M. **The human small intestinal microbiota is driven by rapid uptake and conversion of simple carbohydrates**. *The ISME Journal* 6(7):1415–1426 (2012). [doi:10.1038/ismej.2011.212](https://doi.org/10.1038/ismej.2011.212)

It contains the assembled contigs, predicted genes and proteins, and processed reads of three small-intestinal (ileostomy effluent) metagenomes (samples 1A, 1M, A) and one metatranscriptome (cDNA).

**Website:** https://raeslab.github.io/Small-Intestinal-Microbiota/ (GitHub Pages, served from `docs/` on the `main` branch)

This material was previously hosted on the Raes Lab website at `raeslab.org/companion/suppdata/` and has been migrated to this repository.

## Contents

| Path | Size | Description |
|------|------|-------------|
| `supplementary/README.txt` | 494 B | Description of the samples and file types. |
| `supplementary/contigs/1A.contig2read.gff` | 13.2 MB | Reads mapped on the contigs – sample 1A (MC6.MG1) |
| `supplementary/contigs/1A.contigs.fa` | 21.7 MB | Contigs and singletons – sample 1A (MC6.MG1) |
| `supplementary/contigs/1M.contig2read.gff` | 12.9 MB | Reads mapped on the contigs – sample 1M (MC6.MG2) |
| `supplementary/contigs/1M.contigs.fa` | 21.7 MB | Contigs and singletons – sample 1M (MC6.MG2) |
| `supplementary/contigs/A.contig2read.gff` | 25.3 MB | Reads mapped on the contigs – sample A (MC6.MG3) |
| `supplementary/contigs/A.contigs.fa` | 20.4 MB | Contigs and singletons – sample A (MC6.MG3) |
| `supplementary/contigs/cDNA.contig2read.gff` | 281 KB | Reads mapped on the contigs – sample cDNA (MC5.MG4) |
| `supplementary/contigs/cDNA.contigs.fa` | 1.9 MB | Contigs and singletons – sample cDNA (MC5.MG4) |
| `supplementary/dutch_gut.tar.gz` | 115.7 MB | Archive with all supplementary files |
| `supplementary/genes/1A.contig2gene.gff` | 7.4 MB | Genes predicted on the contigs – sample 1A (MC6.MG1) |
| `supplementary/genes/1A.gene.fa` | 18.2 MB | Nucleotide sequences of protein-coding genes – sample 1A (MC6.MG1) |
| `supplementary/genes/1A.protein.fa` | 8.1 MB | Protein sequences – sample 1A (MC6.MG1) |
| `supplementary/genes/1M.contig2gene.gff` | 7.0 MB | Genes predicted on the contigs – sample 1M (MC6.MG2) |
| `supplementary/genes/1M.gene.fa` | 17.8 MB | Nucleotide sequences of protein-coding genes – sample 1M (MC6.MG2) |
| `supplementary/genes/1M.protein.fa` | 7.9 MB | Protein sequences – sample 1M (MC6.MG2) |
| `supplementary/genes/A.contig2gene.gff` | 6.0 MB | Genes predicted on the contigs – sample A (MC6.MG3) |
| `supplementary/genes/A.gene.fa` | 16.5 MB | Nucleotide sequences of protein-coding genes – sample A (MC6.MG3) |
| `supplementary/genes/A.protein.fa` | 7.2 MB | Protein sequences – sample A (MC6.MG3) |
| `supplementary/genes/cDNA.contig2gene.gff` | 390 KB | Genes predicted on the contigs – sample cDNA (MC5.MG4) |
| `supplementary/genes/cDNA.gene.fa` | 1.5 MB | Nucleotide sequences of protein-coding genes – sample cDNA (MC5.MG4) |
| `supplementary/genes/cDNA.protein.fa` | 614 KB | Protein sequences – sample cDNA (MC5.MG4) |
| `supplementary/processed_reads/1A.reads.fa` | 47.7 MB | Processed reads – sample 1A (MC6.MG1) |
| `supplementary/processed_reads/1M.reads.fa` | 50.9 MB | Processed reads – sample 1M (MC6.MG2) |
| `supplementary/processed_reads/A.reads.fa` | 89.5 MB | Processed reads – sample A (MC6.MG3) |
| `supplementary/processed_reads/cDNA.reads.fa` | 1.9 MB | Processed reads – sample cDNA (MC5.MG4) |

Total supplementary data: 521.7 MB.

Note: the original `README.txt` mentions `*.keggmapping.txt` and `*.eggnogmapping.txt` annotation files; these were not present on the archived website or in the bundled archive.

## Repository layout

```
docs/                 Static, self-contained website (GitHub Pages source; no external CSS/JS/fonts)
  index.html
  assets/             Stylesheet, script, logo, figure previews
supplementary/        Downloadable data files (Git LFS)
.gitattributes        Git LFS tracking rules
```

### Git LFS

All files in `supplementary/` are tracked with [Git LFS](https://git-lfs.com). Install it before cloning
(`git lfs install`), or download individual files from the website. Because GitHub Pages does not serve LFS
objects, the website's download buttons point to `https://github.com/raeslab/Small-Intestinal-Microbiota/raw/main/supplementary/...`;
when `docs/index.html` is opened from a local checkout the links switch to the relative `../supplementary/` paths.

### Publishing

In the repository settings, enable GitHub Pages with source *Deploy from a branch* → `main` / `/docs`.

## How to cite

If you use these data, please cite:

> Zoetendal EG, Raes J, van den Bogert B, Arumugam M, Booijink CCGM, Troost FJ, Bork P, Wels M, de Vos WM, Kleerebezem M. **The human small intestinal microbiota is driven by rapid uptake and conversion of simple carbohydrates**. *The ISME Journal* 6(7):1415–1426 (2012). [doi:10.1038/ismej.2011.212](https://doi.org/10.1038/ismej.2011.212)

```bibtex
@article{zoetendal2012human,
  title   = {{The human small intestinal microbiota is driven by rapid uptake and conversion of simple carbohydrates}},
  author  = {Zoetendal, E. G. and Raes, J. and van den Bogert, B. and Arumugam, M. and Booijink, C. C. G. M. and Troost, F. J. and Bork, P. and Wels, M. and de Vos, W. M. and Kleerebezem, M.},
  journal = {The ISME Journal},
  year    = {2012},
  volume  = {6},
  number  = {7},
  pages   = {1415--1426},
  doi     = {10.1038/ismej.2011.212}
}
```

## Contact

Raes Lab, VIB–KU Leuven Center for Microbiology – Prof. Jeroen Raes (jeroen.raes@kuleuven.be).
