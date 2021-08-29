# Postman Assignment

Extraction of Data from public API's

## Steps To Run:
```
* Run pip install requirements.txt by moving command prompt to our project Directory
* After Installing the requirements Run postman.py
* It will extract the data and you can access it through your mysql shell by executing commands.
  * First you have to take it into sql mode so /sql.
  * Connect it to your database using /connect root@localhost and entering your sql password
  * Use Postman;
  * You can access the data by select * from allData where category = [category you wish to see]
```
### Prerequisites

What things you need to install the software and how to install them

```
Python
mysql 
```

### Installing

A step by step series of examples that tell you how to get a development env running


```
Run postman.py and you will start to see data getting extracted.
```

### Schema

```
* addData
  * Category
  * API
  * Description
  * Auth
  * HTTPS
  * CORS
  * Link
```

Attaching postman database for demo

### Points Achieved:


```
Followed concept of OOPS
Support for handling authentication requirements & token expiration of server
Support for pagination to get all data
Develop work around for rate limited server
Crawled all API entries for all categories and stored it in a mysql database
```



## Authors

* **Aish Kanodia** 
