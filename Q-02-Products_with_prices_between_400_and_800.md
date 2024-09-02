# Tasks

## Q2. Find the product price which are between 400 to 800

### Query Command

```console
guvi> db.products.find({product_price:{$gte:400,$lte:800}})
```

### Shell Output

```console
[
  {
    _id: ObjectId('66d06080837b8c46562710d6'),
    row_id: 1,
    product_name: 'Intelligent Fresh Chips',
    product_price: 655,
    product_material: 'Concrete',
    product_color: 'mint green'
  },
  {
    _id: ObjectId('66d06080837b8c46562710d8'),
    row_id: 3,
    product_name: 'Refined Steel Car',
    product_price: 690,
    product_material: 'Rubber',
    product_color: 'gold'
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
    _id: ObjectId('66d06080837b8c46562710db'),
    row_id: 6,
    product_name: 'Awesome Wooden Towels',
    product_price: 474,
    product_material: 'Plastic',
    product_color: 'orange'
  },
  {
    _id: ObjectId('66d06080837b8c46562710dc'),
    row_id: 7,
    product_name: 'Practical Soft Shoes',
    product_price: 500,
    product_material: 'Rubber',
    product_color: 'pink'
  }
]
```
