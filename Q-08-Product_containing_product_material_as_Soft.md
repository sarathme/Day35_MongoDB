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
    _id: ObjectId('66d06080837b8c46562710d9'),
    row_id: 4,
    product_name: 'Gorgeous Plastic Pants',
    product_price: 492,
    product_material: 'Soft',
    product_color: 'plum'
  },
  {
    _id: ObjectId('66d06080837b8c46562710e0'),
    row_id: 11,
    product_name: 'Unbranded Wooden Cheese',
    product_price: 26,
    product_material: 'Soft',
    product_color: 'black'
  },
  {
    _id: ObjectId('66d06080837b8c46562710e8'),
    row_id: 19,
    product_name: 'Intelligent Cotton Chips',
    product_price: 46,
    product_material: 'Soft',
    product_color: 'azure'
  }
]
```
