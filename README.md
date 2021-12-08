==========================

# Use Akamai Terraform CLI to prepare Akamai Terraform Provider files

Step 1 akamai terraform create-property <your_property_name>

Step 2 Run import.sh to import the existing resource that you would like to manage via. Terraform

. ./import.sh

Step 3 -
Run Terraform plan and apply

Step 4 -
Next, make changes in any rule

- [ ] Open Offload_origin.json and search for ‘ttl’. - change it to 110m or any other number
- [ ] Run terraform apply
- [ ] See the changes being pushed to environment of your choice
