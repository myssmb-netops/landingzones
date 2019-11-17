# Introduction 
Welcome to Azure Terraform landing zones samples.
Using this series of landing zones and blueprints based on Terraform, you will be able to deploy easily a complex environment based on a virtual datacenter and following the cloud adoption framework concepts https://aka.ms/caf.

We designed this series of blueprints to offer a modular and highly specialized approach, each blueprint adding a layer of features and the associated security, just by customizing a set of variables.

To deploy a landingzone, install the rover on your machine as described in the Readme of the rover git repository

https://github.com/aztfmod/rover

## Clean-up

MacOS or Linux
```bash
docker rm $(docker ps -a -f status=exited -q)
docker volume rm -f $(docker volume ls | grep devcontainer | awk '{print $2}')
```

# Contribute
Pull requests are welcome to evolve the framework and integrate new features.