# Notas

## Creación de un ambiente conda
GDAL queda disponible con la creación del ambiente, pero la versión del canal conda-forge es más nueva
```terminal
$ conda create -n pdg
$ conda activate pdg
$ ogrinfo --version # GDAL 2.4.2, released 2019/06/28
$ conda install -c conda-forge gdal
$ ogrinfo --version # GDAL 3.0.4, released 2020/01/28
```
