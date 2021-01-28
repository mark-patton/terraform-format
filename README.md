# terraform-format

This GitHub Action is used to rewrite Terraform configuration files to a canonical format and style.

The canonical format may change in minor ways between versions of Terraform.  After upgrading Terraform, it's a good idea to run this Action on your modules, along with any other changes you are making, to adopt the new version.

### Default Options

This Action uses the following options by default:

1. ```recursive``` - processes files in subdirectories
1. triggers on Pull-Request - ```master```, ```main```, or ```release``` branches
