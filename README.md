# COMPLEX - MU4IN900 - 2024/2025

## TME des semaines 3 à 5

Tarık Ege EKEN - 21110611\
Baran AÇIKEL - 21112041

## Use a virtual environment

Clone this repository to local `git clone git@github.com:xxBWxx/complex.git <dir name (optional)>`.

Create a virtual environment `python -m venv .venv` in your local repository and activate it `source .venv/bin/activate`, or `source .venv/Scripts/activate` if your activation script is not located in `/bin`. (virtual environment deactivation `deactivate`)

Once in your virtual environment, intall dependencies with `pip install -r requirements.txt`.

To add a dependency, write it on `requirements.in` file and generate `requirements.txt` using the command `pip-compile -U` (to use this command you must have downloaded `pip-tools` using `pip install pip-tools`)

Once the new `requirements.txt` is generated, don't forget to intall new dependencies using `pip install -r requirements.txt`.
