# CompCATE
Code to replicate the results in the AISTATS23 paper "Understanding the Impact of Competing Events on Heterogeneous Treatment Effect Estimation from Time-to-Event Data" (Curth & van der Schaar, 2023)

## Installation
Clone the repository with:
```
git clone https://github.com/vanderschaarlab/CompCATE.git
```
install requirements with 
```
pip install -r requirements.txt
```
or from source,
```
pip install .
```

## Experiments
Experiments can be run with:
```
python run_experiments.py --experiment <experiment name> --setting <setting> --n_exp <n_exp> --file_name <file_name>
```

Here are the available options to pass:
```
--experiments: sim or twins
--setting: 1, 1A, 1B, 1C, 1D, 2, 3, or 4
--n_exp: any integer. Defaults to 10
--file_name: The prefix for the results filenames
```

more information is available with:
```
python run_experiments.py --help
```