# Welcome to the Foodie app

This repository provides a Foodie app integration for metaphactory.


## Building the app artifact

Using the provided `build.sh` script it is possible to (re)-build the Foodie app artifact (e.g. when you did local modifications). The artifact can then be deployed on the target system as described below.

## Using the app in your metaphactory installation

Build the latest version as described above and install it through the _Apps administration_ UI of your installation.

To complete the installation a restart of the platform is required. 

See https://help.metaphacts.com/resource/Help:AppDeployment for details on the deployment.

Notes: 

* we recommend to deploy the app in a fresh metaphactory installation
* please make sure to use a compatible app version (e.g. Foodie 3.6 for metaphactory 3.6.x)


