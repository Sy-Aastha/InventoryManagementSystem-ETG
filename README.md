# InventoryManagementSystem-ETG
This Project is abt Inventory Management using Nosql Database{.json file} using Python. It is created during the internship under Elite Techno Group.   

## Description about project
IMS helps you to manage your inventory data and keep track of your sales record simultaneously.It also has a feature to mantain record of customer purchase details.

## Working
-Added new inventory to ProductRecord.json file. </br>
-Catalogue Display after reading json file </br>
-customer may purchase any number of item which is futher added to his card (if product "exist and is available") else it will display "not found" </br>
-his/her purchase get recorded in cust_record.json whenever purchase is done, with corresponding time of purchase{topr[]},transectionID[],TotalBill Amount[] </br>
-this product sale will also be reflected in sale_record.json {where all products have their record of sale with corresponding the time of purchase[],transectionID[],total quantity sold[] } </br>
-ProductRecord.json also have record of which product is sold or not and against which TransectionID[],saletime[] under sale{}. </br>

## json file Structure
#### ProductRecord
{ "1001": {"name": "","SP":,"quant":,"units": "Kg/L/pcs","exp-date": "","salerec": {"sale": true/false,"Salequant":,"saleTime":["","",],"transectionID": ["ce5a154f-e0a3-4bfa-8680-0ea8ae12af25"]}}}
#### Cut_Record
{"smith00":{"name": "smith","Ph.no": "00","purchase_rec": [],"topr": [],"transectio_id": [],"billAmount": []}}
#### sale_record
{"1111": {"name": "","SP":,"salerec": {"sale": true,"Salequant": 2,"saleTime": [],"transectionID": []}}}

## Feature
-Added item to invetory </br>
-catalogue display </br>
-chk new/existing customer in basis of name &phn </br>
-add item to cart </br> 
-bill after purchase </br>
-update all the json record. </br>

### Author

