# Tasks

## Q7. Find only the product name and product material

### Query Command

```console
guvi> db.products.find({row_id:{$eq:10}},{product_name:1,product_material:1})
```

### Shell Output

```console
[
  {
    _id: ObjectId('66d06080837b8c46562710df'),
    product_name: 'Generic Wooden Pizza',
    product_material: 'Frozen',

  }
]
```
