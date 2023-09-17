## Mail Adapter Service

The scope for polling email looking for travel-related emails, filter and whitelist certain emails, parsing & create reservations data into Road Warrior App.
![Mail Adapter Service](../images/mail-adapter-microservice.png)

### Component
#### Mail Adapter Service
- Get a list of emails that the user has registered from user services
- Periodically fetches email messages from a specified email server or service
- Parse email content and save as reservation data
