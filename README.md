# OM4p25_tideamp
tidal amplitude file generation for OM4p25 configuration

Generating tidal amplitudes from [TPXO](https://journals.ametsoc.org/jtech/article/19/2/183/2083/Efficient-Inverse-Modeling-of-Barotropic-Ocean.)
TPXO products need to be obtained through registration [here](https://www.tpxo.net/tpxo-products-and-registration)

## Reproducing the results

I created my `tpxo_interp` environment from the file `tpxo_interp.yml`.
This environment can be recreated exactly using:

```
conda create --name tpxo_interp --file spec-env.txt
```

To make this environment visible from jupyter, use:

```
python -m ipykernel install --user --name tpxo_interp --display-name "Py3-tpxo_interp"
```
