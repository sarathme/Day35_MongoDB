# Tasks

## Q4. List the four product which are greater than 500 in price

### Query Command

```console
guvi> db.products.find({product_price:{$gte:500}})
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
    _id: ObjectId('66d06080837b8c46562710d7'),
    row_id: 2,
    product_name: 'Practical Fresh Sausages',
    product_price: 911,
    product_material: 'Cotton',
    product_color: 'indigo'
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
    _id: ObjectId('66d06080837b8c46562710dc'),
    row_id: 7,
    product_name: 'Practical Soft Shoes',
    product_price: 500,
    product_material: 'Rubber',
    product_color: 'pink'
  }
]
```
