---
layout: post
title: "Spring Blog 2 - CRUD Operations"
date: 2022-02-24 19:39:17 -700
categories: jekyll update
---

## CRUD Operations

In this blog, I will be discussing about the CRUD operations. While researching for the senior design project, I read and learned about the CRUD operations. It is an interesting topic, and I learned this while I was researching this for the front end side of the application. 

### What is CRUD?
CRUD is the four basic functions in storage operations. The acronym stands for Create, Read, Update, and Delete. When building APIs-the model should perform these four basic types of functionality in order to be complete. 
These are how the functions work:

- Create -  A function where a new entry is being added.  
- Read - This function would be called to see all the entries. It would retrieve and display the entries. 
- Update - The update function calls when an existing entry must be edited. It would supply the new values for the field and would later contain the new fields. 
- Delete - This function would call to remove an entry from the storage. The function would supply one or more fields to identify the entry, and later would be removed from the storage. 
    
### Restful APIs

In the REST environment, CRUD corresponds to the HTTP methods POST, GET, PUT, and DELETE

![CRUD-Restful APIs](/assets/images/crud-restful-api.png)
    
### MongoDB CRUD Operations
- Create Operations:
  - Create operations add new documents to a collection. If the collection doesn't exist, insert operations will create the collection. MongoDB provides these methods to add documents:
    - `db.collection.insertOne()`
    - `db.collection.insertMany()`

- Read Operations: 
  - Retrieve documents from a collection. The method to read documents from a collection is:
    - `db.collection.find()`
    - You can specify a criteria that identify the documents to return. 
    
- Update Operations:
  - Edit existing documents in a collection. These methods are:
    - `db.collection.updateOne()`
    - `db.collection.updateMany()`
    - `db.collection.replaceOne()`
    - You can specify a criteria that identify the documents to update. 

- Delete Operations:
  - Remove documents from a collection. The methods are:
    - `db.collection.deleteOne()`
    - `db.collection.deleteMany()`
    - You can specify a criteria that identify the documents to remove

For more information: [MongoDB CRUD Operations](https://docs.mongodb.com/v4.2/crud/)