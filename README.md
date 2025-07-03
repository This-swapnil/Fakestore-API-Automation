# Fakestore-API-Automation


Fake Store API is a free and open-source RESTful API that provides dummy e-commerce data for testing and prototyping frontend or backend applications. It mimics a real online store by offering endpoints for products, categories, users, and carts.

## Run Locally in Postman
- Clone the Project
```bash
git clone https://github.com/This-swapnil/Fakestore-API-Automation.git
```
- Import the global workspace json file 'workspace.postman_global.json'
- Import the collection in Postman you want to run [Products | User | Cart]
 - Download the csv data files [products_data.csv | user_data.csv | cart_data.csv]
 - Select the products collection and click on Run select the products_data.csv file and preview it once
 - Run the collection
 - Results will displayed with all the tests

## Run Locally using Newman
Dependencies

`Newman` `Nodejs` `newman-reporter-htmlextra`

- Clone the Project
```bash
git clone https://github.com/This-swapnil/Fakestore-API-Automation.git
```
- Go to the project directory

```bash
cd FakestoreAPIAutomation
```
- Go to specific collection directory
```bash
cd products_collection
```
- Run the collection using following command
```bash
newman run Products.postman_collection.json -d products_data.csv -g workspace.postman_globals.json
```
- For reports add the following 
```bash
newman run Products.postman_collection.json -d products_data.csv -g workspace.postman_globals.json -r htmlxtra
```

## Features

- GET, POST, PUT, PATCH, DELETE APIs Tested 
- API Test Automation
- RestAPIs Testing
- HTML Reporting
- Schema Validation
- Response data Validation
- Data driven tests 
- End-to-end tests 


## Developed using

- Postman
- JavaScript
- Newman
- Jenkins

## 🛠 Skills

`JavaScript` `Automation Testing` `API Testing` `Postman API Testing` `RESTapi` `Jenkins` `Newman` `Newman Html reports` 

