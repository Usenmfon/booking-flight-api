# FLIGHT BOOKING API DOCUMENTATION

## AVAILABLE ENDPOINTS ##
*Data are stored in an array of objects*

### Add/Book Flight ###
```
method: POST
endpoint: "http://localhost:3000/add/flight"
Sample entry data : 

    {
        title: "flight to florida",
        time: "5pm",
        price: 10000,
        date: "30-06-2022"
    }
```
### Get All Flights ###
```
method: GET
endpoint: "http://localhost:3000/all/flights"
response format: json
```

### Get A Single Flight ###
```
method: GET
endpoint: "http://localhost:3000/single/flight/{id}"
id = array index value
```
### Update/Edit Flight ###
```
method: PUT
endpoint: "http://localhost:3000/update/flight/{id}"
id = array index value
```
### Delete Flight ###
```
method: DELETE
endpoint: "http://localhost:3000/delete/flight/{id}"
id = array index value
```
### FLIGHT BOOKING ###
```
method: GET
endpoint: "http://localhost:3000"
sample reponse: "Flight Booking API"
```
