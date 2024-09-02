# Day 34 Task MongoDB

## Preparations

Inorder to do the task I just ran a local mongoDB server in my computer on
default PORT 27017.

### Creating and using a database

1. I have created a database called guvi and switched to the database with use
   command.

```console
test> use guvi
switched to db guvi
guvi>
```

### Add task data to collection

1. I have created a products collection and inserted the given products data
   into the collection using insertMany() collection method.

```console
guvi> db.products.insertMany(<provided_products_data>)
```
