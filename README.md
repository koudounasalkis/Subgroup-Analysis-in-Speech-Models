# Towards Comprehensive Subgroup Performance Analysis in Speech Models
This repo contains the code for "Towards Comprehensive Subgroup Performance Analysis in Speech Models".

In this repository, you will find the code to replicate our experiments.  

We do not include the datasets ([FSC](https://fluent.ai/fluent-speech-commands-a-dataset-for-spoken-language-understanding-research/), [SLURP](https://github.com/pswietojanski/slurp), [IEMOCAP](https://sail.usc.edu/iemocap/), [LibriSpeech](https://www.openslr.org/12)) used in the paper as they are publicly available and downloadable from the official sites (except for [IEMOCAP](https://sail.usc.edu/iemocap/), for which a request must be made).

Further information will be released upon acceptance of the paper.

------------------  

## Get Started
Our code was tested on Python 3.10.8. To make it work, you will need a working environment with the libraries listed in `requirements.txt`.

## Running the Experiments
To reproduce the paper's experiments, use the `divexplorer_analysis_{name_dataset}.ipynb` notebook, which leverages the files already computed in `data_precomputed/{name_dataset}`. 

------------------ 

## License
This code is released under the Apache 2.0 license. See the [LICENSE](LICENSE) file for more details.

## Contact
For any questions, please contact [Alkis Koudounas](mailto:alkis.koudounas@polito.it).
