# data_contracts
This data contract relates to the raw invoice data we're ingesting into the data warehouse.

The following are the business requirements:

- Data is monitored to ensure it is updated by 9am every day
  
- The "id" field must be 100% unique
  
- The following fields are monitored for anoamlies:
  - id
  - invoice_amount
  - invoice_description
  - status
 
- "invoice_period_start_date" must always be before "invoice_period_end_date"
