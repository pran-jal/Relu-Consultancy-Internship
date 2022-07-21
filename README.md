# Relu-Consultancy-Internship

Python Data Extraction Engineering internship at Relu Consultancy.

## Steps:
run main.py

## Approach:
Amazon detects browsers so we need to use different user-agents.
some items have fixed price and some have a list of different sellers. Need to cinsider both.
need to use selenium for some pages that do not like the user-agent provided.

    
    read csv-> 
        |->create url 
            |-> request url with headers
                    |-> unsuccessful ? 
                            |-> no -> -> -> -> scrape data -> add to json variable 
                            |                         |             |-> save to .json file after 100 urls
                            |-> yes -> use selenium ->|
                            
                        
## [Google Collab](https://github.com/pran-jal/Relu-Consultancy-Internship/blob/main/Relu_Consultancy_Internship.ipynb)                                                            
