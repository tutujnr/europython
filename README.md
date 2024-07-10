# template_bot

This is the template python bot for `vendeeglobe` Europython 2024 game tournament.

Instructions for the tournament can be found [here](https://github.com/europybots2024/vendeeglobe).

## Short summary

## TL;DR

1. Create a repository for your bot from this template.

2. Get started with:

### conda

```
conda create -n <NAME> -c conda-forge python=3.10.*
conda activate <NAME>
git clone https://github.com/europybots2024/vendeeglobe.git
git clone https://github.com/<USERNAME>/<MYBOTNAME>.git
cd vendeeglobe/
python -m pip install -e .
cd run/
ln -s ../../<MYBOTNAME> .
python play.py
```

### venv

```
git clone https://github.com/europybots2024/vendeeglobe.git
git clone https://github.com/<USERNAME>/<MYBOTNAME>.git
cd vendeeglobe/
python -m venv .<NAME>
source .<NAME>/bin/activate
python -m pip install --upgrade pip
python -m pip install -e .
cd run/
ln -s ../../<MYBOTNAME> .
python play.py
```

