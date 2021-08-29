# Postman Assignment

Extraction of Data from public API's

## Steps To Run:
1. Install Python dependencies
    ```
    pip install requirements.txt
    ```
2. Run postman.py
    ```
    python postman.py
    ```
    
    or 
    
    ```
    python3 postman.py
    ```
    

This would extract the data and you can access it through your mysql shell by executing commands:
- First you have to take it into sql mode so:
    ```
    /sql
    ```
- Connect it to your database using:
    ```
    /connect
    ```
    Use root@localhost and enter your sql password
- Use Postman
- Access the data by using the following command:
    ```
    select * from allData where category = [category you wish to see]
    ```
        
### Prerequisites

What things you need to install the software and how to install them

1. Python
2. mysql 

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

1. Followed concept of OOPS
2. Support for handling authentication requirements & token expiration of server
3. Support for pagination to get all data
4. Develop work around for rate limited server
5. Crawled all API entries for all categories and stored it in a mysql database


### If given More Days:

1. May provide With multiple types of Database Support like Mongodb, Postgres.
2. May Deploy it online for demonstration purpose.
3. Can add more features like gui support with flask.
4. Can add docker for single command application.


## Authors

* **Aish Kanodia** 
