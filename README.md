# terraform_for_each_vm
CHANGES: the password was added in tfvars file, subscription_id was added in provider.tf, the main tf file inside modules, vm version was changed from 16 to 22 because of some issues with the python version in later steps.

to run this just add your own password in the tfvars file and azure subscription id in the provider.tf
you can check your id using the command below:
```bash
az account show
```

remember, don't commit your subscription id, I will steal it and use a lot ;)

For the rest of the guide check [this repo](https://github.com/FelipeBarretoB/ansible-pipeline)