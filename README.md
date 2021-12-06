# pre-commit gha workflow

Reusable workflow for github actions to execute pre-commit validations.

## What is this?

This repository contains a github actions workflow to be [reused](https://docs.github.com/en/actions/learn-github-actions/reusing-workflows) in repositories that use [pre-commit](https://pre-commit.com/) to manage pre-commit hooks. 
It just needs to receive as input the labels of the github actions runners that have pre-commit and other dependency tools available to be executed by this workflow.
TODO: put caller example here


After executing pre-commit, the output is posted as a comment on the Pull Request.

TODO: put example here
