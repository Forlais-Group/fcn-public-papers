# Forlais Compression Notation Public Papers

This repository contains the first public Forlais Compression Notation paper pack on lossless compression of trained neural network weights.

The release focuses on the BF16 single-model compression ceiling, its information-theoretic and statistical explanation, public compressor baselines, and public-safe transform evidence. It does not include non-public operational code, source logs, model weights, non-public datasets, hidden benchmark mechanics, or operational procedures.

## Release

Version: v1.0-public  
Author: Oliver Cooper, Forlais Group Ltd  
ORCID: 0009-0005-5798-827X  
Archive target: GitHub release archived to Zenodo  
DOI: https://doi.org/10.5281/zenodo.20961807  
Licence: CC BY 4.0

## Paper Set

| Order | Filename | Paper |
|---:|---|---|
| 1 | `01-fcn-compression-theorem-trained-weights.pdf` | The Compression Theorem for Trained Neural Network Weights |
| 2 | `02-fcn-bf16-1-52-entropy-ceiling.pdf` | BF16 1.52x Entropy Ceiling |
| 3 | `03-fcn-benford-origin-bf16-compression-ceiling.pdf` | Benford's Law as the Origin of the BF16 Compression Ceiling |
| 4 | `04-fcn-mutual-information-paradox-bf16.pdf` | The Mutual-Information Paradox in BF16 Weight Streams |
| 5 | `05-fcn-three-component-decomposition-bf16.pdf` | Three-Component Decomposition of BF16 Weight Values |
| 6 | `06-fcn-r2-law-mantissa-bias.pdf` | The r = 2 Law of Mantissa-Bit Bias in Trained Neural Weights |
| 7 | `07-fcn-r2-prior-negative-result.pdf` | A Closed-Form r=2 Prior for Mantissa Bits and Why Seeding an Adaptive Coder With It Yields No Practical Gain |
| 8 | `08-fcn-public-compressor-comparison-bf16.pdf` | A Wide Comparison of Public Lossless Compressors on BF16 Model Weights |
| 9 | `09-fcn-aligned-byte-compression-bf16.pdf` | Aligned Byte Compression of BF16 Weights |

## Public Front Matter

Each PDF has been exported with:

```text
Status Public Release
Classification Public
Disclosure status Approved for public release
Release channel GitHub + Zenodo
Version 1.0-public
Publication target GitHub + Zenodo public archive
```

The controlled-document sentence has been replaced with:

```text
This is an approved public release of a Forlais Group academic paper.
```

## Repository Contents

```text
README.md
LICENSE.md
CITATION.cff
.zenodo.json
NOTICE.md
papers/
metadata/
release-notes/
```

Checksums for the final PDFs are recorded in `metadata/SHA256SUMS.txt`.

## Boundary

This public release is not the full FCN evidence register. It is a curated public paper pack. The release excludes non-public source logs, operational code, model weights, non-public datasets, hidden benchmark mechanics, C04 cross-model delta codec stack details, non-public deduplication papers, and traversal strategy papers.
