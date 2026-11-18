# CodonOptimizer — CodonLab

A browser-based educational codon optimization web app. It accepts DNA or FASTA input, selects a target host, performs synonymous codon substitutions, reports GC content and a simplified CAI, compares codons, verifies translated protein preservation, and downloads FASTA.

## Live website
After GitHub Pages is enabled: https://kanishk2721-art.github.io/CodonOptimizer/

## Features
- Raw DNA or FASTA input
- Host selection: *E. coli*, yeast, human
- Synonymous codon optimization
- GC content and simplified CAI metrics
- Changed-codon comparison
- Standard genetic-code translation check
- FASTA download and copy
- Browser-only processing: sequences are not uploaded to a server

## Deploy
This repository includes a GitHub Actions workflow. In GitHub, open **Settings → Pages**, select **GitHub Actions** as the build/deployment source if prompted. The workflow will deploy the contents of this repository.

## Scientific limitations
The codon preference weights are simplified illustrative values, not a validated codon-usage dataset. CAI is a simplified estimate and is not a prediction of protein expression. Optimization preserves the translated amino-acid sequence but does not evaluate mRNA structure, regulatory motifs, rare-codon clusters, toxicity, protein folding, or host-specific experimental expression. Do not use these demo values for experimental design without replacing them with validated data and reviewing the sequence.

## Technology
HTML, CSS, JavaScript. GitHub Pages static hosting; no server/backend required.
