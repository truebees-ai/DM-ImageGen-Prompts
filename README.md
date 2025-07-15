# DM-ImageGen-Prompts
Prompts and scripts used to generate the Diffusion Model generated images of the DeepShield Dataset

## DeepShield Dataset
Checkout our dataset at this [link](https://zenodo.org/records/15648378).

Please cite:
```
Truebees Srl, “DeepShield: A Dataset of Real and AI-Generated Images also Shared on Social Networks”. Zenodo, Jun. 12, 2025. doi: 10.5281/zenodo.15648378.
```

## Virtual Env
```
python -m venv prompter
source prompter/bin/activate
pip install more-itertools
```
## Generate Your Prompts
```
python prompter_faces.py
python prompter_animals.py
python prompter_landscapes.py
```
