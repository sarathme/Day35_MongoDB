# Tasks

## Q7. Find the product with a row id of 10

### Query Command

```console
guvi> db.products.find({row_id:{$eq:10}},{product_name:1,product_material:1})
```

### Shell Output

```console
[
  {
    _id: ObjectId('66d06080837b8c46562710df'),
    row_id: 10,
    product_name: 'Generic Wooden Pizza',
    product_price: 84,
    product_material: 'Frozen',
    product_color: 'indigo'
  }
]
```
