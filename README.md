# Automate business analitycs
![Payment_delay](https://github.com/dynatrace-ace-services/magic_lookup/blob/main/payment_delay.png?raw=true)

## Upload Notebook
  
    https://raw.githubusercontent.com/dynatrace-ace-services/magic_lookup/main/magic_lookup.json  


##  Demo : 3 steps 
1) Calculate the payment delay  

- With 2 lookups through 3 datasources  

3) Calculate the SLO   

- Objectif : 99% of payment delay < 12 min on default period  

3) Create the workflow  

- If SLO is not successful  
Send the result on the webhook.site  
Ingest the values on your tenant.
