# README

A conda environment for neuroimaging analysis. This environment should work on all operating systems.

## Installation

Requirements:
- miniconda
- mamba

First install mamba in your base environment:
```
conda install -c conda-forge mamba
```

Next clone this repository with:
```
git clone https://github.com/nhuneke/imagingenv imaging-env
```

Next create the environment on your machine with:
```
cd imaging-env
mamba env create --file imaging-env.yml
```

## Usage

Active the environment with:
```
conda activate imaging-env
```

Deactivate the environment with:
```
conda deactivate
```

## Updates

If you download an updated version of the environment file, you will need to update
the environment on your machine. Navigate to this repository and use the following command:
```
mamba env update --name=imaging-env --file=imaging-env.yml --prune
```
