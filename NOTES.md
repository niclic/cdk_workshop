# Command History

## Init && Demo

```sh

mkdir cdk_workshop && cd cdk_workshop

cdk init sample-app --language python

# cdk init sets up a python virtual environment
# python3 -m venv .venv

# init the virtual envrionment
source .venv/bin/activate

# install python module dependencies
pip install -r requirements.txt

# create vscode project
code .

# generate json templates and yaml output
cdk synth

# run tests
pytest

# create cdk toolkit resources 
cdk bootstrap

# create stack resources
cdk deploy

# destroy initial demo stack
cdk diff
cdk deploy

```

## Hello, CDK!

```sh

mkdir lambda
touch lambda/hello.py

```