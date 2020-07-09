# snapshot
demo project to manage ec2 snapshots

##

this project uses boto3 to manage aws instance snapshots

##configuring

biggs uses config file created by aws cli e.g.

`aws configure --profile biggs`

##running

`pipenv run "biggs.py" <command> <subcommand> <--project=PROJECT>`

*command* is instances, volumes, snapshots
*subcommand* depends on command
*project* is optional
