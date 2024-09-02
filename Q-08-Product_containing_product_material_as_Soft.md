# Tasks

## Q8. Find all products which contain the value of soft in product material

### Query Command

```console
guvi> db.products.find({product_material:{$eq: 'Soft'}})
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
