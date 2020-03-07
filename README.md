# Notas

## Creación de un ambiente conda
```terminal
$ conda create -n pdg
```
## Instalación de GDAL
GDAL queda disponible con la creación del ambiente, pero la versión del canal conda-forge es más nueva
```terminal
$ conda activate pdg
$ ogrinfo --version # GDAL 2.4.2, released 2019/06/28
$ conda install -c conda-forge gdal
$ ogrinfo --version # GDAL 3.0.4, released 2020/01/28
```

## Instalación de Anaconda Navigator
```terminal
$ conda activate pdg
$ conda install -c anaconda anaconda-navigator
```
