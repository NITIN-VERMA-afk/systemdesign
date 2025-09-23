# add property

1 . HTTP method : post endpoint:v1/properties

2 . req body 
```json 
{
  "owner_id": "123",
  "name": "abc",
  "location": {
    "city": "Aspen",
    "state": "co",
    "country": "USA"
  },
  "description": "A charming cottage with stunning mountain views.",
  "price": "150",
  "availability": {
    "start": "date",
    "end": "date"
  },
  "amenities": ["wifi", "parking"],
  "type": "house",
  "images": [
    "image1.jpg",
    "image2.jpg"
  ]
}
```

# view Bookings

1 . http method :GET  Endpoint: /v1/owners/{owner_id}/bookings

#  search property

1 . http methodGETendpoint /v1/properties/search?city=Aspen

# View Property

1 . http method: GET  Endpoints: v1/properties/{propery_id}

# Book Property

1 . http method: POST  Endpoint:/v1/booking-sessions

2 . get 200 from server

3 . http method:post Endpoint:payment url
    httpbody-payment details

4 . status:201

5 . http method :post endpoint:/v1/bookings

6 . verify payment

7 . 201 confirm booking