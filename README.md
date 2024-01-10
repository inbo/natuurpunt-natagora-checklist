# Waarnemingen.be / observations.be - List of species observed in Belgium

This repository is about the _List of species observed in Belgium_, based on data from the portals https://waarnemingen.be and https://observation.be. Natuurpunt manages and validates the source data, INBO provides technical support in publishing it to [GBIF](https://www.gbif.org/).

## Useful links

- [Dataset on the IPT](https://ipt.inbo.be/resource?r=natuurpunt-natagora-checklist)
- [Dataset on GBIF](https://doi.org/10.15468/a7wkuh)
- [Reported issues](https://github.com/inbo/natuurpunt-natagora-checklist/issues)

## Repo structure

The repository structure is based on [Cookiecutter Data Science](http://drivendata.github.io/cookiecutter-data-science/) and the [Checklist recipe](https://github.com/trias-project/checklist-recipe). Files and directories indicated with `GENERATED` should not be edited manually.

```
├── README.md              : Description of this repository
├── LICENSE                : Repository license
├── .gitignore             : Files and directories to be ignored by git
│
├── data  
│   └── raw                : Darwin Core data provided by Natuurpunt
│
├── specification
│   └── dwc-occurrence.yaml : Specification for the data (used for validation)
│
└── notebooks
    └── verify-mapping.ipynb : Script to validate the data
```
