# Roman QSO Detection — Data Files

The large quasar catalog files used in this project are not included in this repository.

Download the following data files before running the notebooks.

## Wu & Shen (2022) — SDSS DR16Q

[Paper](https://arxiv.org/abs/2209.03987)

[Catalog and tutorial repository](https://github.com/QiaoyaWu/sdss4_dr16q_tutorial)

Download the DR16Q spectral-property catalog:

```text
dr16q_prop_Oct20_2022.fits

Place the file in the same directory as the notebooks.


## Shen et al. (2011) — SDSS DR7

Paper:

[Shen et al. (2011)](https://arxiv.org/abs/1006.5178)

Catalog:

[SDSS DR7 Catalog — VizieR](https://cdsarc.cds.unistra.fr/viz-bin/cat/J/ApJS/194/45)

Download the DR7 quasar-property catalog and its ReadMe file.

Expected files:

```text
catalog.dat.gz
ReadMe
```

Unzip:

```text
catalog.dat.gz
```

to produce:

```text
catalog.dat
```

Rename `ReadMe` to `ReadMe.txt` if needed.

Place both files in the same directory as the notebooks.


## Local Project Files

After downloading the catalogs, the directory should contain:

```text
Roman_QSO_Detection/
├── Roman_Prob.ipynb
├── QSO_Detection_Code.ipynb
├── dr16q_prop_Oct20_2022.fits
├── catalog.dat
└── ReadMe.txt
```