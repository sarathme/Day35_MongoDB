# Tasks

## Q10. Delete the products which product price value are 28

### Query Command

```console
guvi> db.products.deleteMany({product_price:{$eq:28}})
```

### Shell Output

```sh

{ acknowledged: true, deletedCount: 1 }

```

