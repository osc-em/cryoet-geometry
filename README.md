# cryoet-metadata

A suggestion for a metadata schema for the transfer of cryo-ET geometry metadata between different software tools and 
data repositories, heavily inspired by the [OME-NGFF coordinate system metadata RFC](https://ngff.openmicroscopy.org/rfc/5/index.html) and [Heymann et al. 3DEM standards](https://doi.org/10.1016/j.jsb.2005.06.001). 

See [docs site](https://cryo-et-standards.github.io/cryoet-geometry/) for details.

## Installation

```bash
git clone 
pip install .[all]
```

## Build python models from linkML schema

```bash
make gen-python
```
