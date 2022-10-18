# LSTM-GARCH

## Introduction

This repository contains a Python implementation of a Hybrid LSTM-GARCH model for forecasting volatility. It is based of the following paper:

[a link](https://www.sciencedirect.com/science/article/pii/S0957417418301416)

## Table of Contents

- [Genome Processing](#Genome-Processing)
- [Recommendation Algorithm](#Recommendation-Algorithm)
- [Airfoil Computations](#Airfoil-Computations)
- [Truss Linear Equations](#Truss-Linear-Equations)
- [Image Processing](#Image-Processing)

## Genome Processing

<table>
<tr>
<td>
  
**Genome Processing** is a Python software to generate _DNA references_ and compute the alignments of given DNA sequences with the _generated reference_. 
This allows to identify **regions of similarity** that may be a consequence of _evolutionary relationships_ between the sequences. 

The code generates an **output file** that contains the index of the _matches of each sequence with the reference_ and the _percentage of how many matches
each sequence has_ (i.e. if a sequence matche once, twice or does not match the reference) and the _computing time_.

<p align="center">
<img src="https://github.com/tlemenestrel/swe_scientific_projects/blob/master/genome_processing/images/alignments.png" width="700">
</p>

</td>
</tr>
</table>

### Terminal commands and outputs

1. First, cd into the genome_processing folder:

    ```
    $ cd genome_processing
    ```

2. Then, run the following command to process a given sequence:

    ```
    $ python processdata.py references/ref_3.txt reads/reads_3.txt alignments/align_3.txt
    ```
3. You should get the following output:
    ```
    reference_length: 100000
    number reads: 60000
    aligns 0: 0.15
    aligns 1: 0.75
    aligns 2: 0.1
    elapsed time: 23.56
    ```

