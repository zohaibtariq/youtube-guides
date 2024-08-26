# Foocus Setup Guide

#### [Follow Foocus Official Repo](https://github.com/lllyasviel/Fooocus)

#### [Generate Unlimited AI Images Locally for Free with Fooocus: No Limits, No Cost!](https://youtu.be/fE158r0p_4Q)

---

#### Clone the repo
```
git clone https://github.com/lllyasviel/Fooocus.git
cd Fooocus
```
---

#### Setup Virtual Environment with venv or conda

for venv
```
python3 -m venv fooocus_env
source fooocus_env/bin/activate
pip3 install -r requirements_versions.txt
source fooocus_env/bin/activate
```
OR
```
conda env create -f environment.yaml
conda activate fooocus
pip install -r requirements_versions.txt
conda activate fooocus
```
---

#### Install pytorch nightly with pip or conda

For pip
```
pip3 install --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/cpu
```

OR

For Conda
```
conda install pytorch-nightly::pytorch torchvision torchaudio -c pytorch-nightly
```
#### Run Fooocus server locally

---
```
python3 entry_with_update.py --disable-offload-from-vram --preset realistic
```

OR

```
python3 entry_with_update.py --disable-offload-from-vram --preset anime
```

#### IMPORTANT must use python version between (3.8 - 3.11)

#### MAC USERS (must go through links mentioned below)

1. [Accelerated PyTorch training on Mac](https://developer.apple.com/metal/pytorch/)
2. [Setup PyTorch locally on macOS](https://pytorch.org/get-started/locally/)
