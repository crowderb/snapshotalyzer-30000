# snapshotalyzer-30000
Demo project to manage AWS EC2 instance snapshot (acloud.guru)

## About

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

## Configuring

shotty sues the configuration file created by the AWS cli. e.g.

`aws cnfigure --profile shotty`

## Running

`pipenv run python shotty/shotty.py <command>
<--project=PROJECT>`

*command* is list, start, or stop
*project* is optional
