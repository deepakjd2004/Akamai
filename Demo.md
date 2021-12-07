==========================

# Use Akamai Terraform CLI to prepare Akamai Terraform Provider files

Step 1 akamai terraform create-property config-rapid-dj.xml

Step 2 Run import.sh to import the existing resource that you would like to manage via. Terraform

. ./import.sh

Step 3 -
Run Terraform plan and apply

Step 4 -
Next, make changes in any rule

- [ ] Open Offload_origin.json and search for ‘ttl’. - change it to 110m or any other number
- [ ] Run terraform apply
- [ ] See the changes being pushed to environment of your choice

Step 5 -
Show how a new rule can be added or removed.

== Demo Done==

Walkthrough property files in scratch directory and may run it to show how to create property from scratch.

Change Property Name, Hostname and CP-Code before executing.— we are reusing the edge hostname.

=== Demo Network List===

Demo Directory
/Users/djha/Desktop/Google Drive/devOps/terraform/Demo-Nine/netlist

Change netlistname in terraform.tfvars

Terraform init
Terraform plan
Terraform apply
