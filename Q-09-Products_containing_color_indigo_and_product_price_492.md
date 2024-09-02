# Tasks

## Q9. Find products which contain product color indigo and product price 492.00

### Query Command

```console
guvi> db.products.find({$and:[
  {product_color: {$eq: 'indigo'}},
  {product_price: {$eq: 492}}
]
})
```

### Shell Output

```sh
# No products which has a color indigo as well as price 492.00
```

## Find products which contain product color indigo or product price 492.00

I just tried to query products which has either color indigo or price 492.00

### Query Command

```console
guvi> db.products.find({$or:[
  {product_color: {$eq: 'indigo'}},
  {product_price: {$eq: 492}}
]
})
```

### Shell Output

```console
[
  {
    _id: ObjectId('66d06080837b8c46562710d7'),
    row_id: 2,
    product_name: 'Practical Fresh Sausages',
    product_price: 911,
    product_material: 'Cotton',
    product_color: 'indigo'
  },
  {
    _id: ObjectId('66d06080837b8c46562710d9'),
    row_id: 4,
    product_name: 'Gorgeous Plastic Pants',
    product_price: 492,
    product_material: 'Soft',
    product_color: 'plum'
  },
  {
    _id: ObjectId('66d06080837b8c46562710df'),
    row_id: 10,
    product_name: 'Generic Wooden Pizza',
    product_price: 84,
    product_material: 'Frozen',
    product_color: 'indigo'
  },
  {
    _id: ObjectId('66d06080837b8c46562710e6'),
    row_id: 17,
    product_name: 'Incredible Metal Car',
    product_price: 36,
    product_material: 'Fresh',
    product_color: 'indigo'
  },
  {
    _id: ObjectId('66d06080837b8c46562710ee'),
    row_id: 25,
    product_name: 'Licensed Steel Car',
    product_price: 20,
    product_material: 'Cotton',
    product_color: 'indigo'
  }
]
```
