# Notas

## Inicio de Anaconda Navigator
```terminal
(base) $ anaconda-navigator
```

## Creación de un ambiente conda
```terminal
# Lista de ambientes
(base) $ conda env list

# Creación
(base) $ conda create -n pdg

# Activación
(base) $ conda activate pdg

# Desactivación
(pdg) $ conda deactivate
```

## Instalación de GDAL
GDAL queda disponible con la creación del ambiente, pero la versión del canal conda-forge es más nueva
```terminal
(base) $ conda update conda
(base) $ conda activate pdg
(pdg) $ ogrinfo --version # GDAL 2.4.2, released 2019/06/28
(pdg) $ conda install -c conda-forge gdal
(pdg) $ ogrinfo --version # GDAL 3.0.4, released 2020/01/28
```

## Instalación de Anaconda Navigator
```terminal
(base) $ conda update conda
(base) $ conda activate pdg
(pdg) $ conda install -c anaconda anaconda-navigator
```
