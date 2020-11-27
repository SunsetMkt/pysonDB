<div align="center">
<img width="80%" src="https://drive.google.com/uc?export=view&id=1ULgadc21bf_p47MDfvW5OsCnGZsnVKm_">
</div>

***
<div align="center">

<h2>A simple,lightweight,efficent JSON based database for python.</h2>

</div>

<h2>Features</h2>

* Lightweight JSON based database.
* Supports CRUD commands.
* No Database drivers required.
* Unique ID assigned for each JSON document added.
* Strict about Schemma of data added. 
* Inbuilt CLI to delete,display,create JSON database.

```python
>> from pysondb import db
>> a=db.getDb("path/to/json.json")
>> a.addMany([{"name":"pysondb","type":"DB"},{"name":"pysondb-cli","type":"CLI"}])
>> a.getAll()
>> [{"name":"pysondb","type":"DB"},{"name":"pysondb-cli","type":"CLI"}]
```
See its simple..

<h4>Quick Links</h4>

* [Documentation]()
* [Install]()
* [Example Code]()
* [Command Line Operations]()
* [Adding Data]()
* [Get data]()
* [Update Data]()
* [Delete Data]()

<h4 id="install">Install</h4>

```python
pip install pysondb
```
<h4>Create a database</h4>

* You can create a database usinf CLI.
```bash
pysondb create database_name
```
* Or in the python file.

```python
from pysondb import db

a=db.getDb("db.json')
```

* The above piece of code will create a database with ``` {data:[]}``` in it.
* Even if the json file exists there is no problem.

<h4>Contributing</h4>

Whether reporting bugs, discussing improvements and new ideas or writing extensions: Contributions to TinyDB are welcome! Here's how to get started:

* Check for issues or open a issue or open a feature requests.
* Fork the repository on Github
* Create a new branch off the master branch.
* Write a test which shows that the bug was fixed or that the feature works as expected.
* Send a pull request to us and wait till it get merged.


 

