# hall_booking

Heroku url: https://mongodb-hp.herokuapp.com

Method: post

/hallbooking/create-room = For creating a room 
{
noOfSeats: "",
amenities: "",
pricePerHour: ""
}


Method: post

/hallbooking/book-room = for booking a room (post)
{
customerName: "",
date:"",
startTime: "",
endTime: "",
roomId: "",
bookingStatus: "" (it could be yes or no)
}


Method: get

/hallbooking/all-rooms = for getting all rooms with booked data

Method: get

/hallbooking/all-customers - for getting all customers with booked data 
