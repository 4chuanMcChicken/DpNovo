# DpNovo

This is the source code of DpNovo:

DpNovo: A DEEP LEARNING MODEL COMBINED WITH DYNAMIC PROGRAMMING FOR DE NOVO PEPTIDE SEQUENCING

De novo peptide sequencing is an efficient approach to identifying peptides from tandem mass spectrometry (MS/MS). Compared with the database search methods, de novo peptide sequencing is particularly effective in identifying novo peptide sequences. This thesis presents a new De Novo sequencing model comprising two deep learning models and a dynamic programming algorithm, namely DpNovo. The deep learning model learns features of a spectrum and gives scores to each peak, and the dynamic programming is capable of determining the optimal amino acid sequence path with the highest accumulated score. Finally, the predicted sequence with mass values representing uncertain mass intervals will be provided. DpNovo is capable of reconstructing charge-two peaks in their charge-one positions, which significantly improves the accuracy of predicting high-charged spectra. Besides, the dynamic programming algorithm ensures that accurate predictions can be made even in cases where some signal peaks are missing. In terms of performance, DpNovo has been tested on both the NIST and ProteomeXchange databases. The deep learning model has demonstrated an excellent ability to identify both signal and noise peaks. Additionally, the accuracy of peptide sequence prediction obtained through the dynamic programming algorithm is comparable to those of other proposed de novo sequencing models.

The model are trained and tested on Google Colab.
