# OKD4 UPI AWS Cloudformation

Cloudformation templates repository tweaked for semi-automate the installation of UPI Openshift 4

* IMPORTANT: You can obtain the [latest cloudformation templates](https://github.com/openshift/installer/tree/master/upi/aws/cloudformation) into the Openshift Installer official repository.

When running openshift-installer to provision OKD 4.x, wildcard DNS is set to *.apps.<cluster_name>.<base_domain> by default. Sometimes user might want to have a different wildcard DNS (ex. *.<base_domain>)for applications. In order to change the default wildcard DNS, user needs to generate cluster manifest files and change the domain name. This repository will show how this can be achieved. 

Tested and working with 4.5.0-0.okd-2020-09-04-180756


