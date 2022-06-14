
Steps i have used -
1. Create docker container- i have used nvidia’s base image for container so that i can utilize gpus also
2. Creating fast API structure- 
	Assignment → main.py, client.py
For that i have used one main file that contains endpoints and virtual environment 

3. I have created one client file for testing urls or can be tested using postman.Here is url -
For load all the data https://search-healthos-es67-nocrz73cfktuhhkgnaz72td3cq.us-east-1.es.amazonaws.com/products104/_search 

For localhost access -
'http://127.0.0.1:8000/get_matched_products'

Can access url using postman also for testing url 
https://search-healthos-es67-nocrz73cfktuhhkgnaz72td3cq.us-east-1.es.amazonaws.com/products104/_search?q=sku:P00530114

Sample output-
['SKU']
https://search-healthos-es67-nocrz73cfktuhhkgnaz72td3cq.us-east-1.es.amazonaws.com/products104/_search?q=sku:9679066509330932
{"took":15,"timed_out":false,"_shards":{"total":1,"successful":1,"skipped":0,"failed":0},"hits":{"total":1,"max_score":10.529836,"hits":[{"_index":"products104","_
… }
	
