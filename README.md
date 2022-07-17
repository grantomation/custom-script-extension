# Custom Script Extension - OpenShift tooling

This Custom Script Extensions (CSE) can be used when deploying Azure Windows 11 VMs to install tooling that is useful for interacting with OpenShift.

It can be referenced directly from github in an ARM template or bicep file.

## Installs the following

* OpenShift command line tool "oc"
* Azure cli 
* Chocolately package manager
    - Firefox
    - Visual Studio Code
    - Git