# Mobile-Ticketing-System-in-Bus-Project
Build NFC system for Ticketing and Identification of passengers in Public Transport such as 
Bus. So basically, passenger need to carry NFC card with them. As soon as they enter into the bus the Conductor will read the NFC tag using Android Cell phone. The cost would be automatically deduced according to distance travelled from departure to destination.

1. This is the first activity where the Conductor enter the details for authentication. Based on thedetails already stored in the smartphone, it will check if the provided information matches the details already stored in the smartphone. If matched it will go to the next activity. Thus the first activity simply shows the login procedure of the Conductor:

![picture alt](NFC%20images/Login%20Page.jpg "Login Page")

2. This is the Second activity where the Conductor enter the Wrong details for login,then Authentication error is occurred:
![picture alt](NFC%20images/Authentication%20Failed.png "Authentication Failed")

3. This is the Third activity where the Conductor get the Starting the page of the Application. This page show the Conductor Authentication has been done successful:

![picture alt](NFC%20images/Authentication%20Successful.png "Authentication Successful")

4. This is the Fourth activity where the Conductor Tap the Nfc Card of the Passenger for the Ticketing purpose. Nfc Card Detected And Conductor get all the details of the Passenger:

![picture alt](NFC%20images/NFC%20card%20detection.jpg "NFC card detection")

5. This is the Fifth activity where the Conductor book the ticket by clicking the Book Button and the Transaction is done Successfully once the ticket is booked:

![picture alt](NFC%20images/Transaction%20Successful.jpg "Transaction Successful")

6. This is the Sixth activity where the Admin has to log in with the details of self to update the details in the database. This is the Admin Log-in Page. If the details of the Admin is Wrong then Authentication will fail:

![picture alt](NFC%20images/Admin%20Login.png "Admin Login")

7. This is the Seventh activity where the Admin log–in into the system, once the Authentication is successful the Admin can Manage Conductors, Manage Passengers, Manage Ticket Fares:

![picture alt](NFC%20images/Admin%20Home%20Page.png "Admin Home Page")

8. This is the Eighth activity where the Admin update the details of the passengers. The Admin Add the new Passengers in the list. The Admin can update the details of the Passengers and also Delete the unwanted and outdated Passengersin the list:

![picture alt](NFC%20images/Manage%20Passenger.png "Manage Passenger")

9. This is the Nineth activity where the Admin can Add the new Tickets Fare.Admincan update the Ticket Fares and Also delete the Unwanted and Outdated Ticket Fares:

![picture alt](NFC%20images/Manage%20Ticket%20Fare.png "Manage Ticket Fare")
 
10. This is the Tenth activity where the Admin Stores the details of the Last Transactions of the Customers with the Date and Time.With the details of the last Transactions the Ticket Checkers can check the Ticket details of the Passengers:

![picture alt](NFC%20images/Passenger%20Log.jpg "Passenger Log")
