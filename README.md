# Notas

## Inicio de Anaconda Navigator
Se ejecuta desde el ambiente base
```terminal
(base) $ anaconda-navigator
```

## Creación de un ambiente conda con paquetes de R
```terminal
# Lista de ambientes
(base) $ conda env list

# Creación de ambiente R
(base) $ conda create -n pdg r-essentials r-base

# Activación
(base) $ conda activate pdg

# Actualización de paquetes de R
(base) $ conda update r-caret

# Instalación de RStudio
(base) $ conda install -c r rstudio

# Lista de paquetes instalados
(base) $ conda list

# Desactivación
(pdg) $ conda deactivate

# Borrado
(base) $ conda env remove --name pdg
```

## Inicio de R y RStudio
```terminal
# R
(pdg) $ R

# RStudio
(pdg) $ rstudio
```

## Instalación de GDAL
GDAL queda disponible con la creación del ambiente, pero la versión del canal conda-forge es más nueva
```terminal
(pdg) $ ogrinfo --version # GDAL 2.4.2, released 2019/06/28
(pdg) $ conda install -c conda-forge gdal
(pdg) $ ogrinfo --version # GDAL 3.0.4, released 2020/01/28
```
