# Species-aware DNA language models capture regulatory elements and their evolution

DNA Lnaguage models present a promising new avenue to extract regulatory information from large collections of unannotated genomes, in an alignment-free manner. 
More details about our approach and the results can be found in the preprint: https://doi.org/10.1101/2023.01.26.525670

In this repository, we have compiled a simple tutorial notebook which explains how to use the Species LM models (which are available from Huggingface) to (1) reconstruct masked nucleotides and (2) generate informative sequence representations.

Additionally, we have included the notebooks which generate the figures in the paper.

All data and precomputed model outputs can be found in the Zenodo: https://doi.org/10.5281/zenodo.8247134

Note that the upstream models were trained using FlashAttention. To upload to Huggingface seemlessly, they were converted to standard Huggingface models. 
As a result they can be run using float32, but this may lead to slight numerical instabilities.
