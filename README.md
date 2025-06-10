# Training Data, Moment Tensor Potentials and Verification for Mg/Al/Ca

*This data is part of a [publication](https://doi.org/10.1038/s41524-025-01669-4).*

Data files may be downloaded from [EDMOND](https://doi.org/10.17617/3.DYLLSS) using the `Unpack.ipynb` notebook.

# Citation

Please cite the following paper, if this data is useful for your work.

```
@article{poul2025automated,
  title={Automated generation of structure datasets for machine learning potentials and alloys},
  volume={11},
  DOI={10.1038/s41524-025-01669-4},
  number={1},
  journal={npj Computational Materials},
  author={Poul, Marvin and Huber, Liam and Neugebauer, J\"org},
  year={2025},
  month={Jun}
}
```

# Notebooks

## Verification

The full test data presented in the manuscript are plotted in `Verification.ipynb` with some additional graphs.

## Training Data

The training set is visualized in `Pyiron.ipynb`.

## Potential Metrics

The fitting metrics of the MTPs are shown in `Pyiron.ipynb`.

# Requirements

To run the `Verification.ipynb` notebook, install the dependencies in `environment-veri.yml` with `conda`.

To run the `Pyiron.ipynb` notebook, install the dependencies in `environment-full.yml` with `conda`.
