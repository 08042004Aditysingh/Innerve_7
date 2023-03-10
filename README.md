# Innerve_7

PROBLEM STATEMENT
1. Voice Based Travel Booking()
2. 5ireLabs Build Track()

##Team Members 
1. Ajay Singh 
2. Kumari Ladli 
3. Vikram Reniwal
4. Divya Prakash 

#The Application will allow users to book a hotel ticket using voice commands.
1. The system will ask travel details to the user like origin, destination, travel date, number of guests, etc.
2. The user will answer the queries and based on this he will get hotel suggestions(on other channel also like email/whatsapp).
3. The user will select a hotel and further enter his contact details like phone number, email address, etc.
4. The user will receive a payment link on his email address. (You may provide a dummy link of upi payment)
5. After successful payment he will be informed about the booking status whether it is booked or failed.

#SOLUTION

#To implement an Application that allows users to book a hotel ticket using voice commands, we are following these steps:
1. For prototyping and saving time, Instead of building our own NLP model. We’ll be using Google Speech-to-text API via react-speech-recognition.
2. When a user initiates the booking process, the application will ask for their travel details, such as the origin, destination, travel date, number of guests, etc.
3. The Application then uses Google Hotels API to search for available hotels that match the user's criteria. The system then provide the user with a list of hotel suggestions, either through the voice assistant or through other channels like email or WhatsApp using emailJS and whatsApp business API.
4. The user can then select a hotel from the list and provide their contact details, such as their phone number and email address. The application will store this information securely in SQL database and use it to send the user a payment link.
5. The application will be sending a payment link generated from Stripe (payment gateway) to the respective email address using Nodemailer.
6. After the payment is completed, the Application will inform the user whether the booking was successful or not. If there are any issues with the booking, such as a lack of availability or a problem with the payment, the application will provide clear and helpful feedback to the user.
7. Overall, the key to building a successful voice-based hotel booking application is to make the user experience as smooth and intuitive as possible.

#Tech-Stack
#Client : ReactJs
#Server : NodeJS, ExpressJs
#Database : MySQL
#APIs and Packages
1. react-speech-recognition
[https://www.npmjs.com/package/react-speech-recognition]
2. Travel Advisor Hotel's API
[https://rapidapi.com/apidojo/api/travel-advisor]
3. Geocoding API
[https://rapidapi.com/trueway/api/trueway-geocoding]
4. WhatsApp Business API Twilio
[https://www.twilio.com/whatsapp]
5. NodeMailer
[https://github.com/nodemailer/nodemailer]
6. Stripe Payment Gateway
[https://dashboard.stripe.com/test/payments]
#Architecture
![image](https://user-images.githubusercontent.com/93976634/224277552-7d12ae9a-5763-4c58-888a-aeec4d98af11.png)
#Demo Video
[high quality on Drive, Github only allows 10MB]()
#FUTURE ASPECT
#What are the future thoughts on the idea, how do you plan to upgrade this idea…..
1. Adding More Features to the application, For Example: Flight ticket using voice commands, Tour package bookings and Personalised tour facility.
2. Improving the User Interface, more similar to that of Udchalo.
3. By using natural language processing and clear feedback, we can ensure that users are able to book a hotel ticket quickly and easily, without having to navigate a complex user interface

