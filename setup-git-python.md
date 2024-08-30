# Install GIT & Python

1. #### Install GIT SCM

Install git scm from provided link (make sure you restart your terminal after)
- [Install GIT SCM](https://git-scm.com/)

2. #### Install Python Version 3.8 - 3.11 (For MacOS Only)

If you don't have pyenv install it first

```
pyenv install 3.11.0
pyenv global 3.11.0
```

after installing confirm python version
```
python --version
```

it must show
```
python 3.11.0

## IMPORTANT NOTE

- Pytorch only support mps (Metal Performance Shaders) for python version 3.8 - 3.11 [READ THIS FOR MORE DETAILS](https://pytorch.org/get-started/locally/)
- [ALSO READ THIS](https://developer.apple.com/metal/pytorch/)
