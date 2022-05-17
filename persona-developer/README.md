# 2022 - AWS Summit Washington, DC - DOP302

## Developer Persona

This persona will create a CloudFormation script to deploy a Hello World NodeJS application to Amazon EC2.

## Usage

```
brew install cfn-guard
cfn-guard validate --data node-stack-hello-world.yml --rules encryption-at-rest.guard

```