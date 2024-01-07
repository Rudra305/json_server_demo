# json_server_demo 
* this will be practice repo for json server + react
* http://localhost:3000/products/1
# filtering
* http://localhost:3000/products?category=electronics
* http://localhost:3000/products?category=electronics&discount.type=shipping
# Sorting
* http://localhost:3000/products?_sort=price
* http://localhost:3000/products?_sort=price&_order=desc
* http://localhost:3000/products?_sort=price,category&_order=desc,asc
# Pagination
* http://localhost:3000/products?_page=1
* http://localhost:3000/products?_page=1&_limit=2
# Operators
* http://localhost:3000/products?price_gte=2000&price_lte=6000
* http://localhost:3000/products?id_ne=1
* http://localhost:3000/products?category_like=^f
# Full text Search 
* http://localhost:3000/products?q=in
# Relationships
* http://localhost:3000/products?_embed=reviews
* http://localhost:3000/products/1?_embed=reviews
* http://localhost:3000/reviews?_expand=product
* http://localhost:3000/reviews/1?_expand=product
# Post Request
* http://localhost:3000/products
# PUT, PATCH and DELETE Request


To generate random data we can use libraries such as Faker, casual and chancejs 
