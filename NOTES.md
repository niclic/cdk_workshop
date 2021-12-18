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

cdk diff

cdk deploy

# repeat for apigw

```

## Writing Constructs

```sh

cdk deploy

curl -i https://1rapjixz04.execute-api.ca-central-1.amazonaws.com/prod/hello/world

```

## Construct Libraries

```sh
pip install cdk-dynamo-table-view==0.2.0

cdk diff

cdk deploy

https://3x5akbsb79.execute-api.ca-central-1.amazonaws.com/prod/

```

## Cleanup

```sh

cdk destroy

```

## Testing Constructs

```sh
pip install -r requirements-dev.txt


```
