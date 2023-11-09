# DIY - Automate business analitycs with DQL 
---

This is a sample for educational purposes only and not officially part of the product.
If you have question, leave a comment on the github repo.
---

![Payment_delay](https://github.com/dynatrace-ace-services/magic_lookup/blob/main/payment_delay.png?raw=true)

## Upload Notebook
Upload the Magic Lookup Notbook in your Dynatrace Saas tenant or in a [free trial tenant](https://www.dynatrace.com/trial) 
![Upload](https://github.com/dynatrace-ace-services/magic_lookup/blob/main/upload_notebook.png?raw=true)

    https://raw.githubusercontent.com/dynatrace-ace-services/DIY_Automate_Business_Analytics_with_DQL/main/DIY_Automate_Business_Analytics.json  


##  Labs
(with solutions) 
1) Calculate the payment delay  

- With 2 lookups through 3 datasources  

3) Calculate the SLO   

- Objectif : 99% of payment delay < 12 min on default period  

3) Create the workflow  

- If SLO is not successful  
Send the result on the webhook.site  
Ingest the values on your tenant.
