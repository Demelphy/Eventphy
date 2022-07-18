# Eventphy
A student proyect maked by Demelphy and supervised by ASantos.

This application have two sides.
If you are a company, you can:
- Manage your events
- Sell your tickets
- Check your simulated-bank balance

Otherwise, you can:
- Buy tickets for diferent events
- Check your simulated-bank balance

# Technologies, frameworks and tools
Java 17

# Modules
## Eventphy Banks
This microservice simulates a small group of banks. You need to create an account here with your personal data and the microservice will give you a card number and a bank account number to use it in Eventphy Users and Eventphy TPV.

## Eventphy Users
This microservice contains the user information. This system will have different roles that gives more or less functions.

## Eventphy Events
This microservice is the events management. If you are logged in as a Bussiness Account, you can create events. Otherwise you can get information about events and list events you bought a ticket.

## Eventphy TPV
This microservice is the gateway to pay tickets.

## Eventphy Back-end
This microservice is the core of the application. You can consume it through REST consumer like Swagger.

## Eventphy Front-end
This microservice consume Back-end microservice to give a user friendly interface.
