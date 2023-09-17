# Functional

This document contains the functional requirements based on the Kata session and the documents provided to all teams. You will find the actors we identified, and how they interact with the system in major scenarios.

## Actors
* Travelers
* Agency

## Road Warrior App

### Mail Scanner
* Poll email related reservations travel from mail services
* Parsing and create reservations in Road Warrior App
			
### Reservation Capturer
* Update reservation details from Agency
* Grouping reservations into Trip by City or Date
* Send Notification updates

### Trip Analytic
* Provide end-of-year summary trip reports to user
* Provide suggestions for user based on analytic engine

## User in Road Warrior App

### Account Management
* Self Registered as User
* Authentication using user id and password
* Update profile information
* Filter and whitelist certain emails

### Trip (Group of Réservation)
* Browse Reservations
* View Reservations details
* Add, update, or delete existing reservations manually
* Share trip as itinerary to social media (instagram, facebook, whatsapp etc)
* Get Notification from reservations updates
* Get end-of-year summary reports

## Agency in Road Warrior App
* Update travel details (delays, cancellations, updates, gate changes, etc.)