# Philosopher
A data processing toolkit for shotgun proteomics.

![Golang](https://img.shields.io/badge/Go-1.12.5-blue.svg)

## Features
Philosopher provides easy access to third-party tools and custom algorithms allowing users to develop proteomics analysis, from Peptide Spectrum Matching to annotated protein reports. Philosopher is also tuned for Open Search analysis, providing a modified version of the prophets for peptide validation and protein inference. To this date, Philosopher is the only proteomics toolkit that allows you to process and analyze close and open search results.

- Mass spec data file conversion with msconvert.

- Database downloading and formatting.

- Peptide Spectrum Matching with Comet.

- Peptide assignment validation with PeptideProphet.

- Multi-level integrative analysis with iProphet.

- PTM site localization with PTMProphet.

- Protein inference with ProteinProphet.

- Open Search data validation.

- FDR filtering with custom algorithms.

  - Two-dimensional filtering for simultaneous control of PSM and Protein FDR levels.
  - Sequential FDR estimation for large data sets using filtered PSM and proteins lists.
  - PickedFDR for scalable estimations.
  - Razor peptide assignment for better quantification and interpretation.
  

- Label-free quantification via Spectral counting and MS1 Quantification.

- Labeling-based quantification using TMT isobaric tags.

- Clustering analysis for proteomics results.

- Multi-level detailed reports including peptides, ions and proteins.

- Mass spec identification file conversion with idconvert.


## How to Download
Download the latest version [here](https://github.com/Nesvilab/philosopher/releases/tag/v1.5.1)

## Documentation
For documentation on Philosopher itself, see Philosopher Documentation [Wiki page](https://github.com/Nesvilab/philosopher/wiki).


## Questions, requests and bug reports
If you have any questions, remarks, requests or if you found a bug, please use the [Issue tracker](https://github.com/Nesvilab/philosopher/issues).


## How to cite
Still in progress!


## License
Since Philosopher is not officially released, the binaries provided here have no license. Once released, the software will be licensed under the GPL 3 license.


## About the developers
[Felipe da Veiga leprevost](http://www.leprevost.com.br)

Alexey Nesvizhskii's [nesvilab](http://www.nesvilab.org/)
