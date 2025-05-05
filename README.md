# EECA-apim-poc
POC for API management platform

## To Deploy
From a bash cloudshell with appropriate permissions, 

1. check out this repo with
   
`git clone https://github.com/pat-ryan-eeca/EECA-apim-poc`

2. switch to the repo code directory
   
`cd EECA-apim-poc/apim`

3.to initialise terraform,  run 

`terraform init -upgrade`

4. run terrafrom plan
   
   `terraform plan -out main.tfplan`
   
5. to execute the plan, run
   
`terraform apply main.tfplan`
   
