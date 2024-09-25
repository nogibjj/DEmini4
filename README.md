
[![CI](https://github.com/nogibjj/DEmini4/actions/workflows/ci.yml/badge.svg)](https://github.com/nogibjj/DEmini4/actions/workflows/ci.yml)
[![CI](https://github.com/nogibjj/DEmini4/actions/workflows/ci.yml/badge.svg)](https://github.com/nogibjj/DEmini4/actions/workflows/ci.yml)

# GitHub Actions Matrix Build for Multiple Python Versions
## Purpose of project
The purpose of this project is to test multiple python versions and environments in Github Actions. I use `setup-python` action in conjuction with `matrix strategy` to run multiple jobs with different configurations. I use a script `main.py` to check the operating system and python version

## Preparation
1. open codespaces 
2. wait for container to be built and virtual environment to be activated with requirements.txt installed 
3. make changes to any parts of the code `main.py` or `test_main.py`
4. push to see code testing in different operating systems and different python environments 

## Check format and test errors 
1. Format code `make format`
2. Lint code `make lint`
3. Test code `make test`

  
## References 
https://docs.github.com/en/actions/automating-builds-and-tests/building-and-testing-python
