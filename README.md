# README

A conda environment for neuroimaging analysis. This environment should work on all operating systems.

## Installation

Requirements:
- miniconda

First clone this repository with:
```
git clone https://github.com/nhuneke/imagingenv imaging-env
```

Next, create the environment on your machine with:
```
cd imaging-env
conda env create --file imaging-env.yml
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
conda env update --name=imaging-env --file=imaging-env.yml --prune
```