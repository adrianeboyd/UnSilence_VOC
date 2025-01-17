[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6958524.svg)](https://doi.org/10.5281/zenodo.6958524)

# Unsilencing Colonial Archives via Automated Entity Recognition 

Colonial archives are at the center of increased interest from a variety of perspectives, as they contain traces of historically marginalized people. Unfortunately, like most archives, they remain difficult to access due to significant persisting barriers. We focus here on one of them: the biases to be found in historical findings aids, such as indices of person names, which remain in use to this day. In colonial archives, indexes can perpetrate silences by omitting to include mentions of historically marginalized persons. In order to overcome such limitation and pluralize the scope of existing finding aids, we propose using automated entity recognition. To this end, we contribute a fit-for-purpose annotation typology and apply it on the colonial archive of the Dutch East India Company (VOC). **We release a corpus of nearly 70,000 annotations as a shared task, for which we provide strong baselines using state-of-the-art neural network models.**

# Paper

The associated paper has been published in the Journal of Documentation’s special issue on _Artificial Intelligence for Cultural Heritage Materials_ [here](https://www.emerald.com/insight/content/doi/10.1108/JD-02-2022-0038/full/html).
The post print can be found [here](https://arxiv.org/abs/2210.02194).

## How To Cite
* Luthra, Mrinalini, Konstantin Todorov, Charles Jeurgens, and Giovanni Colavizza. "Unsilencing colonial archives via automated entity recognition." Journal of Documentation (2023).

```bibtex
@article{luthra2023unsilencing,
  title={Unsilencing colonial archives via automated entity recognition},
  author={Luthra, Mrinalini and Todorov, Konstantin and Jeurgens, Charles and Colavizza, Giovanni},
  journal={Journal of Documentation},
  year={2023},
  publisher={Emerald Publishing Limited}
}

```


# Data

The dataset, that is the annotations are available in 2 formats:

1) brat annotation output: [here](data/annotated_data)
2) data in iob format: [here](processed_data)

## How To Cite

* Mrinalini Luthra, Konstantin Todorov, Leon van Wissen, Charles Jeurgens and Giovanni Colavizza. 2022. “Unsilencing Colonial Archives via Automated Entity Recognition”. Zenodo. https://doi.org/10.5281/zenodo.6958430.

```bibtex

@dataset{mrinalini_luthra_2022_6958430,
  author       = {Mrinalini Luthra and
                  Konstantin Todorov and
                  Leon van Wissen and
                  Charles Jeurgens and
                  Giovanni Colavizza
                  },
  title        = {{Unsilencing Colonial Archives via Automated Entity 
                   Recognition}},
  month        = aug,
  year         = 2022,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.6958430},
  url          = {https://doi.org/10.5281/zenodo.6958430}
}

```

## Annotation Typology
Please refer to the documentation of the annotation typology [here](data/README.md).

## Data Card
Please refer to the data card of the annotated dataset [here](Datacard.pdf).
This document provides a synopsis of the dataset, motivations and uses.

# Code

Please refer to the separate documentation of our Entity Recognition model implementation [here](src/code_documentation.md)

# License

[![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].


[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

# Contact

For issues, suggestions and contributions please contact 
* [Mrinalini Luthra](mrinalini.luthra@gmail.com) 
* [Giovanni Colavizza](g.colavizza@uva.nl)
* [Charles Jeurgens](K.J.P.F.M.Jeurgens@uva.nl)
