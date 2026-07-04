# Pretraining Numerical Frequency and Number-Line in Language Models

Project page and code for our paper accepted at the **ICML 2026 Workshop on Mechanistic Interpretability**.

**Authors:** Mohammed Ibrahim Awad*, Ahmed Elshehaby*, Hilal AlQuabeh†, Velibor Bojkovic†
(*Equal contribution  †Equal supervision)
**Affiliation:** Mohamed bin Zayed University of Artificial Intelligence (MBZUAI), Abu Dhabi, United Arab Emirates

## Overview

Large language models encode numerical magnitude in a compressed, non-uniform internal geometry, but the pretraining factors behind this remain unclear. We study whether corpus-level integer statistics are reflected in the learned number-line geometry of pretrained LLMs.

For four documented pretraining corpora we count integers in [0, 10,000] and fit a magnitude-frequency power law, count(N) ∝ N^α. For nine corresponding base models we project hidden states onto a one-dimensional number line via PCA and estimate a scaling factor β. We find that flatter integer-frequency distributions (less negative α) are associated with less compressed number-line geometry (larger β), and that larger β corresponds to higher number-comparison accuracy.

## Links

- 📄 Paper — coming soon
- 🌐 [Project page](https://mdibrahimawad.github.io/Pretraining-Numerical-Frequency-and-Number-Line-in-Language-Models/)

## Citation

​```bibtex
@inproceedings{awad2026numberline,
  author    = {Awad, Mohammed Ibrahim and Elshehaby, Ahmed and AlQuabeh, Hilal and Bojkovic, Velibor},
  title     = {Pretraining Numerical Frequency and Number-Line in Language Models},
  booktitle = {ICML 2026 Workshop on Mechanistic Interpretability},
  year      = {2026},
}
​```

## Acknowledgements

The project page is built on the [Nerfies](https://github.com/nerfies/nerfies.github.io) template.
