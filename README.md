# SHT_ERP
für die Schnitte


API Endpoints

 - Login
   - POST /login/ -> Username / Password
      - Resp - Userinformations / Token
 - Customer
 - Product
 - Item
   - POST /item/ -> ORDER_NO .....
   - GET /items/ -> send CORDER_NO -> Get ITEMS from Customer
   - PUT /order/ -> send ORDER_NO -> Updates Order
 - Order
   - POST /order/ -> ORDER_NO .....
   - GET /orders/ -> send CUST_NO -> Get Orders from Customer
   - PUT /order/ -> send ORDER_NO -> Updates Order
