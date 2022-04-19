Page 1
List of city
> http://localhost:6700/location
> https://xomato-api.herokuapp.com/location
List of restaurants 
> http://localhost:6700/restaurants
> https://xomato-api.herokuapp.com/restaurants
restaurants wrt to city 
> http://localhost:6700/restaurants?state_id=4
> https://xomato-api.herokuapp.com/restaurants?state_id=4
quick search data  
> http://localhost:6700/mealType
> https://xomato-api.herokuapp.com/mealType


Page 2
restaurants wrt to quickSearch 
> http://localhost:6700/restaurants?meal_id=5
> https://xomato-api.herokuapp.com/restaurants?meal_id=5


filter
> cuisine filter
  data respect to cuisine and quickSearch 
  > http://localhost:6700/filter/3?cuisine=4
  > https://xomato-api.herokuapp.com/filter/4?cuisine=1
> cost filter
  > http://localhost:6700/filter/1?lcost=200&hcost=500
  > https://xomato-api.herokuapp.com/filter/1?hcost=1000&lcost=500
 data respect to cuisine and cost 
> cuisine filter + cost filter 
  > http://localhost:6700/filter/1?lcost=200&hcost=500&cuisineId=1
  > https://xomato-api.herokuapp.com/filter/1?lcost=200&hcost=500&cuisineId=1

> sort
    sort low to high in same quickSearch
    http://localhost:6700/filter/1?cuisineId=1&sort=1
    https://xomato-api.herokuapp.com/filter/1?cuisineId=1&sort=1
    sort high to low in same quickSearch
    http://localhost:6700/filter/1?cuisineId=1&sort=-1
    https://xomato-api.herokuapp.com/filter/1?cuisineId=1&sort=-1

> pagination
   > http://localhost:6700/filter/1?cuisineId=1&skip=2&limit=2
   > https://xomato-api.herokuapp.com/filter/1?cuisineId=1&skip=2&limit=2


Page 3
> restaurants details
> http://localhost:6700/details/2
> https://xomato-api.herokuapp.com/details/1

> Menu of that restaurants
> http://localhost:6700/menu/2
> https://xomato-api.herokuapp.com/menu/1


page 4
> menu items on user selection
  > localhost:6700/menuItem
  > https://xomato-api.herokuapp.com/menuItem
  > body [1,4,5]

> api to place order
  > localhost:6700/placeOrder
  > https://xomato-api.herokuapp.com/placeOrder

page 5
> list all order
  > http://localhost:6700/orders
  > https://xomato-api.herokuapp.com/orders
  > http://localhost:6700/orders?email=mia@gmail.com
  > https://xomato-api.herokuapp.com/orders?email=mia@gmail.com

Delete order 
> localhost:6700/deleteOrder
> https://xomato-api.herokuapp.com/deleteOrder
 

 update order
 > localhost:6700/updateOrder/61ffab62c39f96bf7ba39676?status=Success
 > https://xomato-api.herokuapp.com/updateOrder/61ffab62c39f96bf7ba39676?status=Success
 > localhost:6700/updateOrder/TEST_95860?status=Success
 > https://xomato-api.herokuapp.com/updateOrder/TEST_95860?status=Success