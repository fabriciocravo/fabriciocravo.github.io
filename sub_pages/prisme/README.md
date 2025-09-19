# PRISME

> Statistical Power Analysis for Neuroimaging

## What is PRISME?

PRISME (Power Repetition Interface for Statistical Method Evaluation) is a MATLAB toolbox for comprehensive statistical power analysis in neuroimaging.

## Features

- ⚡ **25x faster** than previous methods
- 🧠 **Multiple statistical methods** supported
- 📊 **Comprehensive analysis** at edge, network, and whole-brain levels

## Quick Start
```matlab
% Load your data
data = load('my_neuroimaging_data.mat');

% Configure parameters
params = setparams();
params.n_repetitions = 500;

% Run power analysis
results = prisme_power(data, params);