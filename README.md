# snapshotAuto-2020
Demo project to manage AWS EC2 instances snapshop

	## About

	This a project demo, and uses boto3 to manage AWS EC2 instances snapshots
 
	## Configuring

	shotty uses the configuration file created by AWS cli e.g
		'aws configure --profile shotty'

	## Running
	
		'pipenv run python shotty/shotty.py <command> <--project=PROJECT>'
		
		*command* is list , start, or stop
		*project* is optional