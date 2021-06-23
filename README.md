# Terraform Ansible Spec

Purpose of this is to build a simple terraform ansible test project.

Project should include these pieces:

## Terraform
  * RDS DB (postgres)
  * EC2 instance that can connect to said DB instance

## Ansible
A playbook to:
  * Install nodejs + npm
  * clone the application
  * Start the app

## Notes
  * Please only use modules you have written and fully understand the 
    ramifications of their use.
  * Please use us-east-1 as your region.

## Terraform config

* Use variables so I can easily change settings on the DB.
* we can wire these up into a completely open security group for now.
* Include outputs so we can load our variables as json in ansible


## Ansible configuration
  * Install nodejs, npm and get a simple app that connects to a db up and running.
  * source code for this app available [here](https://github.com/oddballio/oddball-hello-db)
