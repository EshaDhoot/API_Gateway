FRONTEND -  MIDDLE-END - BACKEND

- We need an intermediate layer between the client side and the microservices.
- Using this middle-end, when client sends request we will be able to make decision that which microservice should actually respond to this request.
- We can do message validation, response transformation, rate limiting.
- We try to prepare an API Gateway that acts as this middle-end.
- Links to other Microservices Repo:
    - Flight and Search Service: ```https://github.com/EshaDhoot/FlightsAndSearchService```
    - Booking Service: ```https://github.com/EshaDhoot/Booking_Service```
    - Auth Service: ```https://github.com/EshaDhoot/Auth_Service```
    - Reminder Service: ```https://github.com/EshaDhoot/ReminderService```
