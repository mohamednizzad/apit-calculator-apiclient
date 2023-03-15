# apit-calculator-apiclient
Advance Personal Income Tax (APIT) Calculator API Client for communicating with AWS API Gateway Demo


# Instruction
This apit-calculator-apiclient is part a demo client application which communicates with the demo Rest API deployed using AWS' API Gateway where the API Gateway invokes the Lambda Function to return the Advance Personal Income Tax w.e.f 01.01.2023 (Sri Lanka). 

This project is designed and developed for the purpose of demonstrating the capability of AWS API Gateway in realising the REST API in a fraction of time with the invocation of Lambda Function through the invocation of AWS API Gateway.

# API Endpoint
- API Endpoint - https://52zydqrp26.execute-api.us-east-2.amazonaws.com/default/apit-api
- Demo Call - https://52zydqrp26.execute-api.us-east-2.amazonaws.com/default/apit-api?income=100000
- Input Parameter - **income** (Monthly Income)
- Sample JSON Output {"statusCode": 200, "income": 100000, "status": "No Tax", "tax": "0", "salaryaftertax": "100000"}
- Note: There is no guarantee for the availability of the API EndPoint as this is hosted for the purpose of learning and demonstration

# Working Demo of the Client
- A Working Demo of the Project can be experimented here at https://projectdemobynizzad.000webhostapp.com/apit-api-client.html

# Disclaimer
This application is developed for the sole purpose of demonstrating the Invocation of AWS Lambda Function through API Gateway, Provisioning it as a Rest API and Accessing via API Client.<b class="text-danger"> This should not be taken as an advise for calculation of tax.
						<a href="http://www.ird.gov.lk/en/publications/APIT_Tax_Tables/2022-2023/Table%20%E2%80%93%201/02.APIT_2223_Table_01.pdf" target="blank">Refer this table</a> for additional information.</b>
