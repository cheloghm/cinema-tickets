# cinema-tickets
The solution to the cinema tickets coding exercise is implemented in JavaScript.

##Cinema Ticket Service
This is a simple solution to model a cinema ticket service. The ticket service validates, calculates prices and processes purchases for cinema tickets.

Features
Validate Purchase Requests: Check if a purchase request is valid based on the number and type of tickets requested.

Calculate Total Price: Given the number of infant, child, and adult tickets, the service calculates the total price.

Calculate Seats to Reserve: Calculates the number of seats to reserve based on the ticket types. Note that infant tickets do not require a seat.

Process Purchase: Process a purchase if it is valid, which includes calculating the total price, reserving the seats, and making a payment.

Requirements
This service was designed to meet the following requirements:

Cannot process more than 20 tickets in a single request.

Cannot process child or infant tickets without adult tickets in the request.

Cannot process a request without tickets.

Please refer to the TicketService class for more details.

Install dependencies:
  npm install

Run tests:
  npm test
  
