
Hit below url from postman with JSON option
URL: http://localhost:9192/order/bookOrder
Method: POST

{
    "order":{
        "id": 1,
        "name": "Pen",
        "qty": 5,
        "price": 5
    },
    "payment":{}
}